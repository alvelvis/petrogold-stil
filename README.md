# petrogold-stil
Files used in STIL2023 to present and test different versions of the gold-standard treebank PetroGold

Paper: (soon)

Presentation: https://docs.google.com/presentation/d/1eQQCrYCpPgtIQ-pMuCXtDB_zb37Xe916i58-5AJ3-OM/

How to cite: (soon)

Files follow this pattern:

> pt_{a}-{b}-{c}-ud-{d}.conllu

Where:

* a: corpus (petrogold,bosque)
* b: where it's published (petroles-v3,petroles-v2,ud-2.11)
* c: variation (none for base,mwepos,simplificado)
* d: partition (train,test,dev,test-system)
  * `test-system` stands for the test file annotated by the model generated using train+dev
