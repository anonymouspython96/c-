g++ -o c-/Sintassi variable_and_data_type.cpp
cc1plus: fatal error: variable_and_data_type.cpp: No such file or directory
compilation terminated.

g++ -o Sintassi variable_and_data_type.cpp 
variable_and_data_type.cpp: In function ‘int main()’:
variable_and_data_type.cpp:11:19: error: ‘Marco’ was not declared in this scope
   11 |     string nome = Marco;
      |                   ^~~~~

operators.cpp: In function ‘int main()’:
operators.cpp:24:89: error: expected ‘;’ before ‘cin’
   24 |     cout << "Insert a number for the switch: ( if you will select 1 it will print One )"
      |                                                                                         ^
      |                                                                                         ;
   25 |     cin << y;
      |     ~~~          