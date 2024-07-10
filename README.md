# BOOT CAMP PROJECT
Java RESTful API

#Diagrama de Classes
```mermaid
classDiagram
    class User {
        +String name
        +Account account
        +Card card
        +List~Feature~ features
        +List~News~ news
    }

    class Account {
        +String number
        +String agency
        +double balance
        +double limit
    }

    class Card {
        +String number
        +double limit
    }

    class Feature {
        +String icon
        +String description
    }

    class News {
        +String icon
        +String description
    }

    User --> Account
    User --> Card
    User --> Feature
    User --> News
    ```
