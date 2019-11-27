all: test
  
test: test.o b_tree.o
    g++ test.o b_tree.o -o test -std=c++11

b_tree.o: b_tree.cpp
    g++ -c b_tree.cpp -std=c++11
test.o: test.cpp
    g++ -c test.cpp -std=c++11

clean:
    rm -rf *.o test