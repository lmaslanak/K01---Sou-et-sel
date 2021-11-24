Napište program, který přečte ze standardního vstupu dvě čísla typu int, sečte je a vypíše na standardni výstup výsledek.

Vytisknutí proveďte ve funkci main:

#include <stdio.h>

int main() {
  return 0;
}
Program můžete zkompilovat a spustit pomocí:

$ gcc main.c -o main
$ ./main
HINT: Ze standardního vstupu se dá načíst pomocí funkce scanf (popis ve skriptech). Použití může být např. následující:

int x, y;

scanf( "%d %d", &x, &y );
