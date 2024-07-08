# Perbandingan-Algoritma-Prim-dan-Kruskal
Proyek ini mengeksplorasi dan membandingkan dua algoritma utama dalam mencari Minimum Spanning Tree (MST) pada graf berbobot: Algoritma Prim dan Algoritma Kruskal.
Minimum Spanning Tree (MST) adalah struktur pohon yang menghubungkan semua simpul dalam graf dengan bobot minimum tanpa membentuk siklus. Algoritma Prim dan Algoritma Kruskal adalah dua pendekatan utama untuk menemukan MST:

- **Algoritma Prim**: Memulai dari sebuah simpul dan menambahkan simpul terdekat hingga seluruh graf terhubung.
- **Algoritma Kruskal**: Mengurutkan semua tepi berdasarkan bobot dan menambahkan tepi terkecil yang tidak membentuk siklus.

### Tujuan
1. Menganalisis konsep Minimum Spanning Tree (MST).
2. Membandingkan dan mengevaluasi kinerja relatif Algoritma Prim dan Algoritma Kruskal.
3. Mengevaluasi kompleksitas waktu dan ruang dari kedua algoritma.

## Metode

### Minimum Spanning Tree (MST)
MST adalah struktur pohon yang mencakup semua simpul dalam graf berbobot dan memiliki bobot total minimum tanpa membentuk siklus.

### Algoritma Prim
- Memilih simpul awal dan menambahkan simpul terdekat yang belum terhubung.
- Kompleksitas waktu: O(V^2) atau O(E log V) tergantung pada representasi graf.

### Algoritma Kruskal
- Mengurutkan semua tepi dan menambahkan tepi terkecil yang tidak membentuk siklus.
- Kompleksitas waktu: O(E log E) atau O(E log V) dengan struktur data Union-Find.

## Hasil dan Analisis

### Analisis Kompleksitas
- **Algoritma Prim**: Kompleksitas waktu O(V^2) atau O(E log V) tergantung pada representasi graf (matriks bobot atau daftar tetangga).
- **Algoritma Kruskal**: Kompleksitas waktu O(E log E) atau O(E log V) dengan Union-Find.

### Implementasi pada Graf Jarang dan Graf Padat
- Implementasi dan evaluasi kinerja pada graf jarang dan padat.
- Perbandingan waktu eksekusi dan penggunaan memori.

### Hasil Implementasi
- Pada graf jarang, Algoritma Prim dan Kruskal menghasilkan MST dengan bobot yang sama namun dengan cara berbeda.
- Pada graf padat, Algoritma Kruskal tetap stabil dengan mengurutkan tepi terkecil, sedangkan Algoritma Prim menunjukkan variasi pada jumlah MST yang ditampilkan.

| Algoritma       | Waktu Eksekusi | Penggunaan Memori | Kompleksitas Waktu   |
|-----------------|----------------|-------------------|----------------------|
| Algoritma Prim  | 0.00099 Detik  | 445920.0 KB       | O(E log V)           |
| Algoritma Kruskal| 0.420 Detik    | 554100.0 KB       | O(E log E + E log V) |
