all: compila executa

compila:
	stanc T1-2.stan > compilacao.txt 2>&1

executa:
	./executavel sample < arquivoentrada > arquivosaida 2>&1

clear:
	rm -f executavel arquivosaida compilacao.txt T1-2.hpp