# Модуль счета импульсов SA-P5-SPPC

## Общие сведения

??? note "Разработка"
    На текущий момент модуль на стадии разработки. Начало тестирования запланировано на апрель 2025 года
<div class="grid cards" markdown>

![Image title](../img/modules/SPPC.png){ width="150" align=left  }
Модуль счета импульсов (SPPC) (арт. SA-P5-SPPC) является 8-ми канальным модулем расширения и предназначен для счета импульсов частотой до 200 кГц.
</div>

## Технические характеристики 
| Характеристика                          | Значение                          |
|-----------------------------------------|-----------------------------------|
| Максимальная потребляемая мощность, Вт  | 7                                 |
| Количество входных каналов              | 8                                 |
| Диапазон изменения частоты, Гц          | от 1 до 200000                    |
| Номинальное входное напряжение канала измерения частоты и счета импульсов, В | 0 … 24 |
| Регулируемый порог детектирования логической единицы, В | Да, от 0,02 до 12 |
| Разрешение счетчика, бит                | 16                                |
| Погрешность модуля, %                   | ±0.1 от полной шкалы              |
| Гальваническая изоляция                 | Между входной и выходной логикой  |
| Сечение проводника, мм²                 | От 0,2 до 1,5                     |
| Масса, г                                | 120                               |
| Габариты ВхШхГ, мм                      | 126х21х90                         |

## Эксплуатационные характеристики
| Характеристика                   | Значение           |
| -------------------------------- | -                  |
| Температура эксплуатации, °С     | От минус 40 до 60  |
| Температура хранения, °С         | От минус 40 до 60  |
| Влажность при хранении, %	       | От 5 до 95         |
| Влажность при эксплуатации, %    | От 5 до 95         |
| Тип монтажа                      | На DIN-рейку 35 мм |
| Расположение при монтаже         | Вертикальное       |

## Схема подключения
<div class="grid cards" markdown>
![Image title](../img/connection/SPPC.svg){ width="370"; align=left  }

![Image title](../img/connection/connector_18pin.png){ width="170";  }
</div>

| Обозначение | Наименование канала | Описание                                         |
|-------------|---------------------|--------------------------------------------------|
| 1           | F1+                 | Плюс устройства 1                                |
| 2           | F1-                 | Минус устройства 1                               |
| 3           | F2+                 | Плюс устройства 2                                |
| 4           | F2-                 | Минус устройства 2                               |
| 5           | F3+                 | Плюс устройства 3                                |
| 6           | F3-                 | Минус устройства 3                               |
| 7           | F4+                 | Плюс устройства 4                                |
| 8           | F4-                 | Минус устройства 4                               |
| 9           | F5+                 | Плюс устройства 5                                |
| 10          | F5-                 | Минус устройства 5                               |
| 11          | F6+                 | Плюс устройства 6                                |
| 12          | F6-                 | Минус устройства 6                               |
| 13          | F7+                 | Плюс устройства 7                                |
| 14          | F7-                 | Минус устройства 7                               |
| 15          | F8+                 | Плюс устройства 8                                |
| 16          | F8-                 | Минус устройства 8                               |
| 17          | GND                 | Допускается подключение экранирующей оплетки     |
| 18          | GND                 | Допускается подключение экранирующей оплетки     |

## Индикация
| Обозначение | Индикация | Показатель |
|------------------|----------------------|---------------------------------------|
| P | :green_circle:| Наличие напряжения питания |
| P | :white_circle:| Отсутствие напряжения питания |
| L | :green_circle:| Наличие соединения Ethernet |
| L | :yellow_circle: :green_circle: :yellow_circle: | Обмен данными по Ethernet |
| L | :white_circle:| Отсутствие соединения Ethernet|

## Размеры
=== "Габаритные размеры" 
    ![Image title](../img/dimensions/overall_dimensions_extensions.png){ width="580"}
=== "Установочные размеры"
    ![alt text](../img/dimensions/installation_dimensions.png) 

## 3D-модель
<model-viewer src="https://manual.saplc.ru//img/3d/DI.glb"
alt="3D Model"
auto-rotate
camera-controls
poster="https://manual.saplc.ru//img/3d/posterDI.webp"
camera-orbit="160deg 75deg 348m"
field-of-view="30deg"
exposure="0.5"
style="width: 100%; height: 500px;">
</model-viewer>


## Файлы для скачивания
<a href="/downloads/IPCSA_OG.xml" download>XML конфигурационный файл для TwinCAT</a>      
<a href="/downloads/Module 18-pin.step" download>3D-модель</a>   
<a href="/downloads/Module 18-pin.dwg" download>2D-модель</a>    






