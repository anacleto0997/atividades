# Aprendendo Programação em C
#### Um jeito diferente de aprender programação.

## Atividade Planejada de Fixação

>	(Desafio)Complete o código abaixo elaborando as questões das opções de menu apresentadas na função questoes(). Implemente o uso de um laço de repetição (loop) até que o estudante digite 11 (Sair). Cada questão tem sua propria função. A elaboração da questão fica a seu critério para cada assunto listado no menu de questões. Ao final, execute o código e veja se o programa roda perfeitamente. (1,5 - Um ponto e meio na nota 3).
```C
// Online C compiler to run C program online
#include <stdio.h>

void cabecalho(){
    printf("\nMinistério da Educação");
    printf("\nUniversidade Federal do Piauí");
    printf("\nDepartamento de Tecnologia");
    printf("\nCurso de Engenharia Civil");
}

int questoes(){
    int questao;
    printf("\n[1] - Tecnologia");
    printf("\n[2] - Lógica");
    printf("\n[3] - Estrutura básica de C");
    printf("\n[4] - Variaveis");
    printf("\n[5] - Tipo de dados e condicionais");
    printf("\n[6] - Laços de repetição");
    printf("\n[7] - Funções sem parâmetros");
    printf("\n[8] - Funções com parâmetros");
    printf("\n[9] - Vetores");
    printf("\n[10] - Registros");
    printf("\n[11] - Sair");
    printf("\nQual questão você deseja fazer.: ");
    scanf("%d",&questao);
    return questao;
}

void questao01(){
    int x;
    fflush(stdin);
    printf("\n\nO que significa na sua opinião 'informática'?");
    printf("\n[1] - Tecnologias de processamento em meio digital");
    printf("\n[2] - Informação automática");
    printf("\n\nEscolha.: ");
    scanf("%d",&x);
    if (x == 1){
        printf("\nmenos um ponto.");
    }else{
        printf("\nacertou. Um ponto");
    }
}

void questao02(){
    
}

void questao03(){
    
}

void questao04(){
    
}
void questao05(){
    
}

void questao06(){
    
}

void questao07(){
    
}

void questao08(){
    
}

void questao09(){
    
}
void questao10(){
    
}
int main() {
    int opc;
    cabecalho();
    printf("\n----------------------------------------------------------------------");
    opc = questoes();
    switch(opc){
        case 1: {
            questao01();break;
        }
        case 2: {
            questao02();break;
        }
        case 3:{
            questao03();break;
        }
        case 4:{
            questao04();break;
        }
        case 5:{
            questao05();break;
        }
        case 6:{
            questao06();break;
        }
        case 7:{
            questao07();break;
        }
        case 8:{
            questao08();break;
        }
        case 9:{
            questao09();break;
        }
        case 10:{
            questao10();break;
        }
    }
    return 0;
}
```
resposta:
```
#include <stdio.h>

void cabecalho(){
    printf("\nMinistério da Educação");
    printf("\nUniversidade Federal do Piauí");
    printf("\nDepartamento de Tecnologia");
    printf("\nCurso de Engenharia Civil");
}

int questoes(){
    int questao;
    printf("\n[1] - Tecnologia");
    printf("\n[2] - Lógica");
    printf("\n[3] - Estrutura básica de C");
    printf("\n[4] - Variaveis");
    printf("\n[5] - Tipo de dados e condicionais");
    printf("\n[6] - Laços de repetição");
    printf("\n[7] - Funções sem parâmetros");
    printf("\n[8] - Funções com parâmetros");
    printf("\n[9] - Vetores");
    printf("\n[10] - Registros");
    printf("\n[11] - copa do mundo");
    printf("\n[12] - Sair");
    printf("\nQual questão você deseja fazer.: ");
    scanf("%d",&questao);
    return questao;
}

void questao01(){
    int x;
    fflush(stdin);
    printf("\n\nO que significa na sua opinião 'informática'?");
    printf("\n[1] - Tecnologias de processamento em meio digital");
    printf("\n[2] - Informação automática");
    printf("\n\nEscolha.: ");
    scanf("%d",&x);
    if (x == 1){
        printf("\nmenos um ponto.");
    }else{
        printf("\nacertou. Um ponto");
    }
}

void questao02(){
 int x;
    fflush(stdin);
    printf("\n\nO Pode-se afirmar que o xou é um operador de:?");
    printf("\n[1] - disjunção exclusiva.");
    printf("\n[2] - conjunção.");
    printf("\n\nEscolha.: ");
    scanf("%d",&x);
    if (x == 1){
        printf("\nacertou um ponto.");
    }else{
        printf("\nerrou menos Um ponto");
    }
}   


void questao03(){
int x;
    fflush(stdin);
    printf("\n\nO Qual é a estrutura básica de um programa em C?");
    printf("\n[1] -  estruturado em blocos de código.");
    printf("\n[2] - estruturado em numeros");
    printf("\n\nEscolha.: ");
    scanf("%d",&x);
    if (x == 1){
        printf("\nacertou um ponto.");
    }else{
        printf("\nerrou menos Um ponto");
    }

}

void questao04(){
int x;
    fflush(stdin);
    printf("\n\nO Quais desses, sao tipos de variáveis na programação??");
    printf("\n[1] - Variável número do tipo inteiro");
    printf("\n[2] - Variavel numero do tipo decimal");
    printf("\n\nEscolha.: ");
    scanf("%d",&x);
    if (x == 1){
        printf("\nacertou um ponto.");
    }else{
        printf("\nerrou menos Um ponto");
    }

}
void questao05(){
int x;
    fflush(stdin);
    printf("\n\nO O que é condicional simples programação?");
    printf("\n[1] - definimos uma situação no código que só irá ocorrer se a condição for verdadeira");
    printf("\n[2] -  definimos uma situação no código que só irá ocorrer se a condição for falsa");
    printf("\n\nEscolha.: ");
    scanf("%d",&x);
    if (x == 1){
        printf("\nacertou um ponto.");
    }else{
        printf("\nerrou menos Um ponto");
    }    
}

void questao06(){
int x;
    fflush(stdin);
    printf("\n\nO Qual e o proposito principal dos lacos de repeticao na programacao?");
    printf("\n[1] - permitir que um conjunto de comandosseja executado varias vezes");
    printf("\n[2] - Ajudar a depurar erros no codigo");
    printf("\n\nEscolha.: ");
    scanf("%d",&x);
    if (x == 1){
        printf("\nacertou um ponto.");
    }else{
        printf("\nerrou menos Um ponto");
    }        
}

void questao07(){
int x;
    fflush(stdin);
    printf("\n\nO o que sao funcoes sem parametros na programcao?");
    printf("\n[1] - funcoes que nao recebem nenhum valor de entrada ");
    printf("\n[2] - funcoes que nao podem ser chamadas de programa");
    printf("\n\nEscolha.: ");
    scanf("%d",&x);
    if (x == 1){
        printf("\nacertou um ponto.");
    }else{
        printf("\nerrou menos Um ponto");
    }            
}

void questao08(){
int x;
    fflush(stdin);
    printf("\n\nO o que sao parametros em uma funcao com parametros na programacao?");
    printf("\n[1] - valores de entrada que a funcao recebe quando e chamada ");
    printf("\n[2] - variaveis locais que podem ser usadas em qualquer parte do codigo");
    printf("\n\nEscolha.: ");
    scanf("%d",&x);
    if (x == 1){
        printf("\nacertou um ponto.");
    }else{
        printf("\nerrou menos Um ponto");
    }                
}

void questao09(){
int x;
    fflush(stdin);
    printf("\n\nO o que sao vetores na programacao?");
    printf("\n[1] - sequencias ordenadas de elementos do mesmo tipo, ecessadas por um indice ");
    printf("\n[2] - variaveis que armazenam apenas valores do tipo string");
    printf("\n\nEscolha.: ");
    scanf("%d",&x);
    if (x == 1){
        printf("\nacertou um ponto.");
    }else{
        printf("\nerrou menos Um ponto");
    }                    
}
void questao10(){
int x;
    fflush(stdin);
    printf("\n\nO o que sao registros na programacao?");
    printf("\n[1] - conjuntos de diferentes tipos de dados agrupados em uma unica estrutura ");
    printf("\n[2] - variaveis que armazenam apenas valores numericos");
    printf("\n\nEscolha.: ");
    scanf("%d",&x);
    if (x == 1){
        printf("\nacertou um ponto.");
    }else{
        printf("\nerrou menos Um ponto");
    }                       
}
void questao11(){
    int x;
    fflush(stdin);
    printf("\n\n qual selecao tem mais copas do mundo?");
    printf("\n[1] - Brasil");
    printf("\n[2] - italia");
    printf("\n\nEscolha.: ");
    scanf("%d",&x);
    if (x == 1){
        printf("\nacertou um ponto.");
    }else{
        printf("\nerrou menos Um ponto");
    }
}
int main() {
    int opc;
    cabecalho();
    printf("\n----------------------------------------------------------------------");

    do {
        printf("\n");
        printf("\n[1] - Tecnologia");
        printf("\n[2] - Logica");
        printf("\n[3] - Estrutura basica de C");
        printf("\n[4] - Variaveis");
        printf("\n[5] - Tipo de dados e condicionais");
        printf("\n[6] - Laços de repeticao");
        printf("\n[7] - Funcoes sem parametros");
        printf("\n[8] - Funcoes com parametros");
        printf("\n[9] - Vetores");
        printf("\n[10] - registros");
        printf("\n[11] - copa do mundo");
        printf("\n[12] - Sair");
        printf("\nQual questao voce deseja fazer? Digite o numero correspondente: ");
        scanf("%d", &opc);

        switch(opc) {
            case 1:
                questao01();
                break;
            case 2:
                questao02();
                break;
            case 3:
                questao03();
                break;
            case 4:
                questao04();
                break;
            case 5:
                questao05();
                break;
            case 6:
                questao06();
                break;
            case 7:
                questao07();
                break;
            case 8:
                questao08();
                break;
            case 9:
                questao09();
                break;
            case 10:
                questao10();
                break;
            case 11:
                questao11();
                break;
            case 12:
                printf("\nSaindo do programa.\n");
                break;
            default:
                printf("\nOpcao invalida. Tente novamente.\n");
                break;
        }
    } while (opc != 12);

    return 0;
}
```



