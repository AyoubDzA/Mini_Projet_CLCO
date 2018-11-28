CREATE TABLE `users` (
  `idUser` int(11) NOT NULL,
  `firstName` varchar(45) NOT NULL,
  `lastName` varchar(45) NOT NULL,
  `email` varchar(45) NOT NULL,
  `password` varchar(45) NOT NULL,
  PRIMARY KEY (`idUser`)
) 
INSERT INTO `mini_proj_clco`.`users`
(`idUser`,
`firstName`,
`lastName`,
`email`,
`password`)
VALUES
(<{idUser: }>,
<{firstName: }>,
<{lastName: }>,
<{email: }>,
<{password: }>);


CREATE TABLE `history` (
  `idHistory` int(11) NOT NULL,
  `day` datetime DEFAULT NULL,
  PRIMARY KEY (`idHistory`)
) 

INSERT INTO `mini_proj_clco`.`history`
(`idHistory`,
`day`)
VALUES
(<{idHistory: }>,
<{day: }>);


CREATE TABLE `user_transformations` (
  `idHistory` int(11) NOT NULL,
  `idUser` int(11) NOT NULL,
  `fromFile` varchar(45) NOT NULL,
  `toFile` varchar(45) NOT NULL,
  PRIMARY KEY (`idHistory`,`idUser`),
  KEY `idUser` (`idUser`),
  CONSTRAINT `idHistory` FOREIGN KEY (`idHistory`) REFERENCES `history` (`idHistory`) ON DELETE NO ACTION ON UPDATE NO ACTION,
  CONSTRAINT `idUser` FOREIGN KEY (`idUser`) REFERENCES `users` (`idUser`) ON DELETE NO ACTION ON UPDATE NO ACTION
) 
INSERT INTO `mini_proj_clco`.`user_transformations`
(`idHistory`,
`idUser`,
`fromFile`,
`toFile`)
VALUES
(<{idHistory: }>,
<{idUser: }>,
<{fromFile: }>,
<{toFile: }>);
