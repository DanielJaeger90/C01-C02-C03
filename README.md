Ejercicios de la Piscina 42 Urduliz de 2024

C01: ex00, ex01, ex02, ex03, ex04, ex05, ex06, ex07, ex08.

C02: ex00, ex01, ex02, ex03, ex04, ex05, ex06, ex07, ex08, ex09, ex10, ex11.

C03: ex00, ex01, ex02, ex03, ex04.


C01 - EX00

Escribe una función que reciba como parámetro un puntero a un int y dé al int
el valor 42.

C01 -EX01

Escribe una función que reciba como parámetro un puntero a un puntero a un
puntero a un puntero un puntero a un puntero a un puntero a un puntero a un
puntero a un int y dé al int el valor 42.

C01 -EX02

Escribe una función que intercambie el contenido de dos enteros cuyas direcciones
se utilicen como parámetro.

C01 - EX03

• Escribe una función ft_div_mod que tenga el prototipo siguiente:
void ft_div_mod(int a, int b, int *div, int *mod);

• Esta función divide los dos parámetros a y b y almacena el resultado en el int
apuntado por div.

También almacena el resto de la división de a y b en el int apuntado por mod.

C01 - EX04

Escribe una función ft_ultimate_div_mod que tenga el prototipo siguiente:

void ft_ultimate_div_mod(int *a, int *b);

• Esta función divide los int apuntados por a y b.

El resultado de la división se almacena en el int apuntado por a.

El resultado del resto de la división se almacena en el int apuntado por b

C01 - EX05

Escribe una función que muestre uno a uno en la pantalla los caracteres de un
string.

• La dirección del primer carácter del string está incluida en el puntero utilizado como
parámetro para a la función.

• El prototipo de la función deberá ser el siguiente:

void ft_putstr(char *str);

C01 -EX06

Escribe una función que cuente el número de caracteres de un string y que devuelva
el número encontrado.

• El prototipo de la función deberá ser el siguiente:

int ft_strlen(char *str);

C01 -EX07

Escribe una función que invierta un array de int (el primer elemento va el último,
etc).

• Los parámetros son un puntero a int y el número de int en el array.

• El prototipo de la función deberá ser el siguiente:

void ft_rev_int_tab(int *tab, i


C01 - EX08

Escribe una función que ordene un array de int en orden ascendente.

• Los parámetros son un puntero a int y el número de int en el array.

• El prototipo de la función deberá ser el siguiente:

void ft_sort_int_tab(int *tab, int size);

_____________________________________________________________________________________  

C02 - EX00
Reproduce el comportamiento de la función strcpy (man strcpy)

• El prototipo de la función deberá ser el siguiente:

char *ft_strcpy(ch

PRIMER PASO:

%> mkdir ex00
%> cd ex00

%> man strcpy

SYNOPSIS
     #include <string.h>

     char *
     strcpy(char *restrict s1, const char *restrict s2);

DESCRIPTION
     The stpcpy() and strcpy() functions copy the string s2 to s1 (including
     the terminating '\0' character).

RETURN VALUES
     The strcpy() and strncpy() functions return s1.
     
%> vim ft_strcpy.c
--------------------------------------------------------------------------------------

C02 - EX01

Reproduce el comportamiento de la función strncpy (man strncpy)

• El prototipo de la función deberá ser el siguiente:

char *ft_strncpy(char *str);

--------------------------------------------------------------------------------------

C02 - EX02

Crea una función que devuelva 1 si el string usado como parámetro contiene únicamente caracteres alfabéticos y devuelva 0 si contiene otro tipo de caracteres.

• El prototipo de la función deberá ser el siguiente:

int ft_str_is_alpha(char *str);

• Tendrá que devolver 1 si str es un string vacío.

---------------------------------------------------------------------------------------

CO2 -EX03

Crea una función que devuelva 1 si el string usado como parámetro contiene únicamente dígitos y devuelva 0 si contiene otro tipo de caracteres.

• El prototipo de la función deberá ser el siguiente:

int ft_str_is_numeric(char *str);

• Tendrá que devolver 1 si str es un string vacío

_--------------------------------------------------------------------------------------

C02 - EX04

Crea una función que devuelva 1 si el string usado como parámetro contiene únicamente caracteres alfabéticos en minúsculas y devuelva 0 si contiene otro tipo de
caracteres.

• El prototipo de la función deberá ser el siguiente:

int ft_str_is_lowercase(char *str);

• Tendrá que devolver 1 si str es un string

---------------------------------------------------------------------------------------

C02 - EX05

Crea una función que devuelva 1 si el string usado como parámetro contiene únicamente caracteres alfabéticos en mayúsculas y devuelva 0 si contiene otro tipo de
caracteres.

• El prototipo de la función deberá ser el siguiente:

int ft_str_is_uppercase(char *str);

• Tendrá que devolver 1 si str es un sting vacío.

_______________________________________________________________________________________


C02 - EX06

Crea una función que devuelva 1 si el string usado como parámetro contiene únicamente caracteres imprimibles y devuelva 0 si contiene otro tipo de caracteres.

• El prototipo de la función deberá ser el siguiente:

int ft_str_is_printable(char *str);

• Tendrá que devolver 1 si str es un string vacío.

________________________________________________________________________________________

C02 - EX07

Crea una función que ponga cada letra en mayúscula.

• El prototipo de la función deberá ser el siguiente:

char *ft_strupcase(char *str);

• Deberá devolver str.

______________________________________________________________________________________

C02 - EX08

Crea una función que ponga cada letra en minúscula.

• El prototipo de la función deberá ser el siguiente:

char *ft_strlowcase(char *str);

• Deberá devolver str

______________________________________________________________________________________

C02 - EX09

Creaa una función que ponga en mayúscula la primera letra de cada palabra y el
resto de la palabra en minúsculas.

• Una palabra es una secuencia (string) de caracteres alfanuméricos.

• El prototipo de la función deberá ser el siguiente:

char *ft_strcapitalize(char *str);

• Deberá devolver str.

• Por ejemplo:

salut, comment tu vas ? 42mots quarante-deux; cinquante+et+un

• Se convierte en:

Salut, Comment Tu Vas ? 42mots Quarante-Deux; Cinquante+Et+Un

_______________________________________________________________________________________

C02 - EX10

Reproduce el comportamiento de la función strlcpy (man strlcpy)

• El prototipo de la función deberá ser el siguiente:

unsigned int ft_strlcpy(char *dest, cha *src, unsigned int size);

_______________________________________________________________________________________

Escribe una función que muestre una secuencia de caracteres en la pantalla. Si esta
secuencia contiene caracteres no imprimibles, deberán ser mostrados en formato
hexadecimal (en minúsculas) precedidos de una barra invertida (backslash).

• Por ejemplo, con este parámetro:

Coucou\ntu vas bien ?

• La función tendrá que mostrar:

Coucou\0atu vas bien ?

• El prototipo de la función deberá ser el siguiente:

void ft_putstr_non_printable(char *str);

________________________________________________________________________________________

C02 - EX11

Escriba una función que muestre la región de memoria en la pantalla.

• La visualización de la región de memoria estará dividida en tres “columnas” separadas por un espacio:

◦ La dirección en hexadecimal del primer carácter de la línea seguido de “:”.

◦ El contenido en hexadecimal, con un espacio cada dos caracteres, deberá ser

completado con espacios si es preciso (ver el ejemplo a continuación).

◦ El contenido en caracteres imprimibles.

• Si un carácter es no imprimible será remplazado por un punto.

• Cada línea debe contener dieciséis caracteres.

• Si size es igual a 0, no se muestra nada.

• Ejemplo:
$> ./ft_print_memory
000000010a161f40: 426f 6e6a 6f75 7220 6c65 7320 616d 696e Bonjour les amin
000000010a161f50: 6368 6573 090a 0963 0720 6573 7420 666f ches...c. est fo
000000010a161f60: 7509 746f 7574 0963 6520 7175 206f 6e20 u.tout.ce qu on
000000010a161f70: 7065 7574 2066 6169 7265 2061 7665 6309 peut faire avec.
000000010a161f80: 0a09 7072 696e 745f 6d65 6d6f 7279 0a0a ..print_memory..
000000010a161f90: 0a09 6c6f 6c2e 6c6f 6c0a 2000 ..lol.lol. .
$> ./ft_print_memory | cat -te
0000000107ff9f40: 426f 6e6a 6f75 7220 6c65 7320 616d 696e Bonjour les amin$
0000000107ff9f50: 6368 6573 090a 0963 0720 6573 7420 666f ches...c. est fo$
0000000107ff9f60: 7509 746f 7574 0963 6520 7175 206f 6e20 u.tout.ce qu on $
0000000107ff9f70: 7065 7574 2066 6169 7265 2061 7665 6309 peut faire avec.$
0000000107ff9f80: 0a09 7072 696e 745f 6d65 6d6f 7279 0a0a ..print_memory..$
0000000107ff9f90: 0a09 6c6f 6c2e 6c6f 6c0a 2000 2e 6c6f 6c0a 2000 ..lol.lol. .$
$>
• El prototipo de la función deberá ser el siguiente:

void *ft_print_memory(void *addr, unsigned int size);

Deberá devolver addr.

______________________________________________________________________________________________

C03 - EX00

Reproduce el comportamiento de la función strcmp (man strcmp).

• El prototipo de la función deberá ser el siguiente:

int ft_strcmp(char *s1, char *s2);

---------------------------------------------------------------------------------------

C03 - EX01

Reproduce el comportamiento de la función strncmp (man strncmp).

• El prototipo de la función deberá ser el siguiente:

int ft_strncmp(char *s1, char *s2, unsigned int n);

-------------------------------------------------------------------------------------------------------

C03 - EX02

Reproduce el comportamiento de la función strcat (man strcat).

• El prototipo de la función deberá ser el siguiente:

char *ft_strcat(char *dest, char *src);

------------------------------------------------------------------------------------------

C03 -EX03

Reproduce el comportamiento de la función strncat (man strncat).

• El prototipo de la función deberá ser el siguiente:

char *ft_strncat(char *dest, char *src, unsigned int nb);

--------------------------------------------------------------------------------------

C03 - EX04

Reproduce el comportamiento de la función strstr (man strstr).

• El prototipo de la función deberá ser el siguiente:

char *ft_strstr(char *str, char *to_find);
