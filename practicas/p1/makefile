CC=g++
CFLAGS=-std=c++11 -w
NUMBERS = 1.0 5.0 10.0 15.0 20.0 25.0 30.0 35.0 40.0 45.0

main: simula.exe
	
	
	

simula.exe: simula.cpp 
	$(CC) $(CFLAGS) -o simula simula.cpp



pruebas:
	rm salidas.txt
	$(foreach var,$(NUMBERS),./simula 10 10 15.0 30.0 $(var) 365.0 1000 >> salidas.txt;)