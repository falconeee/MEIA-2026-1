all: compila executa

compila:
	gcc T1-1.c -lm -o executavel

executa:
	./executavel < arquivoentrada > arquivosaida.txt 2>&1

clear:
	rm executavel arquivosaida.txt