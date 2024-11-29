# CJSONWORK 

CJSONWORK est un objet ecrit en C++ qui comme dependance 

``` 
QJsonDocument
QJsonObject
QFile
QJsonValue
QJsonParseError
QString
```

L'objet a pour but de gerer les fichier JSON 

# Detail methode  

``` C++

CJSONWORD()
```
Constructeur de base 

``` C++
CJSONWORD(QString fileName)
```
Constructeur qui prend en paramètre le fichier JSON (constructeur à utiliser en priorité)

``` C++
bool isExist(QString cles)
```
Méthode qui permet de vérifier si une clé existe dans le fichier JSON. Retourne ```True``` si elle existe et ```False``` sinon.

``` C++
QString read(QString cles)
```

Méthode qui permet de lire une clé passée en paramètre. Retourne ```"error"``` si la clé n'existe pas.

``` C++
bool write(QString cles, QString valeur)
```

Méthode qui permet d'écrire une clé (passée en paramètre) et sa valeur (également passée en paramètre). Retourne ```True``` si l'opération a réussi, et ```False``` en cas de problème.

# Crédit 

Développer par Enzo B et publier par Baptiste P 
