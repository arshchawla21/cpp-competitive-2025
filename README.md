# C++ Competitive Programming Templated (ICPC)

`kactl.cpp` and `strategy.cpp` forked from [kactl](https://github.com/kth-competitive-programming/kactl), containing key algorithms/dsa and strategy ideas for ICPC and similar group programming contests.

Using the foundation, we build two C++ CP template files, a minimal one `temp.cpp` and more feature heavy `dsa.cpp`. We also integrate `.vscode` enabled `lldb` debugging, via a simple to use `Makefile`. 

### Key Commands

```
make
```
> Cleans all files
```
make A
```
> Compiles file A.cpp

```
make A DB=1
```
> Compiles files A.cpp with LOCAL DEBUG set

> [!Tip]
> On vscode, install `CodeLLDB` extension and press _run & debug_ for line-by-line debugger.

```
./A < input.txt > output.txt
```
> Runs A executable using input.txt, results stored in output.txt
