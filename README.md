# 🚀 NLP: Matn Klassifikatsiyasi (DistilBERT yordamida)

<div align="center">
  <h1>🤖 MachineLearning_uz</h1>
  <p><b>Sun'iy Intellekt va NLP dunyosiga xush kelibsiz!</b></p>
</div>

---

## 📝 Loyiha haqida
Ushbu repozitoriyada **NLP (Tabiiy tilni qayta ishlash)** sohasining eng muhim ikki yo'nalishi bo'yicha amaliy loyiha jamlangan. Biz **Hugging Face** ekotizimidan foydalanib, **DistilBERT** transformer modelini ikkita turli vazifa uchun o'qitdik (Fine-tuning).

### ✅ Bajargan vazifalarimiz:
1.  **Sentiment Analysis (IMDB):** Foydalanuvchi fikrlarining ijobiy yoki salbiyligini aniqlash.
2.  **Topic Classification (AG News):** Yangiliklarni 4 ta toifaga (Dunyo, Sport, Biznes, Texno) avtomatik ajratish.

---

## 📊 Datasetlar tavsifi

| Dataset | Klasslar | Tavsif |
| :--- | :--- | :--- |
| **IMDB** | 2 ta (Pos/Neg) | Kinolar haqidagi 50k sharhlar to'plami. |
| **AG News** | 4 ta (World, Sports, Business, Sci/Tech) | 120k dan ortiq yangiliklar sarlavhalari. |

---

## 🛠 Texnologik stek
* **Model:** `distilbert-base-uncased`
* **Library:** `transformers`, `datasets`, `evaluate`, `torch`, `accelerate`
* **Environment:** Google Colab / Jupyter Notebook

## 🚀 Qanday ishga tushirish kerak?

1. Repozitoriyani yuklab oling:
```bash
git clone [https://github.com/SizningUsername/nlp-classification-uz.git](https://github.com/SizningUsername/nlp-classification-uz.git)
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