## Vetor de registros

```C
#include <stdio.h>
#include<stdlib.h>

//Definindo a estrutura e criando o nosso cardápio
struct Cardapio{
    char tipoTapioca[30];
    int qtdBolo;
    char tipoCafe[20];
};
//Programa principal
int main() {
    //criando nosso vetor 'rest' do tipo estrutura de cardápio.
    struct Cardapio rest[2];
    //lendo os pedidos e preenchendo nosso registro.
    for (int i=0; i<2;i++){
        printf("\nTipo tapioca.: ");
        scanf("%s",rest[i].tipoTapioca);
        printf("\nQtd Bolo.: ");
        scanf("%d",&rest[i].qtdBolo);
        printf("\ntipo cafe.: ");
        scanf("%s",rest[i].tipoCafe);
    }
//Imprimindo todos os pedidos feitos	
    for (int i=0; i<2; i++){
        printf("\n-------------------------------------");
        printf("\ntapioca => %s",rest[i].tipoTapioca);
        printf("\nbolos=> %d",rest[i].qtdBolo);
        printf("\ncafe=> %s",rest[i].tipoCafe);
    }
    return 0;
}
```
>	QT13(crucial) - Altere o código acima para preencher um vetor de registros de 10 posições, ems seguida mostre todos os pedidos feitos. Após isso, crie seu próprio código de vetor de registro. Comente cada linha do código de acordo com seu entendimento.
>
>
```C
>#include <stdio.h>
#include<stdlib.h>

//Definindo a estrutura e criando o nosso cardápio
struct Cardapio{
    char tipoTapioca[30];
    int qtdBolo;
    char tipoCafe[20];
};
//Programa principal
int main() {
    //criando nosso vetor 'rest' do tipo estrutura de cardápio.
    struct Cardapio rest[10];
    //lendo os pedidos e preenchendo nosso registro.
    for (int i=1; i<11;i++){
        printf("\nTipo tapioca.: ");
        scanf("%s",rest[i].tipoTapioca);
        printf("\nQtd Bolo.: ");
        scanf("%d",&rest[i].qtdBolo);
        printf("\ntipo cafe.: ");
        scanf("%s",rest[i].tipoCafe);
    }
//Imprimindo todos os pedidos feitos	
    for (int i=1; i<11; i++){
        printf("\n-------------------------------------");
        printf("\ntapioca => %s",rest[i].tipoTapioca);
        printf("\nbolos=> %d",rest[i].qtdBolo);
        printf("\ncafe=> %s",rest[i].tipoCafe);
    }
    return 0;
}
```
```C
#include <stdio.h>
#include <stdlib.h>

// Definir a estrutura para a passagem de ônibus
struct PassagemOnibus {
    char nomePassageiro[50];
    int numeroAssento;
    float precoPassagem;
};

int main() {
    // Criar um array de passagens de ônibus
    struct PassagemOnibus passagensOnibus[10];

    // Ler e preencher os detalhes das passagens de ônibus
    for (int i = 0; i < 10; i++) {
        printf("\nNome do passageiro %d: ", i + 1);
        scanf("%s", passagensOnibus[i].nomePassageiro);

        printf("Número do assento: ");
        scanf("%d", &passagensOnibus[i].numeroAssento);

        printf("Preço da passagem: ");
        scanf("%f", &passagensOnibus[i].precoPassagem);
    }

    // Imprimir todos os detalhes das passagens
    printf("\n--- Detalhes das Passagens de Ônibus ---\n");
    for (int i = 0; i < 10; i++) {
        printf("\nPassageiro %d: %s", i + 1, passagensOnibus[i].nomePassageiro);
        printf("\nAssento: %d", passagensOnibus[i].numeroAssento);
        printf("\nPreço da Passagem: %.2f", passagensOnibus[i].precoPassagem);
        printf("\n------------------------");
    }

    return 0;
}
```


