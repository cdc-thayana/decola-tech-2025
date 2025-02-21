# Decola Tech-2025
java Restful API Web criada para dio.me bootcamp decola tech2025

#Diagrama de Classes
```mermaid
classDiagram
    class User {
        +string name
        +Account account
        +Feature[] features
        +Card card
        +News[] news
    }

    class Account {
        +string number
        +string agency
        +float balance
        +float limit
    }

    class Feature {
        +string icon
        +string description
    }

    class Card {
        +string number
        +float limit
    }

    class News {
        +string icon
        +string description
    }

    User --> Account
    User --> Feature : has multiple
    User --> Card
    User --> News : has multiple
```
