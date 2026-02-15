# Основы БД

## ER диаграмма в гит хабе через mermaid 
```mermaid
    erDiagram
        User ||--|{ Order : has
        Order {
            int id
            string name
            datetime date
        }
        User {
            int id
            string name
        }
```
