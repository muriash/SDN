University: [ITMO University](https://itmo.ru/ru/)  
Faculty: [FICT](https://fict.itmo.ru) 
Group: K33202  
Author: Shalyapina Maria Vasilievna

## Оглавление
 - [Упражнение 1](#part_1)
 - [Упражнение 2](#part_2)
 - [Упражнение 3](#part_3)
 - [Вывод](#part_4)

## <a name="part_1">Упражнение 1</a>
#### 1. Была установлена виртуальная машина Mininet
![1 вирт машина](https://github.com/muriash/SDN/assets/90574857/973b41bb-5074-4092-87fe-8962f29fd095)

### 2. Запуск виртуальной машины
![2 enter mininet](https://github.com/muriash/SDN/assets/90574857/f534b45b-ed2a-490c-8c07-7f040886080f)

## <a name="part_2">Упражнение 2</a>
### 1. Для выполнения задания был создан скрипт LinearTopo.py, в котором описана простая топология сети
![3 script code](https://github.com/muriash/SDN/assets/90574857/6db0e24a-45df-481e-b095-8ac23571082e)

### 2. Результат выполнения скрипта LinearTopo.py
![4 success linearTopo](https://github.com/muriash/SDN/assets/90574857/7820ab9f-d903-458c-8ff9-3eb8020cbca8)

### 3. Из архива  module3-assignment1.zip был взят и дополнен скрипт CustomTopo.py для создания топологии дерева
![5 script customTopo](https://github.com/muriash/SDN/assets/90574857/f86576e7-59ab-4c94-8606-6679b7f06efd)
![5 1 script customTopo](https://github.com/muriash/SDN/assets/90574857/cf127b61-703a-41b8-9e7f-d52f483a803e)

4. Результат выполнения скрипта CustomTopo.py
![6 success customTopo](https://github.com/muriash/SDN/assets/90574857/21c669b0-4192-4536-bb1f-d6e7253215da)

## <a name="part_3">Упражнение 3</a>
1. Перед началом работы был установлен xterm, а также проведен перезапуск Mininet командой sudo mn -c
2. Запуск компонента hub
![9 hub connected](https://github.com/muriash/SDN/assets/90574857/c11240a0-3880-48f7-9381-d6dea88f2cef)
3. Для проверки поведения хаба для каждого узла был запущен xterm с помощью команды xterm h1 h2 h3
4. Результат пинга узлов h2 и h3. Видно, что хостами были получены идентичные пакеты, следовательно хаб работает исправно и отправляет все пакеты на каждый порт сети
![10 ping](https://github.com/muriash/SDN/assets/90574857/1fbcd523-024c-4987-bf83-b30b345a6e7a)
5. При указании некорректного IP-адреса в команде ping была получена ошибка "Destination Host Unreachable"
![11 ping error](https://github.com/muriash/SDN/assets/90574857/3e116c91-1604-4bac-ad6b-8558b3d64d6c)

## <a name="part_4">Вывод</a>
В ходе выполнения данных упражнений была изучена работа со средой моделирования MiniNet, в которой были построены примеры базовых топологий сети. Также была проведена работа с контроллером POX, в результате которой был успешно запущен хаб.
