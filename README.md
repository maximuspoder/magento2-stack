# Magento 2 - Simple Stack


| Stack | Version |
|--|--|
| Apache | 2.4.25 |
|PHP|7.1.25|
| Redis | 4.0.11 |
| MariaDB | 15.1 Distrib 10.3.11-MariaDB |

## How to connect to Apache2/PHP container?
    docker exec -it "apache-container-name" bash

## How to connect to Mariadb?

    docker exec -it "mariadb-container-name" mysql -umagento -pmagento
