### Version posgreSQL :

```sql
CREATE TABLE products (
    id INTEGER GENERATED ALWAYS AS IDENTITY PRIMARY KEY,
    name TEXT NOT NULL,
    price NUMERIC (10 , 2) NOT NULL,
    stock INTEGER DEFAULT 0,
);
```

### Comparaison :

1. le SQLite est pratique pour apprendre et prototyper car il est leger et simple à prendre en main
2. PostgreSQL est mieux adapté à une application web multi-utilisateur car il offre plus de fonctionnalité, de securité et il gère bien de nombreux utilisateur
3. « base basée sur un fichier » signifie que toute la base est stockée dans un fichier
4. une vraie application Django peut fonctionner avec SQLite en développement puis PostgreSQL en production grace à l'ORM (Object-Relational Mapper)
