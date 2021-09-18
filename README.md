# USER WEB PAGE 

| author | Description | version |
| ----------- | ----------- | ------- |
| Gianfranco | Spring Boot Web + Jquery + Ajax | 1.0.0 |

---

### Install application XAMPP

Install version XAMPP 7.3.30 / PHP 7.3.30 

### Compile application with spring boot

![com](img/compile.PNG)

### Server Mysql

http://localhost/phpmyadmin/index.php

````roomsql
CREATE TABLE `usuarios` (
  `id` bigint(20) NOT NULL,
  `nombre` varchar(40) COLLATE utf8_bin NOT NULL,
  `apellido` varchar(40) COLLATE utf8_bin NOT NULL,
  `email` varchar(255) COLLATE utf8_bin NOT NULL,
  `telefono` varchar(40) COLLATE utf8_bin DEFAULT NULL,
  `password` varchar(255) COLLATE utf8_bin NOT NULL
);
````

````roomsql
INSERT INTO `usuarios` (`id`, `nombre`, `apellido`, `email`, `telefono`, `password`) VALUES
(5, 'Gianfranco', 'Lazo', 'gianLazo@gmail.com', NULL, '$argon2id$v=19$m=1024,t=1,p=1$NC3hasjIOHNOQddb2PD27w$/J3VF5uOHR0ZgnWle5Qvt8Mnb/GEkGUZt3GP1rKcRLc'),
(9, 'Gladys', 'Vasquez', 'gian@gmail', NULL, '$argon2id$v=19$m=1024,t=1,p=1$MxvBc5LATtXdNmzMNDxbOQ$c0p0qxfIDEgbfV2ya+OvDnW9vfK0VslE07lPE9aglc0');
````

![img.png](img/img.png)

### Create table



### REFERENCES

[XAMPP](https://www.apachefriends.org/download.html)