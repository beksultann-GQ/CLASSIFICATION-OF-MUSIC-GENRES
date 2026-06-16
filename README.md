# 🎵 Музыка жанрын аудио бойынша анықтау

Аудио файлдардан музыка жанрын автоматты анықтайтын Deep Learning жобасы.

## 📊 Деректер жиынтығы

- **Дереккөз:** [GTZAN Dataset — Kaggle](https://www.kaggle.com/datasets/andradaolteanu/gtzan-dataset-music-genre-classification)
- **Көлемі:** 1000 аудио файл (.wav), әрқайсысы 30 секунд
- **Жанрлар (10):** blues, classical, country, disco, hiphop, jazz, metal, pop, reggae, rock
- **Тәсіл:** Аудио → Mel-спектрограмма (сурет) → CNN классификация

## 🧠 Модельдер және нәтижелер

| Модель | Accuracy | F1-score | Параметрлер |
|--------|----------|----------|-------------|
| CNN (нөлден) | 0.610 | 0.599 | 2.2M |
| ResNet18 (Transfer Learning) | 0.665 | 0.666 | 11.2M |

**Жеңімпаз:** ResNet18 — Transfer Learning кішкентай датасетте артықшылық береді.

## 🛠️ Технологиялар

PyTorch · torchvision · librosa · scikit-learn · pandas · matplotlib

