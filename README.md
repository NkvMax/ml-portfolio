# ML Portfolio

Jupyter-ноутбуки по классическому машинному обучению и глубокому обучению: многоклассовая классификация, регрессия, распознавание изображений, автоэнкодеры и подбор гиперпараметров.
_Все датасеты и обученные модели доступны на [Google Drive](https://drive.google.com/drive/folders/1LE3WVplcPcYmJs6Tbs5sY68xaLWWYLFy)._

**Примечание:** Некоторые ноутбуки были оптимизированы и выполнены локально на архитектуре Apple Silicon (M1, macOS).
Некоторые части кода (например, использование tensorflow-metal, специфичная многопоточность или ускорения) могут потребовать адаптации для корректного запуска в среде Kaggle или Google Colab

## Содержание

- `lab_1_multiclass_classification.ipynb`: Многослойный перцептрон (MLP) для табличных данных (Breast Cancer)
- `lab_2_regression_overfitting.ipynb`: Регуляризация и подбор оптимизаторов для регрессии
- `lab_3_image_classification_raytune.ipynb`: Transfer learning и Ray Tune (CIFAR-10)
- `lab_4_autoencoder_latent_space.ipynb`: Автоэнкодер и анализ латентного пространства (MNIST)
- `lab_5_eth_lstm_forecasting.ipynb`: Прогнозирование курса ETH-USD с помощью LSTM и классификация фаз рынка (бычий/медвежий/флет)
## Требования
Для работы ноутбуков требуется Python 3.10+ и следующие библиотеки:
- numpy, pandas, matplotlib, seaborn, scikit-learn, torch, torchvision, tensorflow, ray[tune]

Полный список — в файле `requirements.txt`.