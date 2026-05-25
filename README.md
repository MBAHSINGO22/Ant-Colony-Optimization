<h1 align="center">Ant Colony Optimization (ACO) with Random Initialization</h1>

<p align="center">
  Implementasi algoritma Ant Colony Optimization (ACO) menggunakan Python untuk optimasi pencarian jalur ada dataset Berlin52
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python">
  <img src="https://img.shields.io/badge/Optimization-ACO-green?style=for-the-badge">
  <img src="https://img.shields.io/badge/Jupyter-Notebook-orange?style=for-the-badge&logo=jupyter">
  <img src="https://img.shields.io/badge/Status-Completed-success?style=for-the-badge">
</p>

<hr>

<h2>📌 Tentang Project</h2>

<p>
Project ini merupakan implementasi algoritma <b>Ant Colony Optimization (ACO)</b> menggunakan Python dan Jupyter Notebook.
Algoritma ACO terinspirasi dari perilaku koloni semut dalam menemukan jalur tercepat menuju sumber makanan melalui mekanisme jejak feromon.
</p>

<p>
Pada project ini digunakan pendekatan random initialization untuk mensimulasikan pencarian jalur optimal secara dinamis pada proses optimasi.
</p>

<hr>

<h2>🎯 Tujuan Project</h2>

<ul>
  <li>Mengimplementasikan algoritma Ant Colony Optimization</li>
  <li>Mensimulasikan perilaku pencarian jalur semut</li>
  <li>Mencari solusi optimal berdasarkan probabilitas feromon</li>
  <li>Menganalisis proses optimasi jalur</li>
  <li>Mempelajari konsep swarm intelligence</li>
</ul>

<hr>

<h2>🛠 Teknologi yang Digunakan</h2>

<ul>
  <li>Python</li>
  <li>NumPy</li>
  <li>Matplotlib</li>
  <li>Random Library</li>
  <li>Jupyter Notebook</li>
</ul>

<hr>

<h2>⚙️ Fitur Utama</h2>

<ul>
  <li>Implementasi algoritma ACO</li>
  <li>Random path initialization</li>
  <li>Perhitungan probabilitas jalur</li>
  <li>Update nilai feromon</li>
  <li>Simulasi iterasi koloni semut</li>
  <li>Pencarian jalur optimal</li>
  <li>Visualisasi proses optimasi</li>
</ul>

<hr>

<h2>📂 Struktur Project</h2>

<pre>
project-folder/
│
├── aco2random.ipynb
└── README.md
</pre>

<hr>

<h2>🚀 Instalasi</h2>

<p>Clone repository:</p>

<pre>
git clone https://github.com/MBAHSINGO22/Ant-Colony-Optimization.git
</pre>

<p>Masuk ke folder project:</p>

<pre>
cd nama-repository
</pre>

<p>Install dependency:</p>

<pre>
pip install numpy matplotlib
</pre>

<hr>

<h2>▶️ Cara Menjalankan</h2>

<ol>
  <li>Buka file <b>aco2random.ipynb</b> menggunakan Jupyter Notebook atau Google Colab</li>
  <li>Jalankan seluruh cell notebook secara berurutan</li>
  <li>Amati proses simulasi pencarian jalur</li>
  <li>Lihat hasil jalur optimal yang ditemukan algoritma</li>
</ol>

<hr>

<h2>🧠 Konsep Algoritma</h2>

<p>
Algoritma ACO bekerja dengan memanfaatkan:
</p>

<ul>
  <li><b>Feromon</b> → penanda jalur yang ditinggalkan semut</li>
  <li><b>Probabilitas</b> → menentukan kemungkinan pemilihan jalur</li>
  <li><b>Evaporasi Feromon</b> → mengurangi nilai feromon agar eksplorasi tetap terjadi</li>
  <li><b>Optimasi Iteratif</b> → mencari solusi terbaik melalui banyak iterasi</li>
</ul>

<hr>

<h2>💻 Contoh Kode</h2>

<pre>
pheromone = np.ones((num_nodes, num_nodes))

probability = (
    pheromone[current_node] ** alpha
) * (
    (1 / distance[current_node]) ** beta
)
</pre>

<hr>

<h2>📊 Output Project</h2>

<ul>
  <li>Jalur terbaik hasil optimasi</li>
  <li>Total jarak optimal</li>
  <li>Visualisasi proses pencarian jalur</li>
  <li>Perubahan nilai feromon setiap iterasi</li>
</ul>

<hr>

<h2>📈 Pengembangan Selanjutnya</h2>

<ul>
  <li>Integrasi dataset Traveling Salesman Problem (TSP)</li>
  <li>Visualisasi jalur secara real-time</li>
  <li>Optimasi parameter algoritma</li>
  <li>Implementasi GUI interaktif</li>
  <li>Perbandingan performa dengan algoritma optimasi lain</li>
</ul>

<hr>

<h2>👨‍💻 Author</h2>

<p>
Eugenius Kriswinar Adi Cahya
</p>

<hr>

<h2>📄 License</h2>

<p>
Project ini dibuat untuk kebutuhan pembelajaran, penelitian, dan pengembangan algoritma optimasi.
</p>
