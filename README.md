# UI Lab 5
![](terminal-icon.png)
![](gui-icon.png)

Це одна з робіт, які доповнюють основний цикл лабораторних робіт #1-8 (проект **Banking**, [Netbeans](https://netbeans.org/)) з ООП.  Основна мета цих додаткових вправ - познайомитись з різними видами інтерфейсів користувача та засобами їх створення. Згадувані 'базові' роботи розміщено в [окремому репозиторії](https://github.com/liketaurus/OOP-JAVA) (якщо будете робити завдання на "4" або "5" раджу переглянути [діаграму класів](https://github.com/liketaurus/OOP-JAVA/blob/master/MyBank.png), аби розуміти які методи є у класів).

В ході цієї роботи вам пропонується виконати **наступне завдання** - [Робота 5: GUI з JavaFX](https://github.com/ppc-ntu-khpi/GUI-Lab3-Starter/blob/master/Lab%205%20-%20JavaFX/Lab%205.md)
  
**Додаткове завдання** (для тих хто зробив все і прагне більшого): [дивіться тут](https://github.com/ppc-ntu-khpi/GUI-Lab3-Starter/blob/master/Lab%205%20-%20JavaFX/Lab%20-%205%20-%20add.md)

Всі необхідні бібліотеки містяться у теці [jars](https://github.com/ppc-ntu-khpi/GUI-Lab3-Starter/tree/master/jars). В тому числі - всі необхідні відкомпільовані класи з робіт 1-8 - файл [MyBank.jar](https://github.com/ppc-ntu-khpi/GUI-Lab3-Starter/blob/master/jars/MyBank.jar). Файл даних лежить у теці [data](https://github.com/ppc-ntu-khpi/GUI-Lab3-Starter/tree/master/data).

---
## На "трійку" 
1. Завантажте jar-файл з усіма потрібними классами (*Bank, Customer, Account* та ін.) з наших попередніх лаб - [MyBank](https://github.com/ppc-ntu-khpi/GUI-Lab3-Starter/blob/master/jars/MyBank.jar) 
2. Створіть в Netbeans новий проект з назвою FxDemo (або використайте проект, створений в ході виконання попередньої роботи). *УВАГА! Чекбокс *Create Main Class* треба **очистити** (**не створювати виконуваний клас**)!* 
3. Додайте до проекту завантажену вами бібліотеку - правою кнопкой на проекті, обрати *Properties*, потім у дереві категорій обрати *Libraries* (другий пункт зверху), натиснути у правій частині вікна кнопку *Add JAR/Folder*, обрати jar-файл, завантажений у п. 1, натиснути *Ok* 
4. Додайте до проекту клас [FXDemo](https://github.com/ppc-ntu-khpi/GUI-Lab3-Starter/blob/master/Lab%205%20-%20JavaFX/FXDemo.java) з цього репозитрію.
5. Вивчіть вихідний код класу, впевніться, що ви розумієте як він має працювати 
6. Запустіть проект у звичайний спосіб. Ви маєте побачити вікно, в якому можна обрати клієнта і переглянути баланс його першого рахунку та переглянути інформацію про програму. Продемонстрируйте результат викладачеві. 

![](https://github.com/ppc-ntu-khpi/javafx-34-DESTROYchambo/blob/363e4d8bc13ba1dad0475cecd78f40e0ce781950/images/%D0%97%D0%BD%D1%96%D0%BC%D0%BE%D0%BA%20%D0%B5%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202025-06-15%20171338.png)

## На "п'ять"
1. Долайте до форми кнопку **Report**, яка має виводити у нижній частині вікна звіт за клієнтами такого ж виду, як у роботі номер 8 (див. CustomerReport).
2. Запустіть проект, впевніться, що все працює як очікувалось. Продемонстрируйте результат викладачеві. 

![](https://github.com/ppc-ntu-khpi/javafx-34-DESTROYchambo/blob/363e4d8bc13ba1dad0475cecd78f40e0ce781950/images/%D0%97%D0%BD%D1%96%D0%BC%D0%BE%D0%BA%20%D0%B5%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202025-06-15%20171352.png)

**УВАГА! Не забудьте завантажити результат виконання роботи до вашого власного репозиторію - в проекті 'Banking' цей класс має бути в пакеті com.mybank.gui!**
