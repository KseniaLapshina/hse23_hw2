# hse23_hw2
https://colab.research.google.com/drive/1B_VT25idB199oDCpcM5npTGaSCH3IQS7?usp=sharing

### FastQC и MultiQC анализ.
![image](https://user-images.githubusercontent.com/114621114/219989686-1b9d6cc3-8742-4e8f-9a6d-db87bab2f7ec.png)
![image](https://user-images.githubusercontent.com/114621114/219989760-f887c6c0-5786-46b5-86a7-af260361cab6.png)
![image](https://user-images.githubusercontent.com/114621114/219989819-0f18399e-9abb-4917-8d96-72523e1fca63.png)
![image](https://user-images.githubusercontent.com/114621114/219989878-ae467693-631f-4035-a564-61f16b3fbcf3.png)
Не было необходимости подрезать чтения.

### Статистика.
Образец | Ридов | Выровн. уникально | Выровн. НЕуникально | НЕ выровн.
-|-|-|-|-
ENCFF411MHC | 21830825 | 882684 | 1691747 |19256394
ENCFF479VFS | 34425242 | 1410567 | 2708870 |30305805
ENCFF364HZK | 69344412 | 2820775 | 4540146 |61983491

Получен низкий процент выравнивания, так как риды со всего генома мы картирует лишь на одну хромосому.

### Диаграммы Венна.
Диаграммы приведены в виде файлов pdf в папке data.

Количество пересечений отличается, поскольку в одном случае берутся полученные пики, пересекающиеся с пиками ENCODE; а в другом случае отбираются пики ENCODE, совпавшие с пиками, которые получили мы.
