# praktikum-projects
 
Данные проекты были выполнены в ходе обучения в Яндекс.Практикуме, профессии "Аналитик данных"  

| Название проекта | Описание |
|-------|:--------------------------------------|
|[Исследуем результаты A/A/B-эксперимента](analyst_product_mobil_Alexgnik.ipynb)|Дизайнеры хотят поменять шрифты во всём приложении, а менеджеры испугались, что пользователям будет непривычно.
Договорились принять решение по результатам A/A/B-теста|


Проект выполнен в среде jupyter notebook.    
Сервер работал на версии Python 3.7.12     
Используемые библиотеки:  
import pandas as pd  
import numpy as np  
import matplotlib.pyplot as plt  
import seaborn as sns  
from scipy import stats as st  
from datetime import datetime, timedelta  
from scipy import stats as st  
import math as mth    

Для выполнения проекта использовались данные из файла logs_exp.csv, который должен находиться в папке с основным файлом проекта.
Доступ к данному файлу не могу предоставить в связи с защитой авторских прав.

**Выводы по проекту:**  
По поводу эксперимента - проведен корректно. Группы А/А теста также корректны, статистические критерии между ними не выявлены.
В целом эксперимент показал, что нет статистической значимости в конверсии пользователей после изменения шрифта.
Новый шрифт никак не повлиял на конверсию, тк что если он нравится всем больше, можно внедрять.
Проект закончен.