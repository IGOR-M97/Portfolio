# **ТЕМА: "Сравнение социально значимых показателей некоторых стран бывшего СССР"**
[File_PDF](https://github.com/IGOR-M97/Portfolio/blob/main/Example_PowerBI/%D0%A1%D1%80%D0%B0%D0%B2%D0%BD%D0%B5%D0%BD%D0%B8%D0%B5%20%D1%81%D0%BE%D1%86%D0%B8%D0%B0%D0%BB%D1%8C%D0%BD%D0%BE%20%D0%B7%D0%BD%D0%B0%D1%87%D0%B8%D0%BC%D1%8B%D1%85%20%D0%BF%D0%BE%D0%BA%D0%B0%D0%B7%D0%B0%D1%82%D0%B5%D0%BB%D0%B5%D0%B9%20%D0%BD%D0%B5%D0%BA%D0%BE%D1%82%D0%BE%D1%80%D1%8B%D1%85%20%D1%81%D1%82%D1%80%D0%B0%D0%BD%20%D0%B1%D1%8B%D0%B2%D1%88%D0%B5%D0%B3%D0%BE%20%D0%A1%D0%A1%D0%A1%D0%A0.pdf)  

**Цель:** Визуализировать, по возможности, официальную стадистику некоторых показателей по России, Казахстану, Узбекистану, Кыргызстану, Таджикистану  
**Формат отчета:** [File_PDF](https://github.com/IGOR-M97/Portfolio/blob/main/Example_PowerBI/%D0%A1%D1%80%D0%B0%D0%B2%D0%BD%D0%B5%D0%BD%D0%B8%D0%B5%20%D1%81%D0%BE%D1%86%D0%B8%D0%B0%D0%BB%D1%8C%D0%BD%D0%BE%20%D0%B7%D0%BD%D0%B0%D1%87%D0%B8%D0%BC%D1%8B%D1%85%20%D0%BF%D0%BE%D0%BA%D0%B0%D0%B7%D0%B0%D1%82%D0%B5%D0%BB%D0%B5%D0%B9%20%D0%BD%D0%B5%D0%BA%D0%BE%D1%82%D0%BE%D1%80%D1%8B%D1%85%20%D1%81%D1%82%D1%80%D0%B0%D0%BD%20%D0%B1%D1%8B%D0%B2%D1%88%D0%B5%D0%B3%D0%BE%20%D0%A1%D0%A1%D0%A1%D0%A0.pdf)
  
**Инструменты:** Power BI, Power Query, DAX.

**Задачи:**
    
   *Визуализировать по странам и годам:   
    1. Процент разводов от браков  
    2. Заболеваемость ВИЧ на 100тыс населения и накопительный контингент, состоящий на учете на 100тыс населения  
    3. Количество прерываний беременности на 100тыс женщин фертильного возраста  
    5. Сравнить доли курящих женщин и мужчин  
    6. Визуализировать младенческую и материнскую смертность*

***
## **Особенности данных в визуализации:**
В работе использовалась официальная статистика соответствующих государств, на некоторых графиках стоит дополнительная маркировка "официально" или "официальная статистика".  
"НОВОСТИ" - значит информация собиралась из открытых просторов сети интернет с параллельной перекрестной проверкой из нескольких источников. В основном о каких-либо показателях сообщали официальные лица соответствующих министерств журналистам или это была статистика СНГ, или статистика зарубежных некоммерческих организаций, в частности американских.  
"ВОЗ" - данные взяты с открытого [сайта Всемирной огганизации здравоохранения](https://gateway.euro.who.int/ru/indicators/epw_22-tobacco-use-prevalence-females/#id=36863)  

Официальные сайты Узбекистана: [Портал открытых данных Республики Узбекистан](https://data.egov.uz/), [Старый официальный сайт](https://olddata.gov.uz/). Для младенческой смертности учитывался [этот дополнительный материал.](https://mics-surveys-prod.s3.amazonaws.com/MICS6/Europe%20and%20Central%20Asia/Uzbekistan/2021-2022/Snapshots/Uzbekistan%202021-22%20MICS%20Statistical%20Snapshots_Russian%20%5B2023-02-23%5D.pdf)  
Официальный сайт России: [Росстат](https://rosstat.gov.ru/folder/10705). Дополнительные материалы для младенческой и материнской смертности: [1](https://www.demoscope.ru/weekly/2023/01001/barom05.php#:~:text=%D0%A1%D0%BF%D0%B0%D0%B4%20%D0%BD%D0%B0%D1%87%D0%B0%D0%BB%D1%81%D1%8F%20%D1%82%D0%BE%D0%BB%D1%8C%D0%BA%D0%BE%20%D0%B2%202022,%D0%BD%D0%B0%20100%20%D1%82%D1%8B%D1%81%D1%8F%D1%87%20%D1%80%D0%BE%D0%B4%D0%B8%D0%B2%D1%88%D0%B8%D1%85%D1%81%D1%8F%20%D0%B6%D0%B8%D0%B2%D1%8B%D0%BC%D0%B8).), [2](https://journals.eco-vector.com/pediatr/article/view/6691/5334), [3](https://gpmu.org/news/news3029).  
Официальные сайты Казахстана: [БЮРО НАЦИОНАЛЬНОЙ СТАТИСТИКИ
АГЕНТСТВА ПО СТРАТЕГИЧЕСКОМУ ПЛАНИРОВАНИЮ И РЕФОРМАМ РЕСПУБЛИКИ КАЗАХСТАН](https://stat.gov.kz/), [Старый официальный сайт](https://old.stat.gov.kz/).  
Официальные сайты Кыргызстана: [База открытых данных](https://data.gov.kg/ru/dataset), [Национальный статистический комитет Кыргызской Республики](https://www.stat.kg/ru/opendata/), а также [Республиканский центр по контролю ВИЧ Министерства Здравоохранения](https://aidscenter.kg/statistika/?lang=ru#).    
Официальный сайт Таджикистана: [Агентство по статистике при призиденте](https://www.stat.tj/ru/database-socio-demographic-sector), далее [смертность_1](
https://www.adb.org/ru/news/adb-grant-improve-maternal-and-child-health-care-tajikistan), [смертность_2](https://www.asiaplustj.info/ru/news/centralasia/20190119/kogda-to-za-nimi-priletali-samoleti), [данные ВОЗ материнской смертности](https://data.who.int/ru/indicators/i/AC597B1), [ВИЧ_ВОЗ_1](https://gateway.euro.who.int/ru/indicators/hfa_349-2190-rate-of-new-hiv-diagnoses-per-100-000/#id=19925), [ВИЧ_ВОЗ_2](https://data.who.int/ru/indicators/i/77D059C), [ВИЧ новости](https://vecherka.tj/archives/55022), [тоже_ВИЧ_1](https://www.unaids.org/sites/default/files/country/documents/TJK_narrative_report_2014.pdf), [тоже_ВИЧ_2](https://unaids-test.unaids.org/sites/default/files/unaids/contentassets/documents/data-and-analysis/tools/nasa/20140707/tajikistan_2010-2011_ru.pdf).  

## **Краткий ВЫВОД и рекомендации:**

111111111111111111111
