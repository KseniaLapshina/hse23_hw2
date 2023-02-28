# hse23_hw2
https://colab.research.google.com/drive/1B_VT25idB199oDCpcM5npTGaSCH3IQS7?usp=sharing

### FastQC и MultiQC анализ.
Результаты приведены в виде файлов pdf в папке data.
#### ENCFF411MHC
![image](https://user-images.githubusercontent.com/114621114/221864955-002a3a58-7f20-4097-b2df-821ad2c8ffde.png)
#### ENCFF479VFS
![image](https://user-images.githubusercontent.com/114621114/221865199-6705f1f3-ee5c-46b8-b857-8571f329e462.png)
#### ENCFF364HZK
![image](https://user-images.githubusercontent.com/114621114/221865331-c4312f69-a007-4811-9a88-b12bcfc22dda.png)
#### MultiQC
![image](https://user-images.githubusercontent.com/114621114/221865725-907108ba-6cca-4067-aa78-3ba456602ee8.png)

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
#### ENCFF411MHC
![image](https://user-images.githubusercontent.com/114621114/221866591-07cb53c6-4c2c-4c85-a8f0-c275486abc56.png)
![image](https://user-images.githubusercontent.com/114621114/221866726-2fa6f11c-0be9-46e1-8e85-c7f286bbee96.png)
#### ENCFF479VFS
![image](https://user-images.githubusercontent.com/114621114/221866906-0280fd95-7066-488f-b033-4fec9ad0becd.png)
![image](https://user-images.githubusercontent.com/114621114/221867036-045b6f3a-6df9-419f-b497-601196eae781.png)

Количество пересечений отличается, поскольку в одном случае берутся полученные пики, пересекающиеся с пиками ENCODE; а в другом случае отбираются пики ENCODE, совпавшие с пиками, которые получили мы.

### ngs.plot

ENCFF411MHC | ENCFF479VFS
-|-
![](data/result_1.png) | ![](data/result_1.png)

![image](https://user-images.githubusercontent.com/114621114/221872447-7f537a07-b01b-4c10-be47-45045640513e.png)
Li e. al. (2007) Cell

Данные ChIP-seq эксперимента из ENCODE согласуются с данными из статьи.
