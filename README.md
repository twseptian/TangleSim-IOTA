# Implementasi dan perbandingan TSA (Algoritma Pemilihan Tips) yang berbeda untuk cryptocurrency IOTA
- IOTA : www.descryptions.com/Iota.pdf
- G-IOTA : https://ieeexplore.ieee.org/document/8845163
- E-IOTA : https://ieeexplore.ieee.org/document/9223294

Proyek ini didasarkan pada git berikut: https://github.com/richardg93/TangleSim dan karena itu memerlukan perangkat lunak OMNeT ++ untuk mensimulasikan Tangle (lihat https://blog.iota.org/the-tangle-an-illustrated-introduction-4d5eae6fe8d4/). 
Beberapa perubahan telah dilakukan untuk itu (tampilan dengan graphviz, file log, benchmark, implementasi dari TSA yang berbeda).

File Tangle.cc, Tangle.h, TangleModules.cc, TangleSim.ned dan omnetpp.ini adalah file sumber yang diperlukan untuk dapat mensimulasikan TSA yang berbeda dengan OMNeT ++.
Folder data berisi file log, statistik kinerja untuk skrip TSA, .dot display (graphviz) dan Python yang berbeda:
- Stats.py memungkinkan Anda untuk rata-rata kinerja TSA melalui file log di folder log.
- Notebook TSAResult.ipynb memungkinkan Anda untuk melakukan barplot untuk membandingkan kinerja TSA yang berbeda.
- TangleGen.py memungkinkan Anda untuk menampilkan Tangle berkode warna di folder im. Ini menggunakan file log dari folder Traking.
RTracking berisi file log dari git referensi.
Untuk detail selengkapnya lihat laporan: https://github.com/T-amairi/Implementation-of-different-TSA-for-IOTA/blob/main/Compte%20Rendu.pdf.