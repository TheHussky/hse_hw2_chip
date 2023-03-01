# hse22_hw4
Работа выполнена в [google colab](colab.research.google.com/drive/1LB6Z6LbvVIE0fSaO7avrRbR6Pp25Ils6?usp=sharing).

## FASTQC reports
Control
![Fastqc report](images/control1.png "control")
![Fastqc report](images/control2.png "control")
ENCF002AAX
![Fastqc report](images/AAX1.png "AAX")
![Fastqc report](images/AAX2.png "AAX")
ENCF002AAZ
![Fastqc report](images/AAX1.png "AAZ")
![Fastqc report](images/AAX2.png "AAZ")

[control](src/ENCFF000WXY_fastqc.html) 
[ENCFF002AAX](src/ENCFF002AAX_fastqc.html) 
[ENCFF002AAZ](src/ENCFF002AAZ_fastqc.html)

Сокращенная информация по подрезанным чтениям:
![Fastqc report](images/trim_AAX.png "AAX")
![Fastqc report](images/trim_AAZ.png "AAZ")
[ENCFF002AAX](src/ENCFF002AAX.fastq.trim_fastqc.html)
[ENCFF002AAZ](src/ENCFF002AAZ.fastq.trim_fastqc.html)

## Таблица с результатами выравнивания
![table](images/table.png "table")
Стоит отметить малый процент выравниваний. Это произошло из-за выравнивания всего на одну хромосому, а не на весь геном.

## Диаграммы
![table](images/venn1.png "diag")
![table](images/venn2.png "diag")
![table](images/venn3.png "diag")
![table](images/venn4.png "diag")
Как и в случае с выравниванием, плохое (а точнее нулевое) пересечение объясняется выравниванием на одну хромосому. 13 хромосама оказалась неудачной для выравнивания.
