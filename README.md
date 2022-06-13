# hse22_project
[Ссылка на Google Colab](https://colab.research.google.com/drive/1E96p2sqwwg0GLWwLrj1snMLPhTZBmxq_#scrollTo=XO8UQfHJwTSN)

### Анализ аннотированных генов:
| Название | Число хромосом | Число плазмид |Число аннотированных генов | Процент | Участков Z-dna предсказано (>500) | Длина участков Z-dna |
| ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | 
| Vibrio kanaloae | 2 | 0 | 4196 | 84.56% | 6318 | 60874 |
| Vibrio gazogenes | 2 | 1 | 4266 | 84.66% | 5159 | 49292 |
| Vibrio furnissii | 2 | 1 | 4656 | 87.02% | 32940 | 317438 |
| Vibrio cholerae | 2 | 1 | 3837 | 86.76% | 13524 | 128090|
| Vibrio astriarenae | 2 | 0 | 4366 | 86.8% | 9107 | 87638 |


### Предсказание участков Z-DNA:
| | |
| - | - |
| <img width="409" alt="image" src="https://user-images.githubusercontent.com/60537387/173353779-cdf90a60-6323-4028-a09b-fdd5494be413.png"> | <img width="414" alt="image" src="https://user-images.githubusercontent.com/60537387/173353893-58001fb6-1919-4575-a7d2-3632d7d0d00b.png"> |
| <img width="428" alt="image" src="https://user-images.githubusercontent.com/60537387/173353970-4ac361e5-f58d-4ec1-9228-bca20bbf29ef.png"> | <img width="426" alt="image" src="https://user-images.githubusercontent.com/60537387/173354029-527ce6b4-4253-4522-9803-260b09ed827c.png"> |
| <img width="434" alt="image" src="https://user-images.githubusercontent.com/60537387/173354064-edd092e2-3350-4f9a-a69c-610e211f72a5.png"> | |

 ### Гомологичные кластеры:

Гистограмма:

<img width="522" alt="image" src="https://user-images.githubusercontent.com/60537387/173356530-b198a981-7625-4cb2-ab7f-f5e8a829b569.png">

Всего 1858 кластеров.

Отобранные кластеры:
| Номер | Генов в кластере | Функция |  Z-DNA score |
| ------------- | ------------- | ------------- | ------------- | 
| 246 | 5 | 50S ribosomal protein | 3160.72 |
| 1225 | 5 | elongation factor G | 2968.97 |
| 239 | 5 | 30S ribosomal protein S17 | 1222.13 |
| 169 | 5 | CvpA family protein | 5627.82 |
| 463 | 5 |  glycosyl transferase  | 36643.15 |

### Множественное белковое выравнивание:

Получено с помощью MegaX:

0:

<img width="1436" alt="image" src="https://user-images.githubusercontent.com/60537387/173438945-b5186915-d12d-421e-86fc-e283b7affddb.png">

1:

<img width="1437" alt="image" src="https://user-images.githubusercontent.com/60537387/173439151-ce1b026f-bcb5-4b3b-bd92-987eb9a8f910.png">

2:

<img width="1440" alt="image" src="https://user-images.githubusercontent.com/60537387/173439240-b13a1bb5-75d2-46ae-9773-f5c7879fb4fc.png">

3:

<img width="1439" alt="image" src="https://user-images.githubusercontent.com/60537387/173439346-7e552583-e9e0-4eb6-9419-4ab5cc1cf7f6.png">

4:

<img width="1439" alt="image" src="https://user-images.githubusercontent.com/60537387/173439444-863ea99f-21b1-40f3-93ee-ac4d5904cf82.png">

### Визуализация расположения участков Z-DNA:
| 0 | 1 | 2 | 3 | 
| - | - | - | - | 
| ![telegram-cloud-photo-size-2-5278742419032095535-y](https://user-images.githubusercontent.com/60537387/173441302-f9d498a0-bb21-4ee4-93ac-eb23cedc6709.jpg) | ![telegram-cloud-photo-size-2-5278742419032095546-y](https://user-images.githubusercontent.com/60537387/173441331-3e9c3513-2c34-421f-90b2-19d4c1a74c54.jpg) | ![telegram-cloud-photo-size-2-5278742419032095552-y](https://user-images.githubusercontent.com/60537387/173441364-9bf9e166-4cc3-4afd-b820-cae28813761a.jpg) | ![telegram-cloud-photo-size-2-5278742419032095557-y](https://user-images.githubusercontent.com/60537387/173441391-d48954f6-d9e7-448d-af41-cad0bf3a5b95.jpg) |
| ![telegram-cloud-photo-size-2-5278742419032095536-y](https://user-images.githubusercontent.com/60537387/173441442-29b1c873-7ce7-444f-b850-62ea63bb09b5.jpg) | ![telegram-cloud-photo-size-2-5278742419032095547-y](https://user-images.githubusercontent.com/60537387/173441471-da2a77e5-52be-4350-9c1b-b5aa3f87de57.jpg) | ![telegram-cloud-photo-size-2-5278742419032095553-y](https://user-images.githubusercontent.com/60537387/173441531-125b1503-3f7b-4c55-a66b-858ecdd99dc5.jpg) | ![telegram-cloud-photo-size-2-5278742419032095558-y](https://user-images.githubusercontent.com/60537387/173441558-968b08c0-c3a7-42fc-9c2b-db00cf0e7dc8.jpg) |
| ![telegram-cloud-photo-size-2-5278742419032095538-y](https://user-images.githubusercontent.com/60537387/173441595-dd7a2668-130d-46ee-8b6c-f88b4c3119d1.jpg) | ![telegram-cloud-photo-size-2-5278742419032095548-y](https://user-images.githubusercontent.com/60537387/173441621-750cf7b4-b901-4e72-a64b-fd7a63afe8c0.jpg) | ![telegram-cloud-photo-size-2-5278742419032095554-y](https://user-images.githubusercontent.com/60537387/173441652-da6161be-4560-422e-8140-1d62bd197524.jpg) | ![telegram-cloud-photo-size-2-5278742419032095559-y](https://user-images.githubusercontent.com/60537387/173441670-42ed36f8-6df1-4847-a841-bbb9daee7bd1.jpg) |
| ![telegram-cloud-photo-size-2-5278742419032095541-y](https://user-images.githubusercontent.com/60537387/173441708-efbdb4af-621b-44cd-b404-b11e8f5bc2f2.jpg) | ![telegram-cloud-photo-size-2-5278742419032095549-y](https://user-images.githubusercontent.com/60537387/173441727-4eac69d8-0d8f-4ff4-bdd4-6da39b0f3a69.jpg) | ![telegram-cloud-photo-size-2-5278742419032095555-y](https://user-images.githubusercontent.com/60537387/173441749-89388aa2-746c-4566-b758-90c79f0dd489.jpg) | ![telegram-cloud-photo-size-2-5278742419032095560-y](https://user-images.githubusercontent.com/60537387/173441772-57a3d4aa-1307-4ca4-b01e-c0561355f725.jpg) |
| ![telegram-cloud-photo-size-2-5278742419032095545-y](https://user-images.githubusercontent.com/60537387/173441889-b0fb9626-853d-45b2-8501-8017bfae4b02.jpg) | ![telegram-cloud-photo-size-2-5278742419032095550-y](https://user-images.githubusercontent.com/60537387/173441856-c06be55e-d104-40bf-9630-abb313b15f42.jpg) | ![telegram-cloud-photo-size-2-5278742419032095556-y](https://user-images.githubusercontent.com/60537387/173441838-5909e62f-fcbf-44be-b301-bdadc22bfa42.jpg) | ![telegram-cloud-photo-size-2-5278742419032095561-y](https://user-images.githubusercontent.com/60537387/173441800-757900a1-c968-40a9-b27c-12d06cb2176f.jpg) |