# Registros em C - Uma forma legal de criar uma "ficha" sobre alguma coisa.
### Nos exemplos a seguir vamos ver códigos com Structs em C que representa um registro, ou seja, tipos diferentes de dados em uma mesma estrutura.
#### Observe o código abaixo auto-explicativo e faça as questões seguintes.

```C
#include <stdio.h>
#include <conio.h>
int main(void)
{
  /*Criando a struct */
  struct ficha_de_aluno
  {
    char nome[100];
    char disciplina[100];
    float nota_prova1;
    float nota_prova2;
  };
  
  /*Criando a variável aluno que será do
  tipo struct ficha_de_aluno */
  struct ficha_de_aluno aluno; //perceba que ficha_de_aluno é como se fosse um tipo. A vairável aluno está sendo criada com esse tipo.
  
  printf("\n---------- Cadastro de aluno -----------\n\n\n");
  
  printf("Nome do aluno ......: ");
  fflush(stdin);
  
  /*usaremos o comando fgets() para ler strings, no caso o nome
  do aluno e a disciplina.
  fgets(variavel, tamanho da string, entrada)
  como estamos lendo do teclado a entrada é stdin (entrada padrão),
  porém em outro caso, a entrada tambem poderia ser um arquivo */
  
  fgets(aluno.nome, 40, stdin);
  
  printf("Disciplina ......: ");
  fflush(stdin);
  fgets(aluno.disciplina, 40, stdin);
  
  printf("Informe a 1a. nota ..: ");
  
  scanf("%f", &aluno.nota_prova1);
  
  printf("Informe a 2a. nota ..: ");
  scanf("%f", &aluno.nota_prova2);
  
  printf("\n\n --------- Mostrando os dados da struct ---------\n\n");
  printf("Nome ...........: %s", aluno.nome);
  printf("Disciplina .....: %s", aluno.disciplina);
  printf("Nota da Prova 1 ...: %.2f\n" , aluno.nota_prova1);
  printf("Nota da Prova 2 ...: %.2f\n" , aluno.nota_prova2);
  
  getch();
  return(0);
}
```
>	QT11(0,25) - Crie estruturas novas e correlacione com sua realidade. Use estruturas de repetição e estruturas switch. Ao final, as fichas com os cadastros deverão ser apresentadas.
```c
#include <stdio.h>
#include <stdlib.h>

#define MAX_PESSOAS 100

typedef struct {
    char nome[50];
    int idade;
    char email[50];
} Cadastro;

int main() {
    Cadastro cadastros[MAX_PESSOAS]; 
    int numCadastros = 0; 
    int opcao;

    while (1) {
        printf("----- Menu -----\n");
        printf("1. Cadastrar pessoa\n");
        printf("2. Exibir fichas de cadastro\n");
        printf("3. Sair\n");
        printf("Escolha uma opcao: ");
        scanf("%d", &opcao);

        switch (opcao) {
            case 1:
                if (numCadastros < MAX_PESSOAS) {
                   
                    printf("Digite o nome da pessoa: ");
                    scanf("%s", cadastros[numCadastros].nome);
                    printf("Digite a idade da pessoa: ");
                    scanf("%d", &cadastros[numCadastros].idade);
                    printf("Digite o email da pessoa: ");
                    scanf("%s", cadastros[numCadastros].email);

                    numCadastros++;
                    printf("Cadastro realizado com sucesso!\n");
                } else {
                    printf("Limite máximo de cadastros atingido!\n");
                }
                break;

            case 2:
                printf("----- Fichas de Cadastro -----\n");
                for (int i = 0; i < numCadastros; i++) {
                    printf("Nome: %s\n", cadastros[i].nome);
                    printf("Idade: %d\n", cadastros[i].idade);
                    printf("Email: %s\n", cadastros[i].email);
                    printf("-----------------------------\n");
                }
                break;

            case 3:
                printf("Saindo...\n");
                exit(0);

            default:
                printf("Opção inválida! Por favor, escolha uma opção válida.\n");
        }
    }

    return 0;
}
```
>	QT12(0,25) - Crie estruturas em C para organizar alguma necessidade sua e realize o cadastro dos registros. Utilize estruturas de loop para realizar mais de um registro. Ao final, apresente todos os cadastros realizados. Justifique todo o seu código.
```c
#include <stdio.h>
#include <stdlib.h>

#define MAX_REGISTROS 5

struct registro_tipo_sanguineo
{
  char nome[100];
  char tipo_sanguineo[4];
  int idade;
};

int main()
{
  struct registro_tipo_sanguineo registros[MAX_REGISTROS];
  int i;

  printf("----------- Cadastro de Tipos Sanguineos -----------\n\n");

  for (i = 0; i < MAX_REGISTROS; i++)
  {
    printf("\nRegistro %d\n", i + 1);

    printf("Nome: ");
    fgets(registros[i].nome, sizeof(registros[i].nome), stdin);
    fflush(stdin);

    printf("Tipo Sanguineo: ");
    fgets(registros[i].tipo_sanguineo, sizeof(registros[i].tipo_sanguineo), stdin);
    fflush(stdin);

    printf("Idade: ");
    scanf("%d", &registros[i].idade);
    fflush(stdin);
  }

  printf("\n\n----------- Registros de Tipos Sanguineos -----------\n\n");

  for (i = 0; i < MAX_REGISTROS; i++)
  {
    printf("Registro %d\n", i + 1);
    printf("Nome: %s", registros[i].nome);
    printf("Tipo Sanguineo: %s", registros[i].tipo_sanguineo);
    printf("Idade: %d\n", registros[i].idade);
    printf("\n");
  }

  return 0;
}
```

