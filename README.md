# Quizlerr App

Bu proje, Python'da geliştirilen basit ve etkili bir quiz uygulamasıdır. Uygulama tkinter ile grafik arayüz kullanır ve soruları Open Trivia DB API üzerinden çeker. Kullanıcıya bilgisayar bilimleriyle ilgili teknik sorular sorar ve doğru/yanlış seçenekleriyle cevap alır.

![image](https://github.com/user-attachments/assets/e8bf045a-19ae-49de-82be-1e6bbd2e3f12)

## ✨ Özellikler

* Tkinter tabanlı modern grafik arayüz
* Open Trivia DB API'den JSON formatında soru alma
* Bilgisayar bilimleri kategorisinde teknik sorular
* Geribildirim renkleriyle doğruluk kontrolü
* Skor takibi ve quiz sonu mesajı

## 📆 Gereksinimler

* Python 3.7+
* `requests` paketi

Kurmak için:

```bash
pip install requests
```

## ⚙️ Nasıl Çalışır?

1. `question_data` verisi API'den alınır.
2. Her soru bir `Question` nesnesine dönüştürülür.
3. `QuizBrain` bu soruları yönetir.
4. `QuizInterface` tkinter ile kullanıcıya soruları gösterir.
5. Kullanıcı "True" veya "False" tuşlarıyla cevap verir.
6. Skor artar, arayüzde geribildirim rengi görünür.

## 📲 Ekran Görünütüsü

(Tkinter arayüzü üzerinden soru ve cevap ekranı görünür)

## ⚡️ Geliştirme Fikirleri

* Zorluk seviyesi secimi
* Kategori seçimi
* Süreli quiz modu
* Skorları dosyaya kaydetme

## 👁‍🔍 Kaynaklar

* [Open Trivia DB API](https://opentdb.com/api_config.php)
* [Tkinter Belgeleri](https://docs.python.org/3/library/tkinter.html)

## ✊ Katkı

Her türlü öneri ve katkıya açığız! Pull request veya issue oluşturabilirsiniz.
