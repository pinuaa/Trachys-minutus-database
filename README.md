# Trachys minutus — база данных находок

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.19588788.svg)](https://doi.org/10.5281/zenodo.19588788)

Интерактивная карта и таблица находок златки *Trachys minutus* (Linnaeus, 1758) (Coleoptera: Buprestidae), составленная на основе открытых литературных источников.

## 📌 О проекте

Данный репозиторий содержит веб-приложение для визуализации географического распространения *Trachys minutus* — минирующей златки, развивающейся на лиственных деревьях (вяз, липа, ива и др.).

## 🗂️ Структура данных

Файл `trachys_min_occurences.csv` содержит следующие поля:

| Поле | Описание |
|------|----------|
| `Автор` | Автор(ы) публикации |
| `Год публикации` | Год выхода работы |
| `Страна` | Страна находки |
| `Место` | Локалитет / географическая привязка |
| `Широта` | Десятичные градусы (WGS 84) |
| `Долгота` | Десятичные градусы (WGS 84) |
| `Ссылка` | URL или DOI источника (при наличии) |

> ⚠️ **Примечание:** Координаты приближены по текстовым указаниям в источниках. Для точных геопривязок сверяйтесь с оригинальными работами.
> Если вы используете этот датасет в научной работе, пожалуйста, ссылайтесь следующим образом:
А.А. Абдулхакова, И.В. Ермолаев (2026). Database of Trachys minutus occurrences (v1.0) [Data set]. Zenodo. https://doi.org/10.5281/zenodo.19588788

📬 Контакты / Обратная связь
📧 Предложения по дополнению базы и исправлению ошибок: abdulhakova28@gmail.com

## Description
This dataset contains georeferenced occurrence records of the leaf-mining jewel beetle *Trachys minutus* (Coleoptera: Buprestidae) compiled from scientific literature and museum collections.

## Data Format
The data are provided as a comma-separated values (CSV) file (`trachys_min_occurences.csv`) with the following columns:
- `Источник`: Publication title / Source name.
- `Год публикации`: Year of record/publication.
- `Автор`: Author(s).
- `Страна`: Country.
- `Место`: Locality description (in Russian/English).
- `Ссылка`: URL or bibliographic reference.
- `Широта` / `Долгота`: Decimal degrees (WGS84).

## Map Visualization
An interactive map of the collection points is available at:
https://pinuaa.github.io/Trachys-minutus-database/

## Usage and Citation
If you use this dataset in your research, please cite it as follows:
A.A. Abdulkhakova, I.V. Ermolaev (2026). Database of Trachys minutus occurrences (v1.0) [Data set]. Zenodo. https://doi.org/10.5281/zenodo.19588788

## License
This work is licensed under a Creative Commons Attribution 4.0 International License (CC BY 4.0).
