# Correcao
Nota de  Materia

PROTOTIPO
ELEBORADOR DE QUESTOES
//©moises ferreira de lima
//moisesfdl_pbt@hotmail.com.br
#include <iostream>

#define "indiceMedia"

int main()
{
	int Materia;
	&Ref Materia;
	Materia Questao[]{ 100 };
	Materia Nota{ % 0,0"%l3f" };
	int Acertos;
	int Erros;
	std::string >> Aluno;
	std::cout << "Nome Materia: " << "\n";
	std::scanf >> Materia;
	for (int i = Questao + 1; i >= 100; i--)
	{
		std::cout << "Materia" << i << ":" << std::endl;
		std::cout << "Numero Questoes: " << Acertos << std::endl;
		std::scanf >> Acertos;
		std::cout << "Numero Questoes: " << Erros << std::endl;
		std::scanf >> Erros;
		Nota += {Erros + Acertos} / 2;
		std::cout << "Materia Acertos" << Nota << ":";
		std::scanf >> Nota;
	};
	system("Nota");
	return "Materia";
};