# Funções em C

>	Declare funções. Uma com opção de menu para o R.U, Biblioteca Central, Teatro ou H.U e mostre-os na tela. Outra que mostre apenas uma saudação do dia após leitura do nome da pessoa. (QT9 - 0,25)
```c
include <stdio.h>

void exibirMenu() {
    printf("Opcoes:\n");
    printf("1. R.U\n");
    printf("2. Biblioteca Central\n");
    printf("3. Teatro\n");
    printf("4. H.U\n");
}

void exibirSaudacao() {
    char nome[50];
    printf("Digite seu nome: ");
    scanf("%s", nome);
    printf("Bom dia, %s!\n", nome);
}

int main() {
    int opcao;

    exibirMenu();
    printf("Digite uma opcao: ");
    scanf("%d", &opcao);

    switch (opcao) {
        case 1:
            printf("Voce selecionou R.U\n");
            break;
        case 2:
            printf("Voce selecionou Biblioteca Central\n");
            break;
        case 3:
            printf("Voce selecionou Teatro\n");
            break;
        case 4:
            printf("Voce selecionou H.U\n");
            break;
        default:
            printf("Opcao invalida\n");
            break;
    }

    exibirSaudacao();

    return 0;
}
```
>	Declare funções para: Totalizar a quantidade de árvores em cada setor(CCHL, CCE, CT, CCN, DIE, CCS) da ufpi através de entrada de dados pelo teclado. Ao final mostrar o total de árvores na UFPI. (Q10 - 25).
```c
#include <stdio.h>

int totalizarArvoresSetor(char setor[]) {
    int quantidade;
    printf("Digite a quantidade de arvores no setor %s: ", setor);
    scanf("%d", &quantidade);
    return quantidade;
}

int main() {
    int totalUfpi = 0;
    
    totalUfpi += totalizarArvoresSetor("CCHL");
    totalUfpi += totalizarArvoresSetor("CCE");
    totalUfpi += totalizarArvoresSetor("CT");
    totalUfpi += totalizarArvoresSetor("CCN");
    totalUfpi += totalizarArvoresSetor("DIE");
    totalUfpi += totalizarArvoresSetor("CCS");
    
    printf("Total de arvores na UFPI: %d\n", totalUfpi);
    
    return 0;
}
```

