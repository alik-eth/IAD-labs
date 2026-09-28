# Інтелектуальний аналіз даних — лабораторні роботи

Вовкотруб Олександр Віталійович, група ФБ-61мн
Навчально-науковий фізико-технічний інститут, кафедра інформаційної безпеки
КПІ ім. Ігоря Сікорського

Викладач: доц. Сахненко Н. К.

| № | Тема | Датасет | Ноутбук | Звіт |
|---|------|---------|---------|------|
| 1 | Класифікація засобами scikit-learn | [Ethereum Fraud Detection](https://www.kaggle.com/datasets/vagifa/ethereum-frauddetection-dataset) | [solution.ipynb](lab1/solution.ipynb) · [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/alik-eth/IAD-labs/blob/main/lab1/solution.ipynb) | [PDF](lab1/PZ1_ClassificationSklearn_Vovkotrub_FB-61mn.pdf) |
| 2 | Зниження розмірності, кластеризація, класифікація текстів | [Ethereum Fraud Detection](https://www.kaggle.com/datasets/vagifa/ethereum-frauddetection-dataset), [CVE & CWE](https://www.kaggle.com/datasets/stanislavvinokur/cve-and-cwe-dataset-1999-2025) | [solution.ipynb](lab2/solution.ipynb) · [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/alik-eth/IAD-labs/blob/main/lab2/solution.ipynb) | — |
| 3 | Нейронні мережі (PyTorch): MLP, CNN, RNN | [Ethereum Fraud Detection](https://www.kaggle.com/datasets/vagifa/ethereum-frauddetection-dataset), [Malimg](https://www.kaggle.com/datasets/ikrambenabd/malimg-original), [CVE & CWE](https://www.kaggle.com/datasets/stanislavvinokur/cve-and-cwe-dataset-1999-2025) | [solution.ipynb](lab3/solution.ipynb) · [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/alik-eth/IAD-labs/blob/main/lab3/solution.ipynb) | — |

## Запуск

**У Colab** — відкрити ноутбук за кнопкою в таблиці й виконати
*Runtime → Run all* (для ЛР3 спершу увімкнути GPU: *Runtime → Change runtime
type → T4 GPU*). Датасет завантажується з Kaggle автоматично, нічого
вивантажувати вручну не треба.

**Локально** (Python 3.13):

```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
jupyter notebook lab1/solution.ipynb   # або lab2/…, lab3/…
```

Перша клітинка ноутбука створює теки `data/` і `assets/` поруч із ним і
завантажує датасет, якщо його ще немає.
