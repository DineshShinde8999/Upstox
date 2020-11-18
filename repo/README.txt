
trades.json file path,at line number of main.cpp(23).

Command line arguement : ./main SymbolName interval

Implementation
Worker 1 and Worker 2 is implemented. Socket part is yet to be done.

main.cpp
		
wk.h/wk.cpp(Worker thread1 implemented inside this)
		This class will take care of the reading and quequeing the data. JSON parser is used to read json file.

wk1.h/wk1.cpp (Worker thread2 implemented inside this)
		This class will be processing the queue on time interval basis and display over the console