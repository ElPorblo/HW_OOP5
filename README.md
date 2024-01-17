# HW_OOP5
Добавил метод delete  в класс UserRepository 

Перенесли из папки dao, методы saveAll и readAll метод в UserRepository 

Изменил createUser() на public static createUser() и перенес метод в UserRepository,  
так же как и метод prompt, сделал его  public static String prompt  
Таким образом в UserView для пользователя, остался только один метод public void run.  


Изменил ввод команд на цифры 