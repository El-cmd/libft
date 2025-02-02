# Libft

Cette bibliothèque contient une collection de fonctions utilitaires en C, recréant certaines fonctions standard de la libc ainsi que d'autres fonctions auxiliaires couramment utilisées.

## Liste des Fonctions

### Fonctions de manipulation de caractères
- `ft_isalpha` : Vérifie si un caractère est alphabétique
- `ft_isdigit` : Vérifie si un caractère est un chiffre
- `ft_isalnum` : Vérifie si un caractère est alphanumérique
- `ft_isascii` : Vérifie si un caractère est dans la table ASCII
- `ft_isprint` : Vérifie si un caractère est imprimable
- `ft_toupper` : Convertit un caractère en majuscule
- `ft_tolower` : Convertit un caractère en minuscule

### Fonctions de manipulation de chaînes
- `ft_strlen` : Calcule la longueur d'une chaîne
- `ft_strchr` : Recherche la première occurrence d'un caractère dans une chaîne
- `ft_strrchr` : Recherche la dernière occurrence d'un caractère dans une chaîne
- `ft_strncmp` : Compare deux chaînes jusqu à n caractères
- `ft_strlcpy` : Copie une chaîne source dans une destination avec une taille limitée
- `ft_strlcat` : Concatène deux chaînes avec une taille limitée
- `ft_strnstr` : Recherche une sous-chaîne dans une chaîne avec une limite de taille
- `ft_strdup` : Duplique une chaîne
- `ft_strjoin` : Joint deux chaînes
- `ft_strtrim` : Retire les caractères spécifiés au début et à la fin d'une     chaîne
- `ft_split` : Divise une chaîne en utilisant un caractère délimiteur
- `ft_strmapi` : Applique une fonction à chaque caractère d'une chaîne

### Fonctions de manipulation de mémoire
- `ft_memset` : Remplit une zone mémoire avec un octet donné
- `ft_bzero` : Met à zéro une zone mémoire
- `ft_memcpy` : Copie une zone mémoire
- `ft_memccpy` : Copie une zone mémoire jusqu'à un caractère donné
- `ft_memmove` : Copie une zone mémoire avec gestion du chevauchement
- `ft_memchr` : Recherche un caractère dans une zone mémoire
- `ft_memcmp` : Compare deux zones mémoire
- `ft_calloc` : Alloue et initialise une zone mémoire

### Fonctions de conversion
- `ft_atoi` : Convertit une chaîne en entier
- `ft_itoa` : Convertit un entier en chaîne

### Fonctions d'output
- `ft_putchar_fd` : Écrit un caractère sur un descripteur de fichier
- `ft_putstr_fd` : Écrit une chaîne sur un descripteur de fichier
- `ft_putendl_fd` : Écrit une chaîne suivie d'un retour à la ligne sur un descripteur de fichier
- `ft_putnbr_fd` : Écrit un nombre sur un descripteur de fichier

### Fonctions de manipulation de listes chaînées
- `ft_lstnew` : Crée un nouveau maillon de liste
- `ft_lstadd_front` : Ajoute un élément au début de la liste
- `ft_lstadd_back` : Ajoute un élément à la fin de la liste
- `ft_lstsize` : Compte le nombre d'éléments dans une liste
- `ft_lstlast` : Retourne le dernier élément d'une liste
- `ft_lstdelone` : Supprime un élément de la liste
- `ft_lstclear` : Supprime et libère la liste entière
- `ft_lstiter` : Applique une fonction à chaque élément de la liste
- `ft_lstmap` : Crée une nouvelle liste en appliquant une fonction à chaque élément

## Compilation

Pour compiler la bibliothèque, utilisez la commande `make`. Cela créera le fichier `libft.a`.

## Utilisation

Pour utiliser la bibliothèque dans votre projet :
1. Compilez la bibliothèque avec `make`
2. Incluez le header `libft.h` dans vos fichiers source
3. Liez votre programme avec `libft.a`

## Normes de Codage

Toutes les fonctions sont écrites selon la norme de l'école 42.