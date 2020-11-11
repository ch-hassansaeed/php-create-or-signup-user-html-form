# php-create-or-signup-user-html-form
php create or signup user html form include resources like css and js files





for detail and step by step video
https://hzonesp.com/php/create-signup-user-insert-salt-sha256-hash-password-mysql/

https://www.youtube.com/watch?v=Wu6RNXDIHn8

Overview

In this Tutorial we made PHP signup form and link this signup form with our dummy website template this signup form will html5 confirm password validation and signup data will insert into mysql database table and password hash encrypted with sha256.
plus this tutorial has following things
-create table and table colmuns
-make auto increment column and primary key column
-difference between varchar and int
user table SQL script snippet code :

--
-- Table structure for table `user`
--

CREATE TABLE IF NOT EXISTS `user` (
`user_id` int(111) NOT NULL AUTO_INCREMENT,
`username` varchar(255) NOT NULL,
`password` varchar(255) NOT NULL,
`salt` varchar(255) NOT NULL,
PRIMARY KEY (`user_id`)
) ENGINE=InnoDB  DEFAULT CHARSET=latin1 AUTO_INCREMENT=7 ;


Summary

PHP signup form with html5 confirm password validation and signup data will insert into mysql database table and password hash encrypted with sha256.
