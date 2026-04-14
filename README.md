# NLP-text-classification-summarization
# 🚀 NLP: Text Classification Project

<p align="center">
  <img src="YOUTUBE_LOGO_URL_MANA_SHU_YERGA" width="150" alt="@MachineLearning_uz">
  <br>
  <b>MachineLearning_uz YouTube kanali maxsus loyihasi</b>
</p>

---

## 📝 Loyiha haqida
Ushbu loyihada zamonaviy **NLP (Natural Language Processing)** usullari, xususan **Transformer** arxitekturasiga asoslangan **DistilBERT** modeli yordamida matnlarni klassifikatsiya qilish amalga oshirilgan. Loyiha doirasida ikkita turli xil vazifa bajarildi:
1. **Binary Classification** (IMDB Reviews)
2. **Multi-class Classification** (AG News)

## 📊 Ishlatilgan Datasetlar
| Dataset | Vazifa | Klasslar soni | Ma'lumot hajmi |
| :--- | :--- | :---: | :--- |
| **IMDB** | Sentiment Analysis | 2 | 50,000 reviews |
| **AG News** | Topic Classification | 4 | 127,600 news |

## 🧠 Model va Texnologiyalar
- **Model:** `distilbert-base-uncased` (Lightweight and Fast Transformer)
- **Kutubxonalar:** `Transformers`, `Datasets`, `Evaluate`, `PyTorch`
- **Metrikalar:** Accuracy, Precision, Recall, F1-score

## 🛠 O'rnatish va Ishga tushirish
Loyihani lokal kompyuteringizda ishlatish uchun quyidagi buyruqlarni bajaring:

```bash
pip install transformers datasets evaluate accelerate torch
🚀 Natijalar (Expected Results)
Model o'qitilgandan so'ng quyidagicha aniqlik ko'rsatkichlariga erishildi:

IMDB Accuracy: ~90-92%

AG News Accuracy: ~91-94%

📂 Kod strukturasi
classification_imdb.ipynb - Kinolar sharhini tahlil qilish (Positive/Negative).

classification_ag_news.ipynb - Yangiliklarni toifalarga ajratish.

📺 Video Darslik
Ushbu loyihaning to'liq tushuntirilgan videosini mening YouTube kanalimda ko'rishingiz mumkin:

👉 MachineLearning_uz YouTube kanali @MachineLearning_uz

🤝 Aloqa
Agar loyiha bo'yicha savollaringiz bo'lsa, menga bog'lanishingiz mumkin!

⭐ Agar loyiha sizga foydali bo'lgan bo'lsa, "Star" tugmasini bosib qo'yishni unutmang!
