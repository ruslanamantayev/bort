up:: [Показатели по технике](Показатели%20по%20технике.md)
tags:: 
dates:: 2022-09-21
Sources:: 
	1. [MTBF — откуда берется «миллион часов MTBF»](https://habr.com/ru/post/122529/),    
	2. [MTBF, MTTR, MTTF, MTTA: общие сведения о метриках инцидента](https://www.atlassian.com/ru/incident-management/kpis/common-metrics)


# MTBF - Среднее время до отказа техники


Строго говоря, на практике, вместо MTBF гораздо практичнее пользоваться параметром AFR — Annual Failure Rate, или «ежегодная вероятность сбоев», выводимом из MTBF.  
Он вычисляется как: **AFR = 1-exp(-8760/MTBF)**
[MTBS](MTBS.md)


