# Домашнее задание к занятию «Вычислительные мощности. Балансировщики нагрузки»
## Создать бакет Object Storage и разместить в нём файл с картинкой:
## Создать бакет в Object Storage с произвольным именем (например, имя_студента_дата).
## Положить в бакет файл с картинкой.
## Сделать файл доступным из интернета.
## Создать группу ВМ в public подсети фиксированного размера с шаблоном LAMP и веб-страницей, содержащей ссылку на картинку из бакета:
## Создать Instance Group с тремя ВМ и шаблоном LAMP. Для LAMP рекомендуется использовать image_id = fd827b91d99psvq5fjit.
## Для создания стартовой веб-страницы рекомендуется использовать раздел user_data в meta_data.
## Разместить в стартовой веб-странице шаблонной ВМ ссылку на картинку из бакета.
## Настроить проверку состояния ВМ.
## Подключить группу к сетевому балансировщику:
## Создать сетевой балансировщик.
## Проверить работоспособность, удалив одну или несколько ВМ.

## РЕШЕНИЕ:
### Bucket
<img width="501" height="220" alt="image" src="https://github.com/user-attachments/assets/92c57f4c-0ae7-4b98-a1b8-a12372dc7161" />

### Instance Group
<img width="1379" height="323" alt="image" src="https://github.com/user-attachments/assets/4490d713-e533-482b-b2c6-affa2d2f2ca4" />

### Target Group

<img width="1029" height="329" alt="image" src="https://github.com/user-attachments/assets/c78b4091-da6b-4d68-ae3b-b8f120ac3c9d" />

### Картинка на инстанстах
<img width="789" height="719" alt="image" src="https://github.com/user-attachments/assets/6cf40f35-04fe-4890-bfd7-61a832098390" />

### Проверка работоспособности при удалении одной ВМ
<img width="1250" height="357" alt="image" src="https://github.com/user-attachments/assets/7fe6e80e-007a-4946-abf6-963e7900c320" />
<img width="1281" height="345" alt="image" src="https://github.com/user-attachments/assets/78a1c1c6-d454-4164-9961-6e178fadeacd" />
<img width="1268" height="382" alt="image" src="https://github.com/user-attachments/assets/75c728b8-64ff-46bf-bd01-4ba4dd61b8e7" />

### Общее количество созданных ресурсов
<img width="1073" height="395" alt="image" src="https://github.com/user-attachments/assets/48f1f238-b68e-475c-947b-3219c2f297ba" />



