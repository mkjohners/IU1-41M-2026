# Задание №5

## Цель задания

- Исследование когнитивных характеристик мозга по данным ЭЭГ.

## Ключевые навыки

- Алгоритмы классификации в нейронных сетях.

## Задание

1. Загрузи датасет *(тренировочная и тестовая выборки содержат сигнал ЭЭГ в строках формата CSV)*:
   - Тренировочная выборка: *[ссылка](https://github.com/TAUforPython/BioMedAI/blob/main/test_datasets/MI-EEG-B9T.csv)*
   - Тестовая выборка: *[ссылка](https://github.com/TAUforPython/BioMedAI/blob/main/test_datasets/MI-EEG-B9T.csv)*
   - Таргет для тренировочной выборки: *[ссылка](https://github.com/TAUforPython/BioMedAI/blob/main/test_datasets/2class_MI_EEG_train_9.csv)*
   - Таргет для тестовой выборки: *[ссылка](https://github.com/TAUforPython/BioMedAI/blob/main/test_datasets/2class_MI_EEG_test_9.csv)*

2. Описание эксперимента, по которому собран датасет:
   https://www.physionet.org/content/eegmmidb/1.0.0/

3. Проведи **анализ датасета**: преобразуй временной сигнал с помощью **вейвлет-преобразования**, получи изображение.

4. Натренируй **нейронную сеть** для распознавания когнитивной характеристики мозга —
   определение представления о движении *(сжимаем левый или правый кулак)*.

---

## Сдача работы

Каждый студент создаёт внутри папки `lab5` папку со своим **именем и фамилией на латинице** в едином формате:

```
lab5/
└── firstname_lastname/   # например: ivan_petrov
    ├── report.pdf        # PDF-отчёт
    └── notebook.ipynb    # Jupyter Notebook с кодом
```

В папку помещаются **два файла**:
- `report.pdf` — письменный отчёт в формате PDF.
- `notebook.ipynb` — Jupyter Notebook с выполненным кодом.