# Vetores em C
Declarar e preencher um vetor em C nos possibilita muitas utilizações. Observe a estrutura básica de um vetor em C.
Observe o código abaixo.
```C
#include <stdio.h>

int main()
{
    int meuVetor[3];
    
    meuVetor[0] = 32;
    meuVetor[1] = 10;
    meuVetor[2] = 5;
    
    printf("O valor dos vetores é: %d\n",meuVetor[0]);
    printf("O valor dos vetores é: %d\n",meuVetor[1]);
    printf("O valor dos vetores é: %d\n",meuVetor[2]);
    
    return 0;
}
```
>	QT04 (0,25 pontos) - Altere o código acima para 10 posições de vetor atribuindo 10 valores inteiros manuais e imprimindo todos eles na tela.
```c
#include <stdio.h>
int main()
{
    int meuVetor[9];
    meuVetor[0] = 32;
    meuVetor[1] = 10;
    meuVetor[2] = 5;
    meuVetor[3] = 3;
    meuVetor[4] = 4;
    meuVetor[5] = 6;
    meuVetor[6] = 7;
    meuVetor[7] = 8;
    meuVetor[8] = 9;
    meuVetor[9] = 10;
    printf("O valor dos vetores 0: %d\n",meuVetor[0]);
    printf("O valor dos vetores 1: %d\n",meuVetor[1]);
    printf("O valor dos vetores 2: %d\n",meuVetor[2]);
    printf("O valor dos vetores 3: %d\n",meuVetor[3]);
    printf("O valor dos vetores 4: %d\n",meuVetor[4]);
    printf("O valor dos vetores 5: %d\n",meuVetor[5]);
    printf("O valor dos vetores 6: %d\n",meuVetor[6]);
    printf("O valor dos vetores 7: %d\n",meuVetor[7]);
    printf("O valor dos vetores 8: %d\n",meuVetor[8]);
    printf("O valor dos vetores 9: %d\n",meuVetor[9]);
    return 0;
}
```

