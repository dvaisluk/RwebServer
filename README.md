# Установка и запуск веб-сервера в Linux
## Цель работы
### Освоить основные навыки установки и первоначальной настройки веб-сервера в ОС Linux.
## Задания для выполнения
1.Используя apt-get установить Apache2 на виртуальную машину

![image](https://user-images.githubusercontent.com/70855182/141357590-27d00014-3c3b-41d1-aff4-2a991766d366.png)

2.С браузера хост-машины по IP-адресу виртуальной машины увидеть приветствие

![image](https://user-images.githubusercontent.com/70855182/141357614-0dd0e4c7-fd11-456e-a2ce-abdde5d70aaa.png)

![image](https://user-images.githubusercontent.com/70855182/141357630-90139789-3954-419a-9a8c-b3f3393c0b9b.png)

3.В настройках сервера изменить  порт на :8080

![image](https://user-images.githubusercontent.com/70855182/141357675-7745d78c-9986-4b62-a8d2-7cc93a880441.png)

![image](https://user-images.githubusercontent.com/70855182/141357694-afb504e1-d28c-4474-810e-bc8798897eba.png)

4.Снова выполнить п 2, но с указанием порта

![image](https://user-images.githubusercontent.com/70855182/141357739-3d5dc387-223f-4661-87cd-5c874086b616.png)

![image](https://user-images.githubusercontent.com/70855182/141357751-37f8ab07-ea99-43f2-b623-16096d2a25dd.png)

5.Изменить порт обратно и проверить как работает заглушка

![image](https://user-images.githubusercontent.com/70855182/141357796-506ee4f7-15d6-40b5-8d9d-97eedd11e81d.png)

![image](https://user-images.githubusercontent.com/70855182/141357806-8ca7d02f-0ec5-40b5-b8a5-942b81c0e580.png)

![image](https://user-images.githubusercontent.com/70855182/141357822-f95c9b2d-053f-4fb1-a630-d749b99ea71f.png)

6.В hosts хост-машины создать три домена: a1.com, b2.com, c3.com и связываем с IP виртуальной машины с Apache

![image](https://user-images.githubusercontent.com/70855182/141357855-74d06755-0e4a-4443-8147-7704ac4f2b31.png)

7.Для каждого домена проверить всё ли правильно, с помощью ping

![image](https://user-images.githubusercontent.com/70855182/141357883-c2995468-3b77-44f4-b6bd-8e8f5717d2f6.png)

![image](https://user-images.githubusercontent.com/70855182/141357899-ec0d6be8-b20e-4a90-98d3-2f153ea48348.png)

![image](https://user-images.githubusercontent.com/70855182/141357919-961513d4-ecbd-422b-855d-97bd9be0b491.png)

8.Зайти на все три домена, написав их вместо IP виртуальной машины

![image](https://user-images.githubusercontent.com/70855182/141357931-740a210a-62c7-4fe8-85ab-3d4d22e0069c.png)

![image](https://user-images.githubusercontent.com/70855182/141357953-68cf7ea8-595f-45bf-b48a-9b0d46cd5b94.png)

![image](https://user-images.githubusercontent.com/70855182/141357961-9db34b75-16e4-4157-a8bb-523c46d91b6b.png)

9.Создать директории /var/www/a1.com, /var/www/b2.com, /var/www/c3.com

![image](https://user-images.githubusercontent.com/70855182/141358043-18c7dde7-b2b2-4025-9837-d04b1f7e976b.png)

10.В каждой из них создать пустой index.html

![image](https://user-images.githubusercontent.com/70855182/141358062-8c623133-159a-4002-a246-bfbe1c44ad8f.png)

11.В каждом из них написать различное содержимое

![image](https://user-images.githubusercontent.com/70855182/141358092-b7196e74-fcdf-4bd6-b2d0-384a99ed8410.png)

![image](https://user-images.githubusercontent.com/70855182/141358125-baef294e-a62d-45fd-a42a-b7eb9fc200fd.png)

![image](https://user-images.githubusercontent.com/70855182/141358139-1fa681d9-d43a-4a6b-863f-f28bff3b24e9.png)

12.Сделать так, чтобы из браузеров хост-машины открывались сайты из директории, а не общая заглушка

![image](https://user-images.githubusercontent.com/70855182/141358202-5742c3d1-cf30-4bd0-9124-0a974ebfda70.png)

![image](https://user-images.githubusercontent.com/70855182/141358218-2c236ba7-f45d-4147-9e44-69f612773284.png)

![image](https://user-images.githubusercontent.com/70855182/141358241-4879ee53-dbf7-401e-ab77-5de7480547cc.png)

![image](https://user-images.githubusercontent.com/70855182/141358278-9dd35639-e427-4f21-ae25-d89d423470e3.png)

![image](https://user-images.githubusercontent.com/70855182/141358303-b02a3c1e-7742-46f7-a7cb-bc86c2df0844.png)
