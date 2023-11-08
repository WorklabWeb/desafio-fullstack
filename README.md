# Desafio Fullstack Worklab

Abaixo você encontrará todas as informações necessárias para iniciar o seu teste.

## Avisos antes de começar

- Crie um repositório no seu GitHub.
- Faça seus commits no seu repositório.
- Envie o link do seu repositório para o email **do recrutador responsável**.
- Você poderá consultar o Google, Stackoverflow ou algum projeto particular na sua máquina.
- Boa sorte! :)

*Corpo do Email com o link do repositório do desafio*

>Seu Nome
>
>Link do repositório
>
>Link do Linkedin

## Stack 

Algumas das tecnologias que trabalhamos aqui:

- PHP(usamos o framework laravel)
- NodeJs
- React
- VueJs
- MySql

No desafio poderá usar qualquer framework das tecnologias acima.
**Lembre-se não é obrigatório usar todas as tecnologias listadas.**

### Sobre o ambiente da aplicação:

- Escolha qualquer framework e linguagem **que esteja dentro da nossa stack** que se sinta mais **confortável** em trabalhar. Esse teste **não faz** nenhuma preferência de framework, portanto decida por aquele com o qual estará mais seguro em apresentar e conversar com a gente na entrevista ;)

- Você pode, inclusive, não optar por framework nenhum.

- Ainda assim, se optar por um framework tente evitar usar muito métodos mágicos ou atalhos já prontos. Sabemos que essas facilidades aumentam a produtividade no dia-a-dia mas aqui queremos ver o **seu** código e a sua forma de resolver problemas.

## Para o dia da entrevista técnica

Na data marcada pelo recrutador teremos sua aplicação rodando em uma máquina local para execução.
Você poderá explicar o que você pensou, como arquitetou e como pode evoluir o projeto.

## Objetivo: WorklabWeb simplificado

Você deverá desenvolver uma versão simplicada do nosso sistemas, assim já poderá se sentir parte da nossa equipe :) e vivenciará o nosso dia-a-dia.
Nesse desafio você deverá desenvolver um sistema que simule um fluxo básico do nosso sistema:

- Cadastrar paciente
- Cadastrar exames
- Vincular exames nesse paciente
- Gerar um relatorio básico 

Você poderá desenvolver um projeto único que contemple esse cenário ou pode dividir em duas partes, uma API e outra o client(caso queira dar desafio a mais :heart:).
Abaixo teremos as especificôes dos campos a serem usados, lembrando que você pode adicionar mais campos ou situações nesse fluxo.

### Paciente
- Número de atendimento
- Nome Completo
- Sexo
- Email
- Celular

### Exame
- Código
- Descrição
- Valor

### Regras

- Um paciente pode ter vários exames.
- Não deverá ser possível cadastrar exames com códigos duplicados.
- Ao cadastrar o paciente o campo Número de atendimento deverá ser gerado um número aleatório.
- Utilize o banco de dados sqlite e adicione um exemplo do banco usado, para fazermos alguns testes.

(Como exemplo de exames temos, HEMO - Hemograma e GLI - Glicose, você poderá usar outros caso conheça)

Lembrando que um paciente pode ter vários exames.
O Relatório precisará listar os dados do paciente e dos exames do mesmo.

### Exemplo em Json Paciente com exames

```json
{
    "numero_atendimento": "102030",
    "nome_completo" : "Jane Doe",
    "sexo" : "F",
    "email": "",
    "celular": "",
    "exames": [
        {
            "codigo": "HEMO",
            "descricao": "HEMOGRAMA",
            "valor": "10.20"
        }, {
            "codigo": "GLI",
            "descricao": "GLICOSE",
            "valor": "20"
        }
    ]
}
```

# Avaliação

Apresente sua solução utilizando o framework que você desejar, justificando a escolha.
Atente-se a cumprir a maioria dos requisitos, pois você pode cumpri-los parcialmente e durante a avaliação vamos bater um papo a respeito do que faltou.

## O que será avaliado e valorizamos :heart:
- Código limpo e organizado (nomenclatura, etc)
- Saber argumentar suas escolhas.
- Tratamento de erros
- Commits realizados(padronização e coerência nas mensagens são importantes para um bom histórico de altração).
- Domínio nas tecnologias escolhidas.
- Documentação(um README bem feito, explicando como rodar o desafio).
