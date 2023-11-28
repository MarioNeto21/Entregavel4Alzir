# Entregavel4Alzir

# Projeto de Algoritmos JavaScript

Este repositório contém a implementação de vários algoritmos fundamentais em JavaScript, com foco na prática de Testes Unitários usando Jest.

## Pré-requisitos

Antes de começar, você precisará ter o Node.js e o npm instalados em seu ambiente de desenvolvimento. Isso permitirá que você instale as dependências e execute os testes.

- Node.js
- npm (normalmente instalado com o Node.js)

## Instalação

Primeiro, clone este repositório em sua máquina local usando o seguinte comando:

### Clonando o Repositório

Para obter uma cópia do projeto em sua máquina local, você precisará clonar o repositório. Isso pode ser feito usando o seguinte comando no terminal (ou prompt de comando, se estiver usando o Windows):

```bash
git clone https://exemplo.com/seuprojeto.git

Em seguida, navegue até o diretório do projeto clonado:

cd seuprojeto

Configurando o Projeto Node.js
Agora que você está dentro do diretório do projeto, inicialize seu projeto Node.js. Isso criará um arquivo package.json no seu projeto, que é usado para gerenciar as dependências do projeto:

npm init

Siga as instruções na tela para criar o package.json. Você pode simplesmente pressionar Enter para aceitar as configurações padrão se desejar.

Configurando Jest para Testes
Após a criação do arquivo package.json, abra-o e modifique a seção scripts para configurar o Jest como seu framework de teste:

"scripts": {
    "test": "jest"
}

Isso permite que você execute seus testes utilizando o comando npm test, que por sua vez chamará o Jest.

Salve as alterações no arquivo package.json.

Instalando Jest
Por fim, instale o Jest como uma dependência de desenvolvimento no seu projeto:

npm install --save-dev jest

Isso irá baixar e instalar o Jest, permitindo que você execute os testes unitários escritos para o seu projeto.

## Executando Testes

Este projeto inclui uma série de testes unitários desenvolvidos com Jest para validar a lógica dos algoritmos implementados. Abaixo estão os detalhes sobre cada arquivo de teste e as funções que eles testam:

### `contagem.test.js`
Testa a função que conta a quantidade de inteiros dentro de um intervalo específico em um array. Verifica se a função conta corretamente os números que estão dentro dos limites definidos e são inteiros.

### `numeroéprimo.test.js`
Verifica a função que determina se um número é primo. Este teste garante que a função identifique corretamente números primos e não primos.

### `fibonacci.test.js`
Testa a função que gera a sequência de Fibonacci. Verifica se a sequência é gerada corretamente para um determinado número de termos.

### `mdc.test.js`
Testa a função de cálculo do Máximo Divisor Comum (MDC). Este teste confirma se a função calcula corretamente o MDC para pares de números.

### `ordenacao.test.js`
Verifica o algoritmo de ordenação (por exemplo, Quick Sort). Testa se a função consegue ordenar corretamente uma variedade de arrays, incluindo arrays com números negativos e positivos.

### `somatorio.test.js`
Testa a função que calcula o somatório dos elementos de um array. Garante que a função some corretamente todos os elementos, independentemente de serem positivos ou negativos.

Para executar esses testes, use o seguinte comando no terminal:

```bash
npm test
