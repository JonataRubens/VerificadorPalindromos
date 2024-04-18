# VerificadorPalindromos
 

Este é um programa em C# que verifica se uma frase ou palavra é um palíndromo.

1. **Declaração de `using`**:
   - O programa utiliza o namespace `System` para ter acesso às funcionalidades básicas de entrada e saída.

2. **Classe `V_Palindromos`**:
   - Declara uma classe chamada `V_Palindromos`.

3. **Método `Main`**:
   - Este é o ponto de entrada do programa.
   - Solicita ao usuário que digite uma frase ou palavra.
   - Chama o método `limpaFrase()` para remover espaços em branco e pontuações da frase inserida.
   - Chama o método `verificador()` para verificar se a frase limpa é um palíndromo.
   - Imprime na tela se a frase é ou não um palíndromo.

4. **Método `limpaFrase(string frase)`**:
   - Recebe uma string `frase` como parâmetro.
   - Remove espaços em branco e pontuações da frase.
   - Converte a frase para letras minúsculas.
   - Retorna a frase limpa.

5. **Método `verificador(string frase)`**:
   - Recebe uma string `frase` como parâmetro.
   - Calcula o comprimento da frase.
   - Itera sobre a metade da frase, verificando se o caractere na posição atual é igual ao caractere na posição correspondente do outro lado da frase.
   - Se em algum momento os caracteres não forem iguais, retorna `false`.
   - Se a verificação passar por todos os caracteres, retorna `true`.

Este programa é útil para verificar se uma frase ou palavra é um palíndromo, ou seja, se ela pode ser lida da mesma forma de trás para frente e vice-versa. Ele remove espaços em branco, pontuações e diferencia maiúsculas de minúsculas antes de realizar a verificação.
