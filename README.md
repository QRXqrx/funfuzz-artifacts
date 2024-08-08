# FunFuzz Artifacts
The code and data of the TOSEM submission of FunFuzz.

We are trying hard cleaning up the code and data. Full artifacts will be available soon :-).

Specifically, the artifacts will include:

- `aflpp-fun`: The source code of FunFuzz.
- `fun-scripts`: The python and bash scripts for running experiments and analyzing data.
- `data`: The experiemtnal results presented in the submitted paper. 
- `aflgo-funexp`: A modified version of [AFLGo artifact](https://github.com/aflgo/aflgo) for the purpose of FunFuzz experiments, which includes an extra customized compiler for extracting locations of function declarations, scripts for transforming the extracted locations into the format of target sites required by AFLGo, and a `README.md` documenting the experimental setups.
