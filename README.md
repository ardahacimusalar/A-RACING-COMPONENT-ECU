https://ardahacimusalar.github.io/A-RACING-COMPONENT-ECU/
---------------------------------------------------------
🏎️ A-RACING Component & ECU Systems (Web Interface)
Bu proje, yüksek performanslı araç modifikasyonu ve ECU yazılım hizmetleri sunan A-RACING markası için geliştirilmiş modern, dinamik ve kullanıcı odaklı bir web arayüzü çalışmasıdır.

Proje, "Dark Mode" (Karanlık Tema) prensipleriyle tasarlanmış olup, CSS3'ün gücü (Flexbox, Grid, Keyframe Animations) ve Vanilla JavaScript'in etkileşim yetenekleri kullanılarak geliştirilmiştir. Ziyaretçilere premium bir garaj hissiyatı vermeyi amaçlayan bu arayüz, responsive (duyarlı) yapısıyla tüm cihazlarda kusursuz görüntülenir.

🚀 Öne Çıkan Özellikler
Premium Dark UI: Otomotiv dünyasının agresif ve şık yapısını yansıtan, göz yormayan siyah zemin üzerine "Marka Kırmızısı" (#e74c3c) aksan kullanımı.

CSS3 Advanced Animations:

3D Flip Cards: Ekip sayfasında CSS perspective ve rotateY kullanılarak hazırlanan, arkalı önlü dönebilen 3 boyutlu kart yapısı.

Slide-Up Effects: Hover (üzerine gelme) durumunda alttan kayarak açılan detay panelleri.

Micro-Interactions: Butonlar ve linkler üzerinde yumuşak geçişli (transition) hover efektleri.

İnteraktif JavaScript Bileşenleri:

Accordion Menü: Stage 4 paketindeki yoğun teknik veriyi (MoTeC ECU, Telemetry vb.) karmaşa yaratmadan sunan, açılır-kapanır liste yapısı.

Social Dropdown: "İletişime Geç" butonlarına entegre edilmiş, tıklandığında açılan dinamik sosyal medya ikonları.

Responsive Grid Mimarisi: CSS Grid ve Flexbox kullanılarak oluşturulan, ekran boyutuna göre otomatik hizalanan hizmet ve paket kartları.

Semantik HTML5: SEO dostu ve tarayıcı uyumlu etiket yapısı.

🛠️ Teknoloji Stack'i
Dil: HTML5, CSS3, JavaScript (ES6+)

İkon Seti: FontAwesome 6.4.0

Fontlar: Google Fonts (Orbitron & Roboto)

Tasarım Mimarisi: Mobile-First, Flexbox & Grid Layouts

📂 Proje Yapısı
Plaintext
├── assets/                  # (Opsiyonel) Resim ve ikon dosyaları
│   ├── motor.png
│   ├── arda-profil.png
│   └── sertifika.png
├── index.html               # Ana Sayfa (Landing Page - Hero & Services)
├── team.html                # Ekip Sayfası (3D Flip Cards & Slide Effects)
├── task2.html               # Paketler & Fiyatlandırma (Accordion System)
├── style.css                # Tüm stillerin ve animasyonların bulunduğu merkezi stil dosyası
└── README.md                # Proje dokümantasyonu

💻 Sayfa Detayları ve Mühendislik Yaklaşımı
1. Ana Sayfa (index.html)
Kullanıcıyı karşılayan "Hero Section", linear-gradient ve arka plan görselleriyle zenginleştirilmiştir. Hizmetler bölümü (ECU Remap, Dyno Test), "Hover State" durumunda belirginleşen kartlarla sunulmuştur.

2. Paketler Sayfası (task2.html)
Bu sayfada, farklı müşteri segmentlerine (Street, Sport, Track) hitap eden paketler listelenir.

Mühendislik Çözümü: Özellikle "Stage 4" paketi çok fazla teknik detay içerdiği için, kullanıcı deneyimini bozmamak adına JavaScript tabanlı Akordiyon (Accordion) yapısı geliştirilmiştir. Bu sayede veriler kategorize edilerek (Örn: Soğutma, Elektronik) sunulmuştur.

Popular Card: "Stage 2" paketi CSS ile vurgulanmış (scale ve box-shadow) ve satış odaklı bir hiyerarşi kurulmuştur.

3. Ekip Sayfası (team.html)
Statik bir tanıtımdan öte, etkileşimli bir deneyim sunar.

Flip Effect: preserve-3d ve backface-visibility özellikleri kullanılarak kartların arkasında teknik yetkinlikler ve sertifikalar gizlenmiştir.

⚙️ Kurulum ve Çalıştırma
Bu proje statik web teknolojileri ile geliştirildiği için herhangi bir derleyiciye veya sunucu kurulumuna (Node.js, Python vb.) ihtiyaç duymaz.

Projeyi Klonlayın:

Bash
git clone https://github.com/ardahacimusalar/A-RACING-COMPONENT-ECU.git
Çalıştırın: Klasör içerisindeki index.html dosyasına çift tıklayarak tarayıcınızda açmanız yeterlidir.

👨‍💻 Geliştirici
Arda Hacımusalar

Computer Engineering Student @ Düzce University

LinkedIn: https://www.linkedin.com/in/ardahacimusalar/
GitHub: https://github.com/ardahacimusalar
