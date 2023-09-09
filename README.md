# petrogold-stil
Files used in STIL2023 to present and test different versions of the gold-standard treebank PetroGold

Title: Explorando variações no tagset e na anotação Universal Dependencies (UD) para Português: Possibilidades e resultados com base no treebank PetroGold

Paper: https://sol.sbc.org.br/index.php/stil/article/view/25444

Presentation: https://docs.google.com/presentation/d/1eQQCrYCpPgtIQ-pMuCXtDB_zb37Xe916i58-5AJ3-OM

How to cite:

```
@inproceedings{de2023explorando,
  title={Explorando varia{\c{c}}{\~o}es no tagset e na anota{\c{c}}{\~a}o Universal Dependencies (UD) para Portugu{\^e}s: Possibilidades e resultados com base no treebank PetroGold},
  author={de{ }Souza, Elvis and Freitas, Cl{\'a}udia},
  booktitle={Anais do XIV Simp{\'o}sio Brasileiro de Tecnologia da Informa{\c{c}}{\~a}o e da Linguagem Humana},
  pages={125--134},
  year={2023},
  organization={SBC}
}
```

Files follow this pattern:

> pt_{a}-{b}-{c}-ud-{d}.conllu

Where:

* a: corpus (petrogold,bosque)
* b: where it's published (petroles-v3,petroles-v2,ud-2.11)
* c: variation (none for base,mwepos,simplificado)
* d: partition (train,test,dev,test-system)
  * `test-system` stands for the test file annotated by the model generated using train+dev
