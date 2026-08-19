# Quantan Atlas

Kuantum bilişim, Python programlama ve kuantum algoritmaları üzerine kapsamlı görsel rehber ve laboratuvar platformu.

Bu repo, [quantanatlas.com](https://quantanatlas.com) sitesinin tüm kaynak kodlarını, interaktif öğrenme içeriklerini ve kuantum bilişim laboratuvarını barındırmaktadır. Python temellerinden ileri kuantum algoritmalarına, Qiskit'ten PennyLane'e kadar uçtan uca bir kuantum bilişim ekosistemi sunar.

## 🌟 İçerik Kategorileri (Bu Repoda Neler Var?)

Bu repo, kuantum bilişim ve Python programlama dünyasında kapsamlı bir kaynak merkezidir:

- **🐍 Python ve Programlama:**
  - **Temel Python:** Değişkenler, kontrol akışı, fonksiyonlar, modüller, OOP.
  - **İleri Python:** Dekoratörler, jeneratörler, async/await, tip ipuçları, metaprogramlama.
  - **Kuantum Python Altyapısı:** Sanal ortamlar, Jupyter, NumPy, PyTorch ile bilimsel yığın, test ve belgelendirme.

- **📚 Kütüphaneler ve Çerçeveler:**
  - **Qiskit:** Devre modelleri, kuantum bilgi (Clifford, Pauli, Statevector), gürültü ve hata azaltma, transpiler ve donanım eşlemesi, Aer simülasyonu, runtime ve ilkel API'ler, kuantum görselleştirme, algoritma araçları (VQE, QAOA, Grover, faz tahmini).
  - **PennyLane:** QNode mimarisi, differentiable quantum programming, optimizörler, şablonlar ve Lightning hızlandırma.
  - **Cirq:** Devre ve grid yapısı, simülatörler, donanım bağlantıları.
  - **PyTorch:** Tensör işlemleri, autograd, kuantum-klasik hibrit modeller.
  - **Diğer:** TensorFlow Quantum, OpenQASM, ProjectQ.

- **🔬 Kuantum Bilgisayar ve Fizik:**
  - **Kuantum Hesaplama:** Kübit ve Bloch küresi, kuantum kapıları, ölçüm ve çökme, donanım mimarileri (süperiletken transmon, iyon tuzakları).
  - **Kuantum Mekaniği:** Hilbert uzayı, postülatlar, dolanıklık, Bell eşitsizlikleri, dekoherens.
  - **Hata ve Gürültü:** Kanal modelleri (Kraus, T1/T2), hata azaltma stratejileri.

- **🧠 Algoritmalar (40+ implementasyon):**
  - **Bell ve İletişim:** Bell durumu, swap testi, kuantum teleportasyon, GHZ, W durumu, süper yoğun kodlama, BB84 (Qiskit ve Cirq).
  - **Deutsch–Jozsa ve Oracle:** Deutsch–Jozsa, Bernstein–Vazirani, Simon (Qiskit).
  - **Grover ve Arama:** Grover araması, genlik güçlendirme, kuantum sayımı (Qiskit).
  - **QFT ve Faz:** Kuantum Fourier dönüşümü, kuantum faz tahmini (Qiskit ve Cirq).
  - **Shor Algoritması:** Sıra bulma, modüler üs alma, periyot alt-devreleri, sürekli kesir sonrası işleme (Qiskit).
  - **Varyasyonel Optimizasyon ve QML:** QAOA, QSVM (Qiskit); VQC, QAOA, QNN (PennyLane).
  - **Rastgelelik ve Dinamik:** Kuantum rastgele sayı üreteci, kuantum yürüyüşü (Qiskit).
  - **Hata Düzeltme ve Kodlama:** 3 kübit bit/phase flip kodları, Shor 9-kübit kodu, stabilizer formalizmi, sendrom ölçümü, yüzey kodu sezgisi (Qiskit).

## 🚀 Canlı Demo & Modüller

Projeyi ve tüm alt modülleri keşfetmek için aşağıdaki linkleri kullanabilirsiniz:

| Kategori | Açıklama | Canlı Link |
| :--- | :--- | :--- |
| 🏠 **Ana Sayfa** | Tüm içeriklerin ana üssü | [quantanatlas.com](https://quantanatlas.com) |
| 🐍 **Python Temelleri** | Python'a giriş, değişkenler, kontrol akışı, fonksiyonlar | [Python Nedir?](https://quantanatlas.com/pages/python_programming/basic_python/introduction/what-is-python.html) |
| 📚 **Qiskit Devre Modeli** | Kuantum devre yapısı, kapılar, register sistemleri | [Quantum Circuit Structure](https://quantanatlas.com/pages/quantum-libraries-and-frameworks/qiskit/circuit-model/quantum-circuit-structure.html) |
| 🔬 **Kuantum Hesaplama** | Kübit, Bloch küresi, kuantum kapıları ve ölçüm | [Qubit ve Bloch Küresi](https://quantanatlas.com/pages/quantum-computing-and-physics/quantum-computing/fundamental-concepts/qubit-and-bloch-sphere.html) |
| 🧠 **Grover Algoritması** | Kuantum arama algoritması ve genlik güçlendirme | [Grover Search](https://quantanatlas.com/pages/quantum_algorithms/grover-search/qiskit/grover-search.html) |
| ⚛️ **Shor Algoritması** | Çarpanlara ayırma algoritması ve sıra bulma | [Shor Algoritması](https://quantanatlas.com/pages/quantum_algorithms/shor/qiskit/shor.html) |
| 🔗 **Kuantum Teleportasyon** | Bell durumları ile ışınlama protokolü | [Quantum Teleportation](https://quantanatlas.com/pages/quantum_algorithms/bell-and-communication/qiskit/quantum-teleportation-protocol-qiskit.html) |

> 💡 *Tüm modüller doğrudan tarayıcıda çalışır, herhangi bir kurulum gerektirmez.*

## 🛠️ Kullanılan Teknolojiler

- **Temel:** HTML5, CSS3, JavaScript (ES6+)
- **Programlama Dili:** Python (rehber içerikleri)
- **Kuantum Kütüphaneleri:** Qiskit, PennyLane, Cirq, PyTorch, TensorFlow Quantum (rehber içerikleri)
- **Mimari:** Modüler JavaScript, Sidebar tabanlı dinamik içerik yönetimi

## 📂 Projeyi Çalıştırma

Projeyi klonlayın:

```bash
git clone https://github.com/code-town3/quantan-atlas.git