Para cada valor a partir da posição zero do vetor, temos um elemento. Cada posição é representada pelo símbolo de colchetes. Sempre iniciará da posição zero. Dessa forma, se o vetor de elementos tem 3 posições corresponderá às posições 0,1,2 (três elementos). A mesma ideia se aplica a qualquer quantidade de elementos.
Quando essa quantidade é bem grande, usamos laços de repetição. Observe o código abaixo.

```C
#include <stdio.h>
// Cada posição i do vetor é um valor multiplicado por 2. Usamos um for para preencher e outro for para mostrar.
int main()
{
    int meuVetor[10];
    
    for (int i=0; i<10; i++){
        meuVetor[i] = i*2;
    }
    for (int i=0; i<10; i++){
        printf("Posição %d e valor => %d \n",i,meuVetor[i]);
    }
    return 0;
}

```
>	QT05 (0,25 pontos) - Altere o código acima para que seja lido diretamente do teclado um valor inteiro, ao invés de atribuído. Mostre todos os valores lidos ao final.
```c
#include <stdio.h>
int main()
{
    int meuVetor[10];
    for (int i=0; i<20; i++){
        meuVetor[i] = i*2;
    }
    for (int i=0; i<20; i++){
        printf("Posicao %d e valor => %d \n",i,meuVetor[i]);
    }
    return 0;
}
```

Em algumas situações temos que impor condições para obter dados de tudo o que foi lido e armazenado em uma lista de vetores. Vejamos um exemplo no código abaixo:
```C
#include <stdio.h>

int main()
{
    int meuVetor[10]; 	//vetor de 10 elementos
    int numero;		//variável inteira
    int pos = 0;	//variável inteira e inicializada com zero
    int neg = 0;	// outra inteira e inicializada com zero	

//Essa estrtura for preenche o vetor
    for (int i=0; i<10; i++){
        printf("Digite um valor para o vetor: ");
        scanf("%d",&numero);
        meuVetor[i] = numero;
    }
//Essa verifica uma condição e totaliza os valores.
    for (int i=0; i<10; i++){
        if(meuVetor[i] > 0){
            pos = pos + 1;
        }else neg = neg + 1;
    }
//Ao final do código, mostra os valores totalizados.
    printf("Quantidade de numeros positivos: %d \n",pos);
    printf("Quantidade de numeros negativos: %d \n",neg);
    return 0;
}
```
>	QT06 (0,5 - pontos) - Crie um código onde sejam lidos 20 votos. Os votos serão armazenados em um vetor inteiro de elementos. Cada número do voto corresponde a um time de futebol que será mostrado em um menu com 4 opções sendo elas: Flamengo, Vasco, São Paulo, Corinthians. Totalize os votos ao final e mostre na tela.
```c
#include <stdio.h>
int main()
{
    int votos[20];
    int contador[4] = {0};
    int voto;

    printf("===== Menu de Times de Futebol =====\n");
    printf("1 - Flamengo\n");
    printf("2 - Vasco\n");
    printf("3 - Sao Paulo\n");
    printf("4 - Corinthians\n");


    for (int i = 0; i < 20; i++) {
        printf("Digite o voto %d: ", i + 1);
        scanf("%d", &voto);

        if (voto >= 1 && voto <= 4) {
            votos[i] = voto;
            contador[voto - 1]++; 
        } else {
            printf("Voto invalido! Digite um numero de 1 a 4.\n");
            i--;
        }
    }

   
    printf("\n===== Resultado dos Votos =====\n");
    printf("Flamengo: %d votos\n", contador[0]);
    printf("Vasco: %d votos\n", contador[1]);
    printf("Sao Paulo: %d votos\n", contador[2]);
    printf("Corinthians: %d votos\n", contador[3]);

    return 0;
}
```
>	QT07 (0,5 - pontos) - Refaça a mesma questão anterior utilizando o While e acrescentando uma condição de parada chamada "Totalizar" representada pelo número 99 no menu.
```c
#include <stdio.h>
int main()
{
    int votos[20]; 
    int contador[4] = {0};
    int voto = 0;
    int i = 0;

    printf("===== Menu de Times de Futebol =====\n");
    printf("1 - Flamengo\n");
    printf("2 - Vasco\n");
    printf("3 - Sao Paulo\n");
    printf("4 - Corinthians\n");
    printf("99 - Totalizar\n");

    
    while (voto != 99 && i < 20) {
        printf("Digite o voto %d (ou 99 para totalizar): ", i + 1);
        scanf("%d", &voto);

        
        if (voto >= 1 && voto <= 4) {
            votos[i] = voto;
            contador[voto - 1]++; 
            i++;
        } else if (voto != 99) {
            printf("Voto invalido! Digite um numero de 1 a 4 ou 99 para totalizar.\n");
        }
    }
```

