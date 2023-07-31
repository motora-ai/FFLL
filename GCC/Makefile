# Project: Static Lib
# Makefile created by Dev-C++ 4.9.4.1

CC   = g++
RES  = 
OBJ  = ../RuleArray.o ../COGDefuzzSetObj.o ../COGDefuzzVarObj.o ../DefuzzSetObj.o ../DefuzzVarObj.o ../FFLLAPI.o ../FFLLBase.o ../FuzzyModelBase.o ../FuzzyOutSet.o ../FuzzyOutVariable.o ../FuzzyOutVariableBase.o ../FuzzySetBase.o ../FuzzyVariableBase.o ../MemberFuncBase.o ../MemberFuncSCurve.o ../MemberFuncSingle.o ../MemberFuncTrap.o ../MemberFuncTri.o ../MOMDefuzzSetObj.o ../MOMDefuzzVarObj.o
LIBS =
PREFIX_INCLUDE = /usr/local/include/ffll
PREFIX_LIB = /usr/local/lib  
INCS =  
BIN  = libffll.a
CFLAGS = $(INCS)  -fexceptions -O3

.PHONY: clean

all: libffll.a

clean:
	rm -f $(OBJ) $(BIN)
	
install:
	mkdir $(PREFIX_INCLUDE)
	cp ../COGDefuzzSetObj.h $(PREFIX_INCLUDE) 
	cp ../DefuzzVarObj.h $(PREFIX_INCLUDE)
	cp ../FFLLBase.h $(PREFIX_INCLUDE)
	cp ../FuzzyOutSet.h $(PREFIX_INCLUDE)
	cp ../FuzzyOutVariable.h $(PREFIX_INCLUDE)
	cp ../FuzzyVariableBase.h $(PREFIX_INCLUDE)
	cp ../MemberFuncSCurve.h $(PREFIX_INCLUDE)
	cp ../MemberFuncTrap.h $(PREFIX_INCLUDE)
	cp ../MOMDefuzzSetObj.h $(PREFIX_INCLUDE)
	cp ../RuleArray.h $(PREFIX_INCLUDE)
	cp ../COGDefuzzVarObj.h $(PREFIX_INCLUDE)
	cp ../DefuzzSetObj.h $(PREFIX_INCLUDE)
	cp ../FFLLAPI.h $(PREFIX_INCLUDE)
	cp ../FuzzyModelBase.h $(PREFIX_INCLUDE)
	cp ../FuzzyOutVariableBase.h $(PREFIX_INCLUDE)
	cp ../FuzzySetBase.h $(PREFIX_INCLUDE)
	cp ../MemberFuncBase.h $(PREFIX_INCLUDE)
	cp ../MemberFuncSingle.h $(PREFIX_INCLUDE)
	cp ../MemberFuncTri.h $(PREFIX_INCLUDE)
	cp ../MOMDefuzzVarObj.h $(PREFIX_INCLUDE)
	cp libffll.a $(PREFIX_LIB)
	

$(BIN): $(OBJ)
	ar -r $(BIN) $(OBJ)
	ranlib $(BIN)

../RuleArray.o: ../RuleArray.cpp 
	$(CC) -c ../RuleArray.cpp -o ../RuleArray.o $(CFLAGS)

../COGDefuzzSetObj.o: ../COGDefuzzSetObj.cpp 
	$(CC) -c ../COGDefuzzSetObj.cpp -o ../COGDefuzzSetObj.o $(CFLAGS)

../COGDefuzzVarObj.o: ../COGDefuzzVarObj.cpp 
	$(CC) -c ../COGDefuzzVarObj.cpp -o ../COGDefuzzVarObj.o $(CFLAGS)

../DefuzzSetObj.o: ../DefuzzSetObj.cpp 
	$(CC) -c ../DefuzzSetObj.cpp -o ../DefuzzSetObj.o $(CFLAGS)

../DefuzzVarObj.o: ../DefuzzVarObj.cpp ../DefuzzVarObj.h ../FFLLBase.h
	$(CC) -c ../DefuzzVarObj.cpp -o ../DefuzzVarObj.o $(CFLAGS)

../FFLLAPI.o: ../FFLLAPI.cpp 
	$(CC) -c ../FFLLAPI.cpp -o ../FFLLAPI.o $(CFLAGS)

../FFLLBase.o: ../FFLLBase.cpp ../FFLLBase.h ../FuzzyVariableBase.h
	$(CC) -c ../FFLLBase.cpp -o ../FFLLBase.o $(CFLAGS)

../FuzzyModelBase.o: ../FuzzyModelBase.cpp 
	$(CC) -c ../FuzzyModelBase.cpp -o ../FuzzyModelBase.o $(CFLAGS)

../FuzzyOutSet.o: ../FuzzyOutSet.cpp 
	$(CC) -c ../FuzzyOutSet.cpp -o ../FuzzyOutSet.o $(CFLAGS)

../FuzzyOutVariable.o: ../FuzzyOutVariable.cpp 
	$(CC) -c ../FuzzyOutVariable.cpp -o ../FuzzyOutVariable.o $(CFLAGS)

../FuzzyOutVariableBase.o: ../FuzzyOutVariableBase.cpp 
	$(CC) -c ../FuzzyOutVariableBase.cpp -o ../FuzzyOutVariableBase.o $(CFLAGS)

../FuzzySetBase.o: ../FuzzySetBase.cpp 
	$(CC) -c ../FuzzySetBase.cpp -o ../FuzzySetBase.o $(CFLAGS)

../FuzzyVariableBase.o: ../FuzzyVariableBase.cpp 
	$(CC) -c ../FuzzyVariableBase.cpp -o ../FuzzyVariableBase.o $(CFLAGS)

../MemberFuncBase.o: ../MemberFuncBase.cpp 
	$(CC) -c ../MemberFuncBase.cpp -o ../MemberFuncBase.o $(CFLAGS)

../MemberFuncSCurve.o: ../MemberFuncSCurve.cpp 
	$(CC) -c ../MemberFuncSCurve.cpp -o ../MemberFuncSCurve.o $(CFLAGS)

../MemberFuncSingle.o: ../MemberFuncSingle.cpp 
	$(CC) -c ../MemberFuncSingle.cpp -o ../MemberFuncSingle.o $(CFLAGS)

../MemberFuncTrap.o: ../MemberFuncTrap.cpp 
	$(CC) -c ../MemberFuncTrap.cpp -o ../MemberFuncTrap.o $(CFLAGS)

../MemberFuncTri.o: ../MemberFuncTri.cpp 
	$(CC) -c ../MemberFuncTri.cpp -o ../MemberFuncTri.o $(CFLAGS)

../MOMDefuzzSetObj.o: ../MOMDefuzzSetObj.cpp 
	$(CC) -c ../MOMDefuzzSetObj.cpp -o ../MOMDefuzzSetObj.o $(CFLAGS)

../MOMDefuzzVarObj.o: ../MOMDefuzzVarObj.cpp 
	$(CC) -c ../MOMDefuzzVarObj.cpp -o ../MOMDefuzzVarObj.o $(CFLAGS)
