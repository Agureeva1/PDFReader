# PDFReader (Поисковая система)

## Цель создания
Программа способна быстро находить указанное слово среди pdf-файлов, ранжировать результаты по количеству вхождений (от большего к меньшему). 

## Особенности реализации
- Программа представляет собой клиент-серверное приложение.
- Для работы с PDF-файлами использована библиотека `com.itextpdf:itext7-core:7.1.15`.
- Пример работы программы (для примера использовано слово "бизнес"):
```
[PageEntry{pdf=Этапы оценки проекта_ понятия, методы и полезные инструменты.pdf, page=12, count=6}, PageEntry{pdf=Этапы оценки проекта_ понятия, методы и полезные инструменты.pdf, page=4, count=3}, PageEntry{pdf=Этапы оценки проекта_ понятия, методы и полезные инструменты.pdf, page=5, count=3}, PageEntry{pdf=1. DevOps_MLops.pdf, page=5, count=2}, PageEntry{pdf=Что такое блокчейн.pdf, page=1, count=2}, PageEntry{pdf=Что такое блокчейн.pdf, page=3, count=2}, PageEntry{pdf=Этапы оценки проекта_ понятия, методы и полезные инструменты.pdf, page=2, count=1}, PageEntry{pdf=Этапы оценки проекта_ понятия, методы и полезные инструменты.pdf, page=11, count=1}, PageEntry{pdf=1. DevOps_MLops.pdf, page=3, count=1}, PageEntry{pdf=1. DevOps_MLops.pdf, page=4, count=1}, PageEntry{pdf=Что такое блокчейн.pdf, page=2, count=1}, PageEntry{pdf=Что такое блокчейн.pdf, page=4, count=1}, PageEntry{pdf=Что такое блокчейн.pdf, page=5, count=1}, PageEntry{pdf=Что такое блокчейн.pdf, page=7, count=1}, PageEntry{pdf=Что такое блокчейн.pdf, page=9, count=1}, PageEntry{pdf=Продвижение игр.pdf, page=7, count=1}, PageEntry{pdf=Как управлять рисками IT-проекта.pdf, page=2, count=1}]
```