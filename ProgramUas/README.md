# ProductManager
This repository is using spring boot java and MVC method with mySQL database with CRUD product


# Create MySQL Database
You can execute the following MySQL script to create the **product** table:

```
CREATE TABLE `product` (
  `id` int(11) NOT NULL AUTO_INCREMENT,
  `name` varchar(45) NOT NULL,
  `brand` varchar(45) NOT NULL,
  `madein` varchar(45) NOT NULL,
  `price` float NOT NULL,
  PRIMARY KEY (`id`)
) ENGINE=InnoDB DEFAULT CHARSET=utf8;
```

The name of the database schema is **sales**.
# Project-Uas
