# A PROPOS

## ndoung sam hermann;

## le titre : Semaine 9 - Jour 1 - Introduction aux bases de données

1. une définition courte d’une base de données relationnelle ;
2. la clé primaire est une colonne qui identifie chaque
   ligne de manière unique ;
3. SQLite est une base stockée dans un fichier unique alors que PostgreSQL est serveur de base de données complet;

### Exercice réalisées:

- ex1_students.sql.
- ex2_courses . sql
- ex3_sqlite_vs_postgresql.md

### Exercice 1

- chaque table doit avoir une clé primaire pour permetre de les relier à d'autres tables et montrer que chaque ligne est unique
- la colone représente un attribut ou une caractéristique spécifique des données stockée dans une table
- l'email est un ensemble de caractère et age des chiffres

### Exercice 2

| Critère               | students                                          | courses                                                  |
| --------------------- | ------------------------------------------------- | -------------------------------------------------------- |
| Clé primaire          | id                                                | id                                                       |
| Colonnes TEXT         | first_name,last_name,email                        | title,description,level                                  |
| Colonnes INTEGER      | id, age, created_at                               | id,duration_hours, created_at                            |
| Valeur par défaut     | heure actuel                                      | beginner                                                 |
| Colonnes obligatoires | id,first_name,last_name,email,id, age, created_at | id,title,description,level,id,duration_hours, created_at |
