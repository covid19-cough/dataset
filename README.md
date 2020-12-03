# Description

Dataset of recordings of induced cough - not spontaneous, but originated according to the researcher request.

The dataset contains records grouped by type:

- verified - records of people whose COVID has been confirmed with positive PCR smear according to the laboratory data.
- unverified - records of people who verbally confirmed positive PCR smear.

Records are also structured by group:

- covid positive with symptoms
- covid positive asymptomatic 
- covid negative healthy

## Collection technology

Samples are collected by phone using the call center and via bot in Telegram

## Data layout

The ```metadata.json``` file contains a description of samples using the following fields:
- **filename** - name of the file which is in the directory ```raw```
- **start_at** - the beginning of an induced cough, sec
- **end_at** - end of induced cough, sec
- **verified** - record verified (optional field)
- **asymptomatic** - asymptomatic (optional field)
- **comment** - comment
- **covid19** - feature of existing COVID19
- **source** - source of seed

# Описание

Датасет записей форсированного кашля - индуцированного, то есть не спонтанного, а вызванного по просьбе исследователя.

Датасет содержит записи, сгруппированные по типам:

- верифицированные - записи людей, у которых COVID подтвержден положительным мазком ПЦР по данным лаборатории.
- неверифицированные - записи людей, которые устно подтвердили наличие у них положительного мазка ПЦР на ковид.

Также записи структурированы по группам:

- ковид положительные с симптомами
- ковид положительные бессимптомные 
- ковид отрицательные здоровые

## Технология сбора

Часть сэмплов собраны по телефону, часть в телеграмм-боте 

## Разметка данных

Файл ```metadata.json``` содержит описание семплов, используя следующие поля:
- **filename** - имя файла, находящегося в директории ```raw```
- **start_at** - начало индуцированного кашля, сек
- **end_at** - окончание индуцированного кашля, сек
- **verified** - запись верифицирована (необязательное поле)
- **asymptomatic** - бессимптоный носитель (необязательное поле)
- **comment** - комментарий
- **covid19** - признак имеющегося COVID19
- **source** - источник получения семпла
