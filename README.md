```
g++ -o helloworld helloworld.cpp
objdump -S --disassemble helloworld > helloworld.dump
g++ -S -o helloworld.s helloworld.cpp
```
