# firstjob
#include<stdio.h>
#include <locale.h>
int main() //
{
	setlocale(LC_ALL, "Russian");
	int year, month;
	year = 2022;
	const char* psz = "C++";
	char name[6] = "Dasha";
	printf("Сейчас %d год \n", year);
	printf("Программа: %s \n", psz);
	printf("Имя %s \n", name);
}

