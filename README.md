# Questionário: Você seria um herói ou vilão no universo de Dragon Ball Z?

Este é um projeto simples de questionário interativo que determina se você seria um herói ou vilão no universo de *Dragon Ball Z*. Com base nas suas respostas, o sistema irá analisar suas escolhas e gerar um resultado indicando o papel que você desempenharia nesse universo.

## Como funciona?

O questionário contém uma série de perguntas sobre o seu comportamento, escolha de poderes, reações a situações extremas e objetivos. Com base nas suas respostas, você será classificado como **herói** ou **vilão** no mundo de *Dragon Ball Z*. 

### Exemplos de Perguntas:
- Qual poder você escolheria para sua luta?
- Quem você salvaria em uma batalha mortal?
- Como você reagiria ao ser traído por um aliado?

## Estrutura do Projeto

O projeto utiliza uma estrutura simples de **JSON** para armazenar as perguntas, opções e resultados. O objetivo é permitir que você crie um questionário interativo e obtenha uma resposta baseada em escolhas feitas pelos usuários.

### Exemplo de Estrutura do Arquivo JSON:

```json
{
  "title": "Você seria um herói ou vilão no universo de Dragon Ball Z?",
  "questions": [
    {
      "id": 1,
      "question": "Qual poder você escolheria para sua luta?",
      "options": [
        {"id": 1, "name": "Kamehameha", "alias": "A"},
        {"id": 2, "name": "Transformar-se em Super Saiyajin", "alias": "B"},
        {"id": 3, "name": "Destruição em massa com o Dodonpa", "alias": "A"},
        {"id": 4, "name": "Curar feridas com o poder do Kaio-Ken", "alias": "B"},
        {"id": 5, "name": "Lançar raios de energia pelas mãos", "alias": "A"}
      ]
    },
    {
      "id": 2,
      "question": "Quem você salvaria em uma batalha mortal?",
      "options": [
        {"id": 1, "name": "Os mais fracos", "alias": "B"},
        {"id": 2, "name": "Somente a si mesmo", "alias": "A"},
        {"id": 3, "name": "Aqueles que mais me ajudam", "alias": "B"}
      ]
    },
    ...
  ],
  "results": {
    "A": "Você muito provavelmente seria um vilão no universo de Dragon Ball Z!",
    "B": "Você muito provavelmente seria um herói no universo de Dragon Ball Z!"
  }
}
