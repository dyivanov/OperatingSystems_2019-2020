# OperatingSystems_2019-2020
Notes on basic shell commands, bash scripting and C code for the Operating Systems course 2019-2020

## Огранизационни
През семестъра се провеждат 3 контролни, като всяко едно е от 4 задачи - 3 задачи за писане на команди/код + 1 теоретична. Всяко контролно носи общо 120т. или общо 360т. като 90 са от теория. 
За **освобождаване** са нужни 70% т.е. приблизително 250 точки, като трябва да имате и поне ?? от точките на теория т.е. около ?? точки общо от теоретичните задачи. 
### Дати на контролни 
Дата|Материал  |
|--|--|
|28.03.2020  |Писане на поредици от Bash команди  |
|09.05.2020  |Bash скриптове  |
|06.06.2020  |Писане на C програми за работа с файлове и процеси  |


## Линукс среда
На упражнения ще ползвате PuTTy, чрез което ще се свързвате до сървъра, на който ще работите. Той е достъпен **само** в мрежата на ФМИ.  

Ако PuTTy не ви харесва, може да се свързвате със сървъра чрез SSH (протокол за сигурна връзка към отдалечен сървър). Естествено, командата е вградена в Linux/MacOS, за Windows трябва да се свали допълнително и да се използва PowerShell. 

**Как да използваме SSH:**

В терминала пишем
`ssh s81xxx@os-server.fmi.uni-sofia.bg`, където израза преди @ е вашето потребителско име, а след @ е името или IP-то на сървъра (на сървъра на ФМИ IP адреса е 62.44.100.23) и натискаме Enter. След това ще ви даде да си въведете паролата.

За да се упражнявате вкъщи може да:

 - си инсталирате Linux :)
 - ако сте на MacOS просто отваряте терминала и сте вие.
 - Ако сте на Windows има няколко варианта:
 -- Подкарвате си виртуална машина 
 -- От Microsoft Store си сваляте и инсталирате [това](https://www.microsoft.com/en-us/p/ubuntu/9nblggh4msv6?activetab=pivot:overviewtab), което ви позволява да пишете bash команди под Windows. 