>	QT08 (0,5 - pontos) - Crie um vetor de 20 posições para ler números correspondente ao estilo musical da turma (1 - Sertanejo, 2 - Internacional, 3 - Pop, 4 - Coreano, 5 - Forró, 6 - Funk, 7 - Gospel, 8 - Rock, 9 - Eletrônica, 10 - Classica). Totalize os votos por estilo e mostre ao final. Utilize o Do..while.
```c
#include <stdio.h>

int main()
{
    int votos[20]; 
    int contador[10] = {0}; 
    int voto;
    int i = 0;

    printf("===== Menu de Estilos Musicais =====\n");
    printf("1 - Sertanejo\n");
    printf("2 - Internacional\n");
    printf("3 - Pop\n");
    printf("4 - Coreano\n");
    printf("5 - Forro\n");
    printf("6 - Funk\n");
    printf("7 - Gospel\n");
    printf("8 - Rock\n");
    printf("9 - Eletronica\n");
    printf("10 - Classica\n");

    
    do {
        printf("Digite o voto %d: ", i + 1);
        scanf("%d", &voto);

        
        if (voto >= 1 && voto <= 10) {
            votos[i] = voto;
            contador[voto - 1]++; 
            i++;
        } else {
            printf("Voto inválido! Digite um número de 1 a 10.\n");
        }
    } while (i < 20);

    
    printf("\n===== Resultado dos Votos =====\n");
    printf("Sertanejo: %d votos\n", contador[0]);
    printf("Internacional: %d votos\n", contador[1]);
    printf("Pop: %d votos\n", contador[2]);
    printf("Coreano: %d votos\n", contador[3]);
    printf("Forró: %d votos\n", contador[4]);
    printf("Funk: %d votos\n", contador[5]);
    printf("Gospel: %d votos\n", contador[6]);
    printf("Rock: %d votos\n", contador[7]);
    printf("Eletrônica: %d votos\n", contador[8]);
    printf("Clássica: %d votos\n", contador[9]);

    return 0;
}
```

## Revisando estrutura básica

##### Aqui você irá ver de novo e praticar a estrutura básica.

