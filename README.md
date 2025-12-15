\# Notepad Application



Modern bir Windows Forms tabanlı Notepad. Metin düzenleme, RTF desteği, biçimlendirme araçları, dosya açma/kaydetme, geri alma/yeniden yapma işlemleri ve çok daha fazlasını sunar.



---



\## 🚀 Açıklama



Bu proje, C# ve Windows Forms kullanılarak geliştirilmiş bir Notepad uygulamasıdır. Kullanıcı dostu arayüzü ve temel/orta seviye metin editörü özellikleri sayesinde standart Notepad'e gelişmiş bir alternatif sunar.



---



\## ✨ Özellikler



\* \*\*Yeni belge, aç, kaydet, farkı kaydet\*\* işlemleri

\* \*\*TXT ve RTF\*\* format desteği

\* Gerçek zamanlı \*\*Undo / Redo\*\* (Geri Al – İleri Al)

\* \*\*Font değiştirme, renk seçme\*\*, kalın/italik/altı çizili/üstü çizili stilleri

\* \*\*Kes / Kopyala / Yapıştır\*\* özellikleri (Context Menu + Toolbar)

\* \*\*Tarih/Saat ekleme\*\*

\* Caps Lock durum göstergesi

\* Dosya değişiklik uyarı sistemi

\* ToolStrip ve StatusStrip entegrasyonları



---



\## 🛠 Kullanılan Teknolojiler



\* \*\*C# (.NET Framework)\*\*

\* \*\*Windows Forms (WinForms)\*\*

\* System.IO

\* RichTextBox bileşeni

\* Dialog bileşenleri (OpenFileDialog, SaveFileDialog, FontDialog, ColorDialog)



---



\## 📦 Kurulum ve Çalıştırma



1\. Proje dosyalarını indirin veya klonlayın:



&nbsp;  ```bash

&nbsp;  git clone https://github.com/firatysrgl/Notepad

&nbsp;  ```

2\. Visual Studio ile açın.

3\. Çözümü derleyin (Build).

4\. Uygulamayı çalıştırın (Start).



---



\## ▶️ Kullanım



\* Menü veya toolbar üzerinden \*\*Yeni\*\*, \*\*Aç\*\*, \*\*Kaydet\*\* işlemlerini kullanabilirsiniz.

\* Biçimlendirme menüsünden font ayarı yapabilir veya kısayollardan stil uygulayabilirsiniz.

\* Sağ tık menüsünden kes/kopyala/yapıştır işlemlerini hızlıca uygulayabilirsiniz.



---



\## 🔍 Teknik Detaylar



\* `fileAlreadySave` ve `fileUpdated` değişkenleriyle dosyanın durumu takip edilir.

\* TXT dosyaları \*\*PlainText\*\*, RTF dosyaları \*\*RichText\*\* olarak kaydedilir.

\* Undo/Redo kontrolü hem menü hem de toolbar ile entegredir.

\* FontDialog APPLY event'i ile gerçek zamanlı önizleme uygulanır.



---



\## 👨‍💻 Geliştirici



\*\*Fırat Yunus Yaşaroğlu\*\*

GitHub: https://github.com/firatysrgl

LinkedIn: https://www.linkedin.com/in/firat-yunus-yasaroglu/







