## GDBugger


GDB é uma ferramenta poderosa e útil para depurar programas em C e C++. Ele fornece várias funcionalidades que podem ajudar a encontrar e corrigir erros em um programa, permitindo que os(as) desenvolvedores trabalhem de forma mais eficiente e eficaz. <br>

Principais funcionalidades:
- Inspreção de Variaveis: Permite visualizar o valor atual das variaveis em um determinado ponto do programa.
- Definição de pontos de interrupção: Permite definir pontos de interrupção em partes especificas do programa.
- Execução do passo-a-passo: Permite executar o programa passo a passo, permitindo que você veja como o programa está sendo executado.
- Analise de ponteiros: Permite identificar erros relacionados à manipulação de ponteiros, como acesso inválido à memória, vazamento de memória e outros erros de gerenciamento de memória (rastreando o caminho que ele segue dentro da memoria).

> Ele é igual ao [Python Tutor](https://pythontutor.com/) usado durante a piscina para ver por debaixo do capô da Linguagem C, só que ele atende a codigos maiores e complexos.

❗️| Dicas baseadas no GDB (GNU Debugger) para a debugação do codigo em terminais Unix.


<!-- 
Sumario:
- Instalação:
- Preparação do ambiente de desenvolvimento:
- Compilação do código com opções de depuração (-g):
- Comandos básicos do GDB:
- Exibição de variáveis:
- Configuração de breakpoints:
- Boas práticas para escrever código fácil de depurar:
- Como evitar armadilhas comuns durante a depuração:
- Recursos adicionais: 


**Compilação do código: **

1. Compile o programa com a opção -g para incluir informações de depuração no executavel gerado:
```bash
$ gcc -g meu_programa.c -o meu_programa
```
2. Caso queira que o GDB :<br>
Seja iniciado no modo normal: <br>
```bash
$ gdb meu_programa
```
Caso queira que o GDB inicie no modo visual:<br>
```bash
$ gdb --tui ./meu_programa
```
Caso queira que o GDB inicie no modo visual e argumentos na linha de comando:<br>
```bash
$ gdb --tui --args ./meu_programa "abc"
```
-->
