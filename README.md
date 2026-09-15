# Consumo de Água

## Sobre o projeto

O projeto **Consumo de Água** foi desenvolvido em Python com o objetivo de criar um programa que analisa o consumo mensal de água de diferentes tipos de imóveis.
O programa pede para o usuário informar o tipo do imóvel, podendo ser **comercial, casa ou apartamento**. Depois, solicita o consumo mensal de água em metros cúbicos (m³).
A partir dessas informações, o programa verifica as condições definidas e apresenta uma mensagem de acordo com o perfil de consumo.

## Objetivo

O principal objetivo do programa é ajudar na conscientização sobre o consumo de água. A partir do resultado apresentado, o usuário consegue identificar se o consumo está econômico, moderado ou excessivo.
O programa também orienta o usuário a prestar atenção em possíveis vazamentos e a adotar medidas para economizar água.

## Como o programa funciona

Primeiro, o programa pergunta o tipo de imóvel. As opções utilizadas são:
- `comercial`
- `casa`
- `apartamento`
Depois, o usuário informa o consumo mensal de água em `m³`.
O programa utiliza as estruturas condicionais `if`, `elif` e `else` para analisar as informações e decidir qual mensagem deve ser apresentada.

### Classificações

**Imóvel comercial:**

Se o tipo de imóvel for comercial, o programa apresenta:

```text
Tarifa comercial aplicada – consulte o plano corporativo.
```

**Apartamento com consumo menor que 10 m³:**

O programa considera o consumo econômico e apresenta:

```text
Consumo econômico – excelente controle de água!
```

**Casa ou apartamento com consumo de até 25 m³:**

O programa considera o consumo moderado e apresenta:

```text
Consumo moderado – dentro do padrão residencial.
```

**Outros casos:**

Quando o consumo passa do limite residencial, o programa apresenta:

```text
Consumo excessivo – adote medidas de economia e verifique vazamentos.
```

## Tecnologias utilizadas
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)

![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)

![Visual Studio Code](https://img.shields.io/badge/VS%20Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white)

![Água](https://img.shields.io/badge/Água-2196F3?style=for-the-badge&logoColor=white)

![Meio Ambiente](https://img.shields.io/badge/Meio%20Ambiente-4CAF50?style=for-the-badge&logoColor=white)

## Como executar o programa

Para executar o programa, é necessário ter o Python instalado no computador.
Depois:
1. Abra o arquivo `app.py` no Visual Studio Code.
2. Execute o código.
3. Informe o tipo de imóvel.
4. Informe o consumo mensal de água em m³.
5. Confira a mensagem apresentada pelo programa.

## Exemplo de execução

```text
Digite o tipo de imóvel (comercial, casa ou apartamento): apartamento
Digite o consumo mensal de água em m³: 8

Consumo econômico – excelente controle de água!
