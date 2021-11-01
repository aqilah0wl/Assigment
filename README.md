# Assigment
Terdapat dua project di dalam repository ini

## 1. Project Decode UDP Header
> [Decode_udpHeader.ipynb](https://github.com/aqilah0wl/Assigment/blob/main/Decode_udpHeader.ipynb)

Project Decode UDP Header ini merupakan project yang berisi fungsi-fungsi untuk mengubah UDP header menjadi informasi-informasi yang lebih mudah dimengerti.Project ini dibuat menggunakan Google Collabs dengan bahasa pemograman Python.

**Cara penggunaan:** 
1. Inputkan UDP Header hexadesimal dengan tipe string ke fungsi decodeHeader.

```
decodeUdpHeader(udpHeader)
```

[Contoh input Decode UDP Header](https://drive.google.com/file/d/1flecyJk85WAWZT-5SbL-5CCW-u_-SFUn/view?usp=sharing)

[Contoh output Decode UDP Header](https://drive.google.com/file/d/1xW4yhvO4MoZ1CKaZpgYqMNbY4bizMuwN/view?usp=sharing)


## 2. Project Algoritma Djikstra
> [Dijkstra's_Algorithm.ipynb](https://github.com/aqilah0wl/Assigment/blob/main/Dijkstra's_Algorithm.ipynb)

Project Algoritma Dijkstra ini merupakan project yang berisi algoritma untuk mencari jarak terpendek dalam rangka menghubungkan semua simpul dalam satu graf. Algoritma ini biasanya terdapat pada maps untuk mencari jarak terdekat dari satu lokasi ke lokasi lainnya. Project ini dibuat menggunakan Google Collabs dengan bahasa pemograman Python.

**Cara penggunaan:**
1. Buat dan inisiasi graf dengan jumlah node
2. Tambahkan node-node ke dalam graf beserta jaraknya 
3. Panggil fungsi dijkstra
4. Outputkan hasilnya

```
g = Graph(jumlah_node)
g.add_edge(node_satu, node_dua, jarak_node)
D = g.dijkstra(node_awal)
for vertex in range(len(D)):
    print("Distance from vertex 0 to vertex", vertex, "is", D[vertex])
```

[Contoh membuat graf dan menambahkan node](https://drive.google.com/file/d/1UWqsPkZ9nsLkyyXWfuvWZZT7vL9vbCIg/view?usp=sharing)

[Contoh menggunakan fungsi dijkstra](https://drive.google.com/file/d/1_N_Pjr6wnYWWjHolkjViz0D11sTpXmEW/view?usp=sharing)

[Contoh output Decode UDP Header](https://drive.google.com/file/d/1qyFQY8iirz8VlXV8lKqjD5cbJSnR1OfM/view?usp=sharing)
