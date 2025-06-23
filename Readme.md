# Как воспроизвести результаты

1. Скачать dataset.zip по ссылке https://drive.google.com/drive/folders/1ilRpgfsbiQH-4yE-jF7uFq8szLTF9nv_?usp=drive_link и распаковать в папку data/dataset
2. Скачать видео по ссылке https://disk.yandex.ru/d/-VhiX2BOWdw-rg и распаковать видео в папку data/videos_raw
В итоге должна получится следующая структура:

```
├── data
│   ├── dataset
│   │   ├── data.yaml
│   │   ├── images
│   │   │   ├── Test
│   │   │   ├── Train
│   │   │   └── Validation
│   │   ├── labels
│   │   │   ├── Test
│   │   │   ├── Train
│   │   │   ├── Validation
│   │   ├── Test.txt
│   │   ├── Train.txt
│   │   └── Validation.txt
│   └── videos_raw
│       ├── 1.MOV
│       ├── 2_1.MOV
│       ├── 3_1.MOV
│       ├── 3_2.MOV
│       ├── 4_1.MOV
│       └── 4.MOV
├── train.ipynb
```

3. Открыть train.ipynb в любом удобнов вам редакторе (который поддерживает jupyter notebook)
4. Выполнить его по шагам