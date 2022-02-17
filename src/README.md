#Описание
количество куриных бедер расчитывается неправильно (с округлением)

#Локация дефекта
https://github.com/scriperirk/javaqa2-homeworks-pervii/blob/dbbe3a307efe4f11b71dfa792b4ced8acd2a0a0e/src/Main.java#L14

#Шаги воспроизведения
1.Открыть [код программы]https://github.com/scriperirk/javaqa2-homeworks-pervii/blob/dbbe3a307efe4f11b71dfa792b4ced8acd2a0a0e/src/Main.java
2.Запустить программу
3.Посмотреть на вывод в консоли

*Ожидаемый результат:* куриных бёдер должно быть 1.2 (chicken = 6,eaters = 5.  6/5 = 1.2)
*Фактический результат:* куриных бёдер равно 1 (chicken = 6,eaters = 5)

#Скриншот
https://github.com/scriperirk/javaqa2-homeworks-pervii/blob/c52dcc563579852909188f8aef37885dcd5c9f57/Screenshot.png

#Окружение
* **Операционнаы система:** Windows 10
* **IDE:** IntelliJ IDEA 2021.3.1 (Community Edition)
* **Java:** OpenJDK 11