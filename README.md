# Bienvenue
Programme C++ qui affiche "Bienvenue le monde !" en utilisant la fonction
`afficherBienvenue()`. sourour
L'exécution d'une commande Linux :
```sh
$ make rebuild
Fabrication du programme : bienvenue
rm -f *.o
g++ -c -Wall -std=c++11 bienvenue.cpp
g++ -c -Wall -std=c++11 fonction-bienvenue.cpp
g++ -o bienvenue bienvenue.o fonction-bienvenue.o
$ ./bienvenue
Bienvenue le monde !
```
defzfnzfefnlnlzfs
Le contenu d'un fichier source C++ :
```cpp
#ifndef FONCTION_BIENVENUE_H
#define FONCTION_BIENVENUE_H
void afficherBienvenue();
#endif // FONCTION_BIENVENUE_