> Usando o compilador C online repassado para a turma {https://www.onlinegdb.com/online_c_compiler} reescreva o código abaixo:
```C
#include<stdio.h>
int main(){
	int a;
	a = 20;
	printf("o valor de a é: %d",a);
}
```
Na estrutura básica temos:
>	#include<stdio.h>
>	int main()
> 	{} //chaves para o escopo do código.
### Atividade QT01 (0,1 pontos) - Reescreva o código criando mais duas variáveis inteiras e mostre-as na saída padrão.
```c
#include<stdio.h>
int main(){
	int a;
	a = 20;
	int b;
	b = 30;
	int c;
	c = 40;
	printf("o valor de a e: %d\n",a);
	printf("o valor de b e: %d\n",b);
	printf("o valor de c e: %d\n",c);
	return 0;
}
```
## Revisando estrutura condicional.

##### Aqui você irá ver de novo e praticar as condicionais de C.

> Usando o compilador C online repassado para a turma {https://www.onlinegdb.com/online_c_compiler} reescreva o código abaixo:
```C
#include <stdio.h>
int main(){
	int a;
	a = 20;
	if (a < 20){
		printf("O valor é menor que 20");
	}
}
```
Na estrutura acima temos:
>	O uso de uma estrutura condicional com o if
>	Seu escopo também inicia com chaves e termina com chaves.
### Atividade QT02 (0,1 pontos) - Reescreva o código criando mais uma estrutura if para uma frase se valores de a forem maiores que 20.
```c
#include <stdio.h>
int main(){
	int a;
	a = 20;
	if (a < 20){
		printf("O valor e menor que 20\n");
	}else{
	if (a > 20){	
		printf("O valor e maior que 20\n");			
	}
}
}
```
## Revisando estrutura condicional com if - else.

##### Aqui você irá ver de novo e praticar as condicionais de C com if - else.

> Usando o compilador C online repassado para a turma {https://www.onlinegdb.com/online_c_compiler} reescreva o código abaixo:
```C
#include <stdio.h>
int main(){
	int a;
	a = 20;
	if (a < 20){
		printf("O valor é menor que 20");
	}else{
		printf("esse é maior");
	}
}
```
Na estrutura acima temos:
>	O uso de uma estrutura condicional com o if e outra para o else
>	Seu escopo também inicia com chaves e termina com chaves também.
### Atividade QT03 (0,1 pontos) - Reescreva o código com estrutura if-else para uma frase se valores forem negativos ou positivos.
```c
#include <stdio.h>
int main(){
	int a;
	a = 0;
	if (a < 0){
		printf("O valor e negativo");
	}else{
		printf("esse e negativo\n");
	if (a > 0){
        printf("O valor e positivo");
    }else{  
    	printf("esse e positivo\n");
	}
	}
}
``
## Revisando Laços de Repetição: for.
##### Nessa atividade iremos revisar através de código escrito em C, como podemos trabalhar com esse tipo de variável que pode armazenar dados de um único tipo.

>  Usando novamente o "for" em C.
```C
int main(){
  
  //Vamos criar um laço de repetição ou loop usando o for logo abaixo.
  //Esse laço apenas escreverá 10 números começando do zero.
  //Observe que foi criado e inicializado uma variável "i" no próprio for.
  
  for(int i=0; i<10;i++){
    print("Esse é o valor de i: %d",i);
  }
}
```
>  Tarefa 01 - Altere o código e execute-o no falcon++ para que ele imprime todos os números entre 20 e 40. Após conseguir, basta copiar as linhas de código e colar aqui e realize o commit. #include<stdio.h>
int main(){
	for(int i=20; i<41;i++){
    printf("\nEsse é o valor de i: %d",i);
  }
}

## Revisando Laços de Repetição: While.
#### Aqui iremos agora focar no laço de repetição While.

>  Usando o While temos uma particularidade. Diferente do for, ele não é finalizado com um valor específico. Ele é finalizado com uma condição. Observe:

```C
int main(){
  // Foi criado uma variável inteira chamada "parada" e inicializada com 0 (zero).
  int parada = 0;
  //Agora vamos impor a condição de que essa variável não pode ser maior que 20. Iremos incrementar ela de 1 a cada interação.
  while (parada <=20){    
    printf("\n O valor da parada agora: %d",parada);
    //na linha abaixo incrementamos de 1 para a próxima interação.
    parada++;
  }  
}
```
>  Tarefa 2 - Altere o código anterior para mostrar a frase "esse é o valor escolhido" quando a variável "parada" for igual a 9. Copie e cole o código aqui e realize o commit.
```c
#include <stdio.h>
int main(){
	int parada = 0;
	while (parada <=20) {
		printf("\n O valor da parada agora: %d",parada);
		parada++;
		if (parada==9){
			printf("\n Esse eh o valor escolhido: %d",parada);
		}
	}
	return 0;
}
```
## Revisando Laços de Repetição: Do
#### Agora iremos finalizar nosso último laço de repetição. Iremos usar o do.
>  Usando o do..while temos algo bem legal: iremos colocar a condição de parada apenas no final do código. Observe:
```C
int main(){
  //Criamos a variável inteira incremento aqui para ser lida do teclado. O usuário irá digitar um valor inteiro.
  int incremento = 0;
  // Nas linhas abaixo iremos escrever todo o nosso cardápio vitual.
  do{
    printf("\n############# CARDAPIO VIRTUAL ##############");
    printf("\n[1]-Cafe");
    printf("\n[2]-Almoco");
    printf("\n[3]-Janta");
    printf("\n[99]-Sair do Menu");
    printf("\n#############################################");
    //Aqui mostramos uma frase para o usuário escolher um dos números do cardápio.
    printf("\nEscolha a um numero do cardapio: ");
    //Nesse scanf fazemos a leitura do valor que ele vai digitar.
    scanf("%d",&incremento);
  }while(incremento != 99);// com essa condição, o laço do..while só irá parar quando ele digitar 99.
}
```
>  Tarefa 3 - Altera o código para que quando seja escolhido 1, seja escrito "você escolheu cafe da manhã". Quando 2, seja escrito "você escolheu almoço". Quando 3, seja escrito "você escolheu agora jantar". Copie o código aqui e realize o commit.
>
```C
#include <stdio.h>
int main(){
  int incremento = 0;
  do{
    printf("\n############# CARDAPIO VIRTUAL ##############");
    printf("\n[1]-Cafe");
    printf("\n[2]-Almoco");
    printf("\n[3]-Janta");
    printf("\n[99]-Sair do Menu");
    printf("\n#############################################");
    printf("\nEscolha a um numero do cardapio: ");
    scanf("%d",&incremento);
    if(incremento==1)
    	printf("\n voce escolheu cafe!");
    if(incremento==2)
    	printf("\n voce escolheu almoco!");
    if(incremento==3)
    	printf("\n voce escolheu janta");
  }
  while(incremento != 99);
  if(incremento==99)
  	printf("Obrigado");
}
```
