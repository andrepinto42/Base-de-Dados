---
title: Apontamentos
author: Pinto
---
# Apontamentos

Aula 04/03/2022


[link da aula anterior](https://github.com/dianazevedoferreira/UM_BD_2022)

# Definição de requisitos de software

* Revisão do caso pratico

* Técnicas de levantamento

## Questão 1

*De acordo com os métodos de levantamentos referidos quais são os mais uteis*

<span style="color: blue;">
    Professora fala depressa demais
</span>

* Entrevistas são as mais uteis, compreender os processos operacionais/workflows nos diferentes contextos hospitalares e especialiadades

## Questão 2

*Identifique as principais vistas de utilização por área/vertente de trabalho do sistema e/ou funções do utilizador especificas, para o levantamento de requisitos*

## Questão 3

Levantamento de requisitos necessários

| Descrição     | Area        | Font  |Analista|
|:-------------:|:-----------:|:-----:|:------:|
| Todos os pacientes do hospital devem ser registadods com o seu numero sequencial| Pacientes | Hospital |D.F
|Devem ser armazenados dados demográficos do paciente como nome,sexo,data de nascimento, morada, telefone, email, número de contribuinte, estado civil |Pacientes |Hospital|D.F
|A cada momento, deve ser possivel obter a lista de medicos de uma determinada especialidade| Especialidade      |Hospital|D.F
|O registo de consultas deve incluir um identificador único (nº episódio), o identificador do paciente e do médico, data e hora, custo da consulta |Consulta |Hospital |D.F

## Questao 4

*Organize os requisitos levantados anteriormente, de acordo com a categorização das vertentes de trabalho definida na aula teórica - Descrição, Manipulação e Controlo*

<span style="color: yellow;"
        font="verdana">
    Nota: Para cada vertente de trabalho deve ser criado um documento especifico que segue a estrutura do documento inicial de recolha de requisitos, mas agora os requisitos tem um numeração propria - RD, RM e RC
</span>

### Requisitos de Descriçao
* RD 01
* * Todos os pacientes do hospital devem ser registados com o seu numero sequencial - valor unico
* RD 02
* * Devem ser armazenados dados demográficos do paciente como o nome, sexo,data de nascimento, morada, telefone, email,etc..

### Requisitos de Manipulação
* RM 01
* * A cada momento, deve ser possivel obter a lista de medicos de uma determinada especilidade
  
### Requisitos de Controlo
* RC 01
* * Os profissionais de saúde não devem conseguir aceder à faturação
* RC 02 
* * Os anastesistas não podem marcar exames