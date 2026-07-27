### Exercício 1 — acesso direto
```
int obter(int vetor[], int i) {
 return vetor[i];
}
```
- _a) Quantas operações primitivas são realizadas?_ <br> 2
- _b) A complexidade depende de n?_ <br> Não

### Exercício 2 — contagem em um vetor
```
int contarPares(int vetor[], int n) {
 int quantidade = 0;
 for (int i = 0; i < n; i++) {
 if (vetor[i] % 2 == 0) {
 quantidade++;
 }
 }
 return quantidade;
}
```
- _a) Quantas vezes a condição é avaliada?_ <br> n
- _b) A quantidade de incrementos pode mudar?_ <br> 
- _c) Qual é a complexidade no melhor e no pior caso?_ <br>

### Exercício 3 — dois laços sequenciais
```
for (int i = 0; i < n; i++) {
 printf("%d\n", vetor[i]);
}
for (int j = 0; j < n; j++) {
 soma += vetor[j];
}
```
- _Determine T(n) de forma simplificada e explique por que o resultado não é Theta(n²)._ <br>

### Exercício 4 — laços aninhados
```
for (int i = 0; i < n; i++) {
 printf("%d\n", vetor[i]);
}
for (int j = 0; j < n; j++) {
 soma += vetor[j];
}
```
- _Quantas vezes a linha comparacoes++ é executada?_ <br>
-  _Qual é a classe de crescimento?_ <br>

### Exercício 5 — análise de casos
```
int contem(int vetor[], int n, int x) {
 for (int i = 0; i < n; i++) {
   if (vetor[i] == x) {
     return 1;
   }
 }
 return 0;
}
```
- _Descreva uma entrada de melhor caso, uma entrada de pior caso e uma hipótese adequada para calcular o caso
médio._ <br>
- _a) Quantas vezes a condição é avaliada?_ <br> n
- _b) A quantidade de incrementos pode mudar?_ <br> 
- _c) Qual é a complexidade no melhor e no pior caso?_ <br>
