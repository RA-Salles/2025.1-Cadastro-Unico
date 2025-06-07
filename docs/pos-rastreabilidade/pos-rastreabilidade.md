# Pós-Rastreabilidade

<figure markdown>

<p style="text-align: center">Tabela 1 - Funções dos autores no artefato</p>

| Nome                 | Função      | 
|----------------------|-------------|
|[João Pedro Costa](https://github.com/johnaopedro)| Criação do documento; Desenvolvimento da pós-rastreabilidade; Modelagem e configuração das tabelas; Desenvolvimento da introdução e metodologia; Adição de todos os requisitos do projeto; Adição dos hyperlinks| 
|[Ryan Salles](https://github.com/RA-Salles)| Revisão geral|
|[Julia Gabriela](https://github.com/JuliaGabP)| Revisão geral|

**Autor(es):** [João Pedro Costa](https://github.com/johnaopedro)

<figcaption></figcaption>
</figure>

## Introdução

Este documento tem como objetivo apresentar a rastreabilidade entre os requisitos elicitados do Cadastro Único e os principais artefatos desenvolvidos ao longo do projeto, como diagramas, cenários, casos de uso, léxicos, protótipos e outros documentos presentes na pasta `docs/`. A rastreabilidade permite visualizar como cada requisito está relacionado aos artefatos de análise e projeto, facilitando a verificação, validação e manutenção do sistema.

## Metodologia

A metodologia utilizada para rastreabilidade foi baseada em modelos clássicos de pós-rastreabilidade, adaptando-os ao contexto do projeto. Os elos de rastreabilidade considerados são:

- **Satisfação:** artefatos que comprovam o atendimento ao requisito.
- **Recurso:** artefatos que fornecem informações ou contexto para o requisito.
- **Representação:** artefatos que ilustram ou detalham o requisito.
- **Alocado:** artefatos nos quais o requisito está explicitamente tratado.
- **Agregação:** agrupamento de requisitos ou artefatos relacionados.

A tabela a seguir apresenta um template utilizado para a pós-rastreabilidade dos requisitos:

<figure markdown>

<p style="text-align: center">Tabela 2 - Template Pós-Rastreabilidade</p>

| Artefato Analisado | Classificação do Artefato Analisado |
| :---------------: | :---------------------------------: |
| Tipos de Elo      | Artefatos Relacionados              |
| Satisfação        | -                                   |
| Recurso           | -                                   |
| Representação     | -                                   |
| Alocado           | -                                   |
| Agregação         | -                                   |

**Autor(es):** [João Pedro Costa](https://github.com/johnaopedro) Adaptado de [Meta-modelo de Toranzo (TORANZO, 2002)](http://wer.inf.puc-rio.br/WERpapers/artigos/artigos_WER02/toranzo.pdf)

<figcaption></figcaption>
</figure>

## Rastreabilidade

Nesta seção são apresentados os requisitos do Cadastro Único e os artefatos relacionados a cada um deles, conforme o modelo de pós-rastreabilidade adotado. As tabelas 3 a 60 contêm os requisitos e seus respectivos elos de rastreabilidade com os artefatos do projeto.

### RF01 - Cadastro de Famílias

<details markdown="1">
<summary>Permitir o cadastro de famílias com renda mensal de até meio salário mínimo por pessoa ou vinculadas a programas sociais.</summary>

<figure markdown>

<p style="text-align: center">Tabela 3 - RF01</p>
|RF01|Desenvolvimento|
| :---: | :---: |
| Tipos de Elo | Artefatos Relacionados |
| Satisfação | [Especificação Suplementar](../modelagem/especificacao_suplementar.md) |
| Recurso | [Cenários](../modelagem/cenarios.md), [Léxico](../modelagem/lexico.md) |
| Representação | [Casos de Uso](../modelagem/caso_de_uso.md) |
| Alocado | [História de Usuário](../modelagem/agil/historia_de_usuario.md), [Backlog](../modelagem/agil/backlog.md) |
| Agregação | [Requisitos Elicitados](../elicitacao/requisitos_elicitados.md) |

**Autor(es):** [João Pedro Costa](https://github.com/johnaopedro)

<figcaption></figcaption>
</figure>

</details>

### RF02 - Cadastro de Pessoas

<details markdown="1">
<summary>Registrar informações pessoais, como dados de identificação, documentação, frequência escolar, grau de instrução, entre outros.</summary>

<figure markdown>

<p style="text-align: center">Tabela 4 - RF02</p>

|RF02|Desenvolvimento|
| :---: | :---: |
| Tipos de Elo | Artefatos Relacionados |
| Satisfação | [Especificação Suplementar](../modelagem/especificacao_suplementar.md) |
| Recurso | [Cenários](../modelagem/cenarios.md), [Léxico](../modelagem/lexico.md) |
| Representação | [Casos de Uso](../modelagem/caso_de_uso.md) |
| Alocado | [História de Usuário](../modelagem/agil/historia_de_usuario.md), [Backlog](../modelagem/agil/backlog.md) |
| Agregação | [Requisitos Elicitados](../elicitacao/requisitos_elicitados.md) |

**Autor(es):** [João Pedro Costa](https://github.com/johnaopedro)

<figcaption></figcaption>
</figure>

</details>

### RF03 - Cadastro de Domicílios

<details markdown="1">
<summary>Registrar características do domicílio, como tipo de construção, abastecimento de água, iluminação, escoamento sanitário, entre outros.</summary>

<figure markdown>

<p style="text-align: center">Tabela 5 - RF03</p>

|RF03|Desenvolvimento|
| :---: | :---: |
| Tipos de Elo | Artefatos Relacionados |
| Satisfação | [Especificação Suplementar](../modelagem/especificacao_suplementar.md) |
| Recurso | [Cenários](../modelagem/cenarios.md), [Léxico](../modelagem/lexico.md) |
| Representação | [Casos de Uso](../modelagem/caso_de_uso.md) |
| Alocado | [História de Usuário](../modelagem/agil/historia_de_usuario.md), [Backlog](../modelagem/agil/backlog.md) |
| Agregação | [Requisitos Elicitados](../elicitacao/requisitos_elicitados.md) |

**Autor(es):** [João Pedro Costa](https://github.com/johnaopedro)

<figcaption></figcaption>
</figure>

</details>

### RF04 - Cadastro de Agricultores Familiares

<details markdown="1">
<summary>Registrar informações sobre posse de terra, atividade primária, contratação de mão de obra e composição da renda.</summary>

<figure markdown>

<p style="text-align: center">Tabela 6 - RF04</p>

|RF04|Desenvolvimento|
| :---: | :---: |
| Tipos de Elo | Artefatos Relacionados |
| Satisfação | [Especificação Suplementar](../modelagem/especificacao_suplementar.md) |
| Recurso | [Cenários](../modelagem/cenarios.md), [Léxico](../modelagem/lexico.md) |
| Representação | [Casos de Uso](../modelagem/caso_de_uso.md) |
| Alocado | [História de Usuário](../modelagem/agil/historia_de_usuario.md), [Backlog](../modelagem/agil/backlog.md) |
| Agregação | [Requisitos Elicitados](../elicitacao/requisitos_elicitados.md) |

**Autor(es):** [João Pedro Costa](https://github.com/johnaopedro)

<figcaption></figcaption>
</figure>

</details>

### RF05 - Atualização de Dados de família

<details markdown="1">
<summary>Permitir a atualização dos dados das famílias cadastradas.</summary>

<figure markdown>

<p style="text-align: center">Tabela 7 - RF05</p>

|RF05|Desenvolvimento|
| :---: | :---: |
| Tipos de Elo | Artefatos Relacionados |
| Satisfação | [Especificação Suplementar](../modelagem/especificacao_suplementar.md) |
| Recurso | [Cenários](../modelagem/cenarios.md), [Léxico](../modelagem/lexico.md) |
| Representação | [Casos de Uso](../modelagem/caso_de_uso.md) |
| Alocado | [História de Usuário](../modelagem/agil/historia_de_usuario.md), [Backlog](../modelagem/agil/backlog.md) |
| Agregação | [Requisitos Elicitados](../elicitacao/requisitos_elicitados.md) |

**Autor(es):** [João Pedro Costa](https://github.com/johnaopedro)

<figcaption></figcaption>
</figure>

</details>

### RF06 - Processamento de Dados

<details markdown="1">
<summary>Transmitir os dados coletados para a CAIXA, processá-los e atribuir um Número de Identificação Social (NIS) único para cada pessoa cadastrada.</summary>

<figure markdown>

<p style="text-align: center">Tabela 8 - RF06</p>

|RF06|Desenvolvimento|
| :---: | :---: |
| Tipos de Elo | Artefatos Relacionados |
| Satisfação | [Especificação Suplementar](../modelagem/especificacao_suplementar.md) |
| Recurso | [Cenários](../modelagem/cenarios.md), [Léxico](../modelagem/lexico.md) |
| Representação | [Casos de Uso](../modelagem/caso_de_uso.md) |
| Alocado | [História de Usuário](../modelagem/agil/historia_de_usuario.md), [Backlog](../modelagem/agil/backlog.md) |
| Agregação | [Requisitos Elicitados](../elicitacao/requisitos_elicitados.md) |

**Autor(es):** [João Pedro Costa](https://github.com/johnaopedro)

<figcaption></figcaption>
</figure>

</details>

### RF07 - Correção de Inconsistências

<details markdown="1">
<summary>Permitir a correção de inconsistências detectadas no processamento e retransmissão dos dados.</summary>

<figure markdown>

<p style="text-align: center">Tabela 9 - RF07</p>

|RF07|Desenvolvimento|
| :---: | :---: |
| Tipos de Elo | Artefatos Relacionados |
| Satisfação | [Especificação Suplementar](../modelagem/especificacao_suplementar.md) |
| Recurso | [Cenários](../modelagem/cenarios.md), [Léxico](../modelagem/lexico.md) |
| Representação | [Casos de Uso](../modelagem/caso_de_uso.md) |
| Alocado | [História de Usuário](../modelagem/agil/historia_de_usuario.md), [Backlog](../modelagem/agil/backlog.md) |
| Agregação | [Requisitos Elicitados](../elicitacao/requisitos_elicitados.md) |

**Autor(es):** [João Pedro Costa](https://github.com/johnaopedro)

<figcaption></figcaption>
</figure>

</details>

### RF08 - Consulta de Dados

<details markdown="1">
<summary>Permitir a consulta de dados cadastrais, situação de benefícios e ações de gestão de benefícios por meio do NIS.</summary>

<figure markdown>

<p style="text-align: center">Tabela 10 - RF08</p>

|RF08|Desenvolvimento|
| :---: | :---: |
| Tipos de Elo | Artefatos Relacionados |
| Satisfação | [Especificação Suplementar](../modelagem/especificacao_suplementar.md) |
| Recurso | [Cenários](../modelagem/cenarios.md), [Léxico](../modelagem/lexico.md) |
| Representação | [Casos de Uso](../modelagem/caso_de_uso.md) |
| Alocado | [História de Usuário](../modelagem/agil/historia_de_usuario.md), [Backlog](../modelagem/agil/backlog.md) |
| Agregação | [Requisitos Elicitados](../elicitacao/requisitos_elicitados.md) |

**Autor(es):** [João Pedro Costa](https://github.com/johnaopedro)

<figcaption></figcaption>
</figure>

</details>

### RF09 - Relatórios e Divulgação

<details markdown="1">
<summary>Gerar relatórios anuais com o perfil das famílias beneficiárias e disponibilizar dados para instituições de pesquisa e órgãos de governo mediante acordos e termos de responsabilidade.</summary>

<figure markdown>

<p style="text-align: center">Tabela 11 - RF09</p>

|RF09|Desenvolvimento|
| :---: | :---: |
| Tipos de Elo | Artefatos Relacionados |
| Satisfação | [Especificação Suplementar](../modelagem/especificacao_suplementar.md) |
| Recurso | [Cenários](../modelagem/cenarios.md), [Léxico](../modelagem/lexico.md) |
| Representação | [Casos de Uso](../modelagem/caso_de_uso.md) |
| Alocado | [História de Usuário](../modelagem/agil/historia_de_usuario.md), [Backlog](../modelagem/agil/backlog.md) |
| Agregação | [Requisitos Elicitados](../elicitacao/requisitos_elicitados.md) |

**Autor(es):** [João Pedro Costa](https://github.com/johnaopedro)

<figcaption></figcaption>
</figure>

</details>

### RF10 - Formulários de Coleta

<details markdown="1">
<summary>Implementar formulários principais e suplementares para coleta de dados, abrangendo características de domicílios, famílias, pessoas, vinculação a programas e pessoas em situação de rua.</summary>

<figure markdown>

<p style="text-align: center">Tabela 12 - RF10</p>

|RF10|Desenvolvimento|
| :---: | :---: |
| Tipos de Elo | Artefatos Relacionados |
| Satisfação | [Especificação Suplementar](../modelagem/especificacao_suplementar.md) |
| Recurso | [Cenários](../modelagem/cenarios.md), [Léxico](../modelagem/lexico.md) |
| Representação | [Casos de Uso](../modelagem/caso_de_uso.md) |
| Alocado | [História de Usuário](../modelagem/agil/historia_de_usuario.md), [Backlog](../modelagem/agil/backlog.md) |
| Agregação | [Requisitos Elicitados](../elicitacao/requisitos_elicitados.md) |

**Autor(es):** [João Pedro Costa](https://github.com/johnaopedro)

<figcaption></figcaption>
</figure>

</details>

### RF11 - Cadastro MEI

<details markdown="1">
<summary>Permitir que, ao cadastrar um usuário, o cadastro possa especificar que o usuário é um MEI.</summary>

<figure markdown>

<p style="text-align: center">Tabela 13 - RF11</p>

|RF11|Desenvolvimento|
| :---: | :---: |
| Tipos de Elo | Artefatos Relacionados |
| Satisfação | [Especificação Suplementar](../modelagem/especificacao_suplementar.md) |
| Recurso | [Cenários](../modelagem/cenarios.md), [Léxico](../modelagem/lexico.md) |
| Representação | [Casos de Uso](../modelagem/caso_de_uso.md) |
| Alocado | [História de Usuário](../modelagem/agil/historia_de_usuario.md), [Backlog](../modelagem/agil/backlog.md) |
| Agregação | [Requisitos Elicitados](../elicitacao/requisitos_elicitados.md) |

**Autor(es):** [João Pedro Costa](https://github.com/johnaopedro)

<figcaption></figcaption>
</figure>

</details>

### RF12 - Informações MEI

<details markdown="1">
<summary>Conter seção de informações sobre microempreendedorismo individual.</summary>

<figure markdown>

<p style="text-align: center">Tabela 14 - RF12</p>

|RF12|Desenvolvimento|
| :---: | :---: |
| Tipos de Elo | Artefatos Relacionados |
| Satisfação | [Especificação Suplementar](../modelagem/especificacao_suplementar.md) |
| Recurso | [Cenários](../modelagem/cenarios.md), [Léxico](../modelagem/lexico.md) |
| Representação | [Casos de Uso](../modelagem/caso_de_uso.md) |
| Alocado | [História de Usuário](../modelagem/agil/historia_de_usuario.md), [Backlog](../modelagem/agil/backlog.md) |
| Agregação | [Requisitos Elicitados](../elicitacao/requisitos_elicitados.md) |

**Autor(es):** [João Pedro Costa](https://github.com/johnaopedro)

<figcaption></figcaption>
</figure>

</details>

### RF13 - Personalização MEI

<details markdown="1">
<summary>Personalização de conteúdos da seção MEI de acordo com o setor de atuação do usuário registrado e/ou região do território brasileiro onde atua.</summary>

<figure markdown>

<p style="text-align: center">Tabela 15 - RF13</p>

|RF13|Desenvolvimento|
| :---: | :---: |
| Tipos de Elo | Artefatos Relacionados |
| Satisfação | [Especificação Suplementar](../modelagem/especificacao_suplementar.md) |
| Recurso | [Cenários](../modelagem/cenarios.md), [Léxico](../modelagem/lexico.md) |
| Representação | [Casos de Uso](../modelagem/caso_de_uso.md) |
| Alocado | [História de Usuário](../modelagem/agil/historia_de_usuario.md), [Backlog](../modelagem/agil/backlog.md) |
| Agregação | [Requisitos Elicitados](../elicitacao/requisitos_elicitados.md) |

**Autor(es):** [João Pedro Costa](https://github.com/johnaopedro)

<figcaption></figcaption>
</figure>

</details>

### RF14 - Consultar dados cadastrais

<details markdown="1">
<summary>Permite ao usuário visualizar seus dados no Cadastro Único.</summary>

<figure markdown>

<p style="text-align: center">Tabela 16 - RF14</p>

|RF14|Desenvolvimento|
| :---: | :---: |
| Tipos de Elo | Artefatos Relacionados |
| Satisfação | [Especificação Suplementar](../modelagem/especificacao_suplementar.md) |
| Recurso | [Cenários](../modelagem/cenarios.md), [Léxico](../modelagem/lexico.md) |
| Representação | [Casos de Uso](../modelagem/caso_de_uso.md) |
| Alocado | [História de Usuário](../modelagem/agil/historia_de_usuario.md), [Backlog](../modelagem/agil/backlog.md) |
| Agregação | [Requisitos Elicitados](../elicitacao/requisitos_elicitados.md) |

**Autor(es):** [João Pedro Costa](https://github.com/johnaopedro)

<figcaption></figcaption>
</figure>

</details>

### RF15 - Pré-cadastrar família

<details markdown="1">
<summary>Possibilita iniciar um pré-cadastro para uma nova unidade familiar.</summary>

<figure markdown>

<p style="text-align: center">Tabela 17 - RF15</p>

|RF15|Desenvolvimento|
| :---: | :---: |
| Tipos de Elo | Artefatos Relacionados |
| Satisfação | [Especificação Suplementar](../modelagem/especificacao_suplementar.md) |
| Recurso | [Cenários](../modelagem/cenarios.md), [Léxico](../modelagem/lexico.md) |
| Representação | [Casos de Uso](../modelagem/caso_de_uso.md) |
| Alocado | [História de Usuário](../modelagem/agil/historia_de_usuario.md), [Backlog](../modelagem/agil/backlog.md) |
| Agregação | [Requisitos Elicitados](../elicitacao/requisitos_elicitados.md) |

**Autor(es):** [João Pedro Costa](https://github.com/johnaopedro)

<figcaption></figcaption>
</figure>

</details>

### RF16 - Localizar postos de atendimento

<details markdown="1">
<summary>Mostra os CRAS mais próximos com base na localização do usuário.</summary>

<figure markdown>

<p style="text-align: center">Tabela 18 - RF16</p>

|RF16|Desenvolvimento|
| :---: | :---: |
| Tipos de Elo | Artefatos Relacionados |
| Satisfação | [Especificação Suplementar](../modelagem/especificacao_suplementar.md) |
| Recurso | [Cenários](../modelagem/cenarios.md), [Léxico](../modelagem/lexico.md) |
| Representação | [Casos de Uso](../modelagem/caso_de_uso.md) |
| Alocado | [História de Usuário](../modelagem/agil/historia_de_usuario.md), [Backlog](../modelagem/agil/backlog.md) |
| Agregação | [Requisitos Elicitados](../elicitacao/requisitos_elicitados.md) |

**Autor(es):** [João Pedro Costa](https://github.com/johnaopedro)

<figcaption></figcaption>
</figure>

</details>

### RF17 - Enviar notificações

<details markdown="1">
<summary>Envia notificações sobre pendências ou atualizações necessárias ao usuário.</summary>

<figure markdown>

<p style="text-align: center">Tabela 19 - RF17</p>

|RF17|Desenvolvimento|
| :---: | :---: |
| Tipos de Elo | Artefatos Relacionados |
| Satisfação | [Especificação Suplementar](../modelagem/especificacao_suplementar.md) |
| Recurso | [Cenários](../modelagem/cenarios.md), [Léxico](../modelagem/lexico.md) |
| Representação | [Casos de Uso](../modelagem/caso_de_uso.md) |
| Alocado | [História de Usuário](../modelagem/agil/historia_de_usuario.md), [Backlog](../modelagem/agil/backlog.md) |
| Agregação | [Requisitos Elicitados](../elicitacao/requisitos_elicitados.md) |

**Autor(es):** [João Pedro Costa](https://github.com/johnaopedro)

<figcaption></figcaption>
</figure>

</details>

### RF18 - Integrar com o CNIS

<details markdown="1">
<summary>Traz dados de vínculos e contribuições automaticamente do CNIS.</summary>

<figure markdown>

<p style="text-align: center">Tabela 20 - RF18</p>

|RF18|Desenvolvimento|
| :---: | :---: |
| Tipos de Elo | Artefatos Relacionados |
| Satisfação | [Especificação Suplementar](../modelagem/especificacao_suplementar.md) |
| Recurso | [Cenários](../modelagem/cenarios.md), [Léxico](../modelagem/lexico.md) |
| Representação | [Casos de Uso](../modelagem/caso_de_uso.md) |
| Alocado | [História de Usuário](../modelagem/agil/historia_de_usuario.md), [Backlog](../modelagem/agil/backlog.md) |
| Agregação | [Requisitos Elicitados](../elicitacao/requisitos_elicitados.md) |

**Autor(es):** [João Pedro Costa](https://github.com/johnaopedro)

<figcaption></figcaption>
</figure>

</details>

### RF19 - Cadastro de Usuário

<details markdown="1">
<summary>O sistema deve permitir o cadastro de novos usuários, coletando informações pessoais como nome, CPF, endereço, e outros dados necessários.</summary>

<figure markdown>

<p style="text-align: center">Tabela 21 - RF19</p>

|RF19|Desenvolvimento|
| :---: | :---: |
| Tipos de Elo | Artefatos Relacionados |
| Satisfação | [Especificação Suplementar](../modelagem/especificacao_suplementar.md) |
| Recurso | [Cenários](../modelagem/cenarios.md), [Léxico](../modelagem/lexico.md) |
| Representação | [Casos de Uso](../modelagem/caso_de_uso.md) |
| Alocado | [História de Usuário](../modelagem/agil/historia_de_usuario.md), [Backlog](../modelagem/agil/backlog.md) |
| Agregação | [Requisitos Elicitados](../elicitacao/requisitos_elicitados.md) |

**Autor(es):** [João Pedro Costa](https://github.com/johnaopedro)

<figcaption></figcaption>
</figure>

</details>

### RF20 - Atualização de Dados do Usuário

<details markdown="1">
<summary>O sistema deve possibilitar ao usuário atualizar seus dados cadastrais a qualquer momento.</summary>

<figure markdown>

<p style="text-align: center">Tabela 22 - RF20</p>

|RF20|Desenvolvimento|
| :---: | :---: |
| Tipos de Elo | Artefatos Relacionados |
| Satisfação | [Especificação Suplementar](../modelagem/especificacao_suplementar.md) |
| Recurso | [Cenários](../modelagem/cenarios.md), [Léxico](../modelagem/lexico.md) |
| Representação | [Casos de Uso](../modelagem/caso_de_uso.md) |
| Alocado | [História de Usuário](../modelagem/agil/historia_de_usuario.md), [Backlog](../modelagem/agil/backlog.md) |
| Agregação | [Requisitos Elicitados](../elicitacao/requisitos_elicitados.md) |

**Autor(es):** [João Pedro Costa](https://github.com/johnaopedro)

<figcaption></figcaption>
</figure>

</details>

### RF21 - Consultar Situação Cadastral

<details markdown="1">
<summary>O sistema deve permitir que o usuário consulte o status de seu cadastro e a situação atual do benefício.</summary>

<figure markdown>

<p style="text-align: center">Tabela 23 - RF21</p>

|RF21|Desenvolvimento|
| :---: | :---: |
| Tipos de Elo | Artefatos Relacionados |
| Satisfação | [Especificação Suplementar](../modelagem/especificacao_suplementar.md) |
| Recurso | [Cenários](../modelagem/cenarios.md), [Léxico](../modelagem/lexico.md) |
| Representação | [Casos de Uso](../modelagem/caso_de_uso.md) |
| Alocado | [História de Usuário](../modelagem/agil/historia_de_usuario.md), [Backlog](../modelagem/agil/backlog.md) |
| Agregação | [Requisitos Elicitados](../elicitacao/requisitos_elicitados.md) |

**Autor(es):** [João Pedro Costa](https://github.com/johnaopedro)

<figcaption></figcaption>
</figure>

</details>

### RF22 - Emissão de Comprovante de Cadastro

<details markdown="1">
<summary>O sistema deve possibilitar que o usuário gere e imprima um comprovante de cadastro atualizado.</summary>

<figure markdown>

<p style="text-align: center">Tabela 24 - RF22</p>

|RF22|Desenvolvimento|
| :---: | :---: |
| Tipos de Elo | Artefatos Relacionados |
| Satisfação | [Especificação Suplementar](../modelagem/especificacao_suplementar.md) |
| Recurso | [Cenários](../modelagem/cenarios.md), [Léxico](../modelagem/lexico.md) |
| Representação | [Casos de Uso](../modelagem/caso_de_uso.md) |
| Alocado | [História de Usuário](../modelagem/agil/historia_de_usuario.md), [Backlog](../modelagem/agil/backlog.md) |
| Agregação | [Requisitos Elicitados](../elicitacao/requisitos_elicitados.md) |

**Autor(es):** [João Pedro Costa](https://github.com/johnaopedro)

<figcaption></figcaption>
</figure>

</details>

### RF23 - Filtragem de Benefícios

<details markdown="1">
<summary>O sistema deve permitir ao usuário visualizar os benefícios aos quais ele pode ter direito com base nos dados cadastrados.</summary>

<figure markdown>

<p style="text-align: center">Tabela 25 - RF23</p>

|RF23|Desenvolvimento|
| :---: | :---: |
| Tipos de Elo | Artefatos Relacionados |
| Satisfação | [Especificação Suplementar](../modelagem/especificacao_suplementar.md) |
| Recurso | [Cenários](../modelagem/cenarios.md), [Léxico](../modelagem/lexico.md) |
| Representação | [Casos de Uso](../modelagem/caso_de_uso.md) |
| Alocado | [História de Usuário](../modelagem/agil/historia_de_usuario.md), [Backlog](../modelagem/agil/backlog.md) |
| Agregação | [Requisitos Elicitados](../elicitacao/requisitos_elicitados.md) |

**Autor(es):** [João Pedro Costa](https://github.com/johnaopedro)

<figcaption></figcaption>
</figure>

</details>

### RF24 - Consulta de Benefícios

<details markdown="1">
<summary>Consulta de status de benefícios.</summary>

<figure markdown>

<p style="text-align: center">Tabela 26 - RF24</p>

|RF24|Desenvolvimento|
| :---: | :---: |
| Tipos de Elo | Artefatos Relacionados |
| Satisfação | [Especificação Suplementar](../modelagem/especificacao_suplementar.md) |
| Recurso | [Cenários](../modelagem/cenarios.md), [Léxico](../modelagem/lexico.md) |
| Representação | [Casos de Uso](../modelagem/caso_de_uso.md) |
| Alocado | [História de Usuário](../modelagem/agil/historia_de_usuario.md), [Backlog](../modelagem/agil/backlog.md) |
| Agregação | [Requisitos Elicitados](../elicitacao/requisitos_elicitados.md) |

**Autor(es):** [João Pedro Costa](https://github.com/johnaopedro)

<figcaption></figcaption>
</figure>

</details>

### RF25 - Informações Cadastrais

<details markdown="1">
<summary>Visualização de informações cadastrais.</summary>

<figure markdown>

<p style="text-align: center">Tabela 27 - RF25</p>

|RF25|Desenvolvimento|
| :---: | :---: |
| Tipos de Elo | Artefatos Relacionados |
| Satisfação | [Especificação Suplementar](../modelagem/especificacao_suplementar.md) |
| Recurso | [Cenários](../modelagem/cenarios.md), [Léxico](../modelagem/lexico.md) |
| Representação | [Casos de Uso](../modelagem/caso_de_uso.md) |
| Alocado | [História de Usuário](../modelagem/agil/historia_de_usuario.md), [Backlog](../modelagem/agil/backlog.md) |
| Agregação | [Requisitos Elicitados](../elicitacao/requisitos_elicitados.md) |

**Autor(es):** [João Pedro Costa](https://github.com/johnaopedro)

<figcaption></figcaption>
</figure>

</details>

### RF26 - Chatbot de atendimento automatizado

<details markdown="1">
<summary>Implementa um chatbot para atendimento automatizado ao usuário.</summary>

<figure markdown>

<p style="text-align: center">Tabela 28 - RF26</p>

|RF26|Desenvolvimento|
| :---: | :---: |
| Tipos de Elo | Artefatos Relacionados |
| Satisfação | [Especificação Suplementar](../modelagem/especificacao_suplementar.md) |
| Recurso | [Cenários](../modelagem/cenarios.md), [Léxico](../modelagem/lexico.md) |
| Representação | [Casos de Uso](../modelagem/caso_de_uso.md) |
| Alocado | [História de Usuário](../modelagem/agil/historia_de_usuario.md), [Backlog](../modelagem/agil/backlog.md) |
| Agregação | [Requisitos Elicitados](../elicitacao/requisitos_elicitados.md) |

**Autor(es):** [João Pedro Costa](https://github.com/johnaopedro)

<figcaption></figcaption>
</figure>

</details>

### RF27 - Notificação de pendências ou atualizações

<details markdown="1">
<summary>Envia notificações sobre pendências ou atualizações necessárias ao usuário.</summary>

<figure markdown>

<p style="text-align: center">Tabela 29 - RF27</p>

|RF27|Desenvolvimento|
| :---: | :---: |
| Tipos de Elo | Artefatos Relacionados |
| Satisfação | [Especificação Suplementar](../modelagem/especificacao_suplementar.md) |
| Recurso | [Cenários](../modelagem/cenarios.md), [Léxico](../modelagem/lexico.md) |
| Representação | [Casos de Uso](../modelagem/caso_de_uso.md) |
| Alocado | [História de Usuário](../modelagem/agil/historia_de_usuario.md), [Backlog](../modelagem/agil/backlog.md) |
| Agregação | [Requisitos Elicitados](../elicitacao/requisitos_elicitados.md) |

**Autor(es):** [João Pedro Costa](https://github.com/johnaopedro)

<figcaption></figcaption>
</figure>

</details>

### RF28 - Simulador de benefícios sociais

<details markdown="1">
<summary>Permite ao usuário simular quais benefícios sociais poderia receber.</summary>

<figure markdown>

<p style="text-align: center">Tabela 30 - RF28</p>

|RF28|Desenvolvimento|
| :---: | :---: |
| Tipos de Elo | Artefatos Relacionados |
| Satisfação | [Especificação Suplementar](../modelagem/especificacao_suplementar.md) |
| Recurso | [Cenários](../modelagem/cenarios.md), [Léxico](../modelagem/lexico.md) |
| Representação | [Casos de Uso](../modelagem/caso_de_uso.md) |
| Alocado | [História de Usuário](../modelagem/agil/historia_de_usuario.md), [Backlog](../modelagem/agil/backlog.md) |
| Agregação | [Requisitos Elicitados](../elicitacao/requisitos_elicitados.md) |

**Autor(es):** [João Pedro Costa](https://github.com/johnaopedro)

<figcaption></figcaption>
</figure>

</details>

### RF29 - Upload de documentos

<details markdown="1">
<summary>Permite ao usuário fazer upload de documentos para o sistema.</summary>

<figure markdown>

<p style="text-align: center">Tabela 31 - RF29</p>

|RF29|Desenvolvimento|
| :---: | :---: |
| Tipos de Elo | Artefatos Relacionados |
| Satisfação | [Especificação Suplementar](../modelagem/especificacao_suplementar.md) |
| Recurso | [Cenários](../modelagem/cenarios.md), [Léxico](../modelagem/lexico.md) |
| Representação | [Casos de Uso](../modelagem/caso_de_uso.md) |
| Alocado | [História de Usuário](../modelagem/agil/historia_de_usuario.md), [Backlog](../modelagem/agil/backlog.md) |
| Agregação | [Requisitos Elicitados](../elicitacao/requisitos_elicitados.md) |

**Autor(es):** [João Pedro Costa](https://github.com/johnaopedro)

<figcaption></figcaption>
</figure>

</details>

### RF30 - Agendamento de atendimento no CRAS

<details markdown="1">
<summary>Agendamento de atendimentos no CRAS pelo app.</summary>

<figure markdown>

<p style="text-align: center">Tabela 32 - RF30</p>

|RF30|Desenvolvimento|
| :---: | :---: |
| Tipos de Elo | Artefatos Relacionados |
| Satisfação | [Especificação Suplementar](../modelagem/especificacao_suplementar.md) |
| Recurso | [Cenários](../modelagem/cenarios.md), [Léxico](../modelagem/lexico.md) |
| Representação | [Casos de Uso](../modelagem/caso_de_uso.md) |
| Alocado | [História de Usuário](../modelagem/agil/historia_de_usuario.md), [Backlog](../modelagem/agil/backlog.md) |
| Agregação | [Requisitos Elicitados](../elicitacao/requisitos_elicitados.md) |

**Autor(es):** [João Pedro Costa](https://github.com/johnaopedro)

<figcaption></figcaption>
</figure>

</details>

### RF31 - Notificações Personalizadas

<details markdown="1">
<summary>Notificações personalizadas (pendências, atualizações, confirmações).</summary>

<figure markdown>

<p style="text-align: center">Tabela 33 - RF31</p>

|RF31|Desenvolvimento|
| :---: | :---: |
| Tipos de Elo | Artefatos Relacionados |
| Satisfação | [Especificação Suplementar](../modelagem/especificacao_suplementar.md) |
| Recurso | [Cenários](../modelagem/cenarios.md), [Léxico](../modelagem/lexico.md) |
| Representação | [Casos de Uso](../modelagem/caso_de_uso.md) |
| Alocado | [História de Usuário](../modelagem/agil/historia_de_usuario.md), [Backlog](../modelagem/agil/backlog.md) |
| Agregação | [Requisitos Elicitados](../elicitacao/requisitos_elicitados.md) |

**Autor(es):** [João Pedro Costa](https://github.com/johnaopedro)

<figcaption></figcaption>
</figure>

</details>

### RF32 - Atualização Cadastral

<details markdown="1">
<summary>Passo a passo claro para atualização cadastral.</summary>

<figure markdown>

<p style="text-align: center">Tabela 34 - RF32</p>

|RF32|Desenvolvimento|
| :---: | :---: |
| Tipos de Elo | Artefatos Relacionados |
| Satisfação | [Especificação Suplementar](../modelagem/especificacao_suplementar.md) |
| Recurso | [Cenários](../modelagem/cenarios.md), [Léxico](../modelagem/lexico.md) |
| Representação | [Casos de Uso](../modelagem/caso_de_uso.md) |
| Alocado | [História de Usuário](../modelagem/agil/historia_de_usuario.md), [Backlog](../modelagem/agil/backlog.md) |
| Agregação | [Requisitos Elicitados](../elicitacao/requisitos_elicitados.md) |

**Autor(es):** [João Pedro Costa](https://github.com/johnaopedro)

<figcaption></figcaption>
</figure>

</details>

### RF33 - Simulador de Benefícios

<details markdown="1">
<summary>Simulador de elegibilidade para benefícios.</summary>

<figure markdown>

<p style="text-align: center">Tabela 35 - RF33</p>

|RF33|Desenvolvimento|
| :---: | :---: |
| Tipos de Elo | Artefatos Relacionados |
| Satisfação | [Especificação Suplementar](../modelagem/especificacao_suplementar.md) |
| Recurso | [Cenários](../modelagem/cenarios.md), [Léxico](../modelagem/lexico.md) |
| Representação | [Casos de Uso](../modelagem/caso_de_uso.md) |
| Alocado | [História de Usuário](../modelagem/agil/historia_de_usuario.md), [Backlog](../modelagem/agil/backlog.md) |
| Agregação | [Requisitos Elicitados](../elicitacao/requisitos_elicitados.md) |

**Autor(es):** [João Pedro Costa](https://github.com/johnaopedro)

<figcaption></figcaption>
</figure>

</details>

### RF34 - Chat de Atendimento

<details markdown="1">
<summary>Chat de atendimento ao usuário.</summary>

<figure markdown>

<p style="text-align: center">Tabela 36 - RF34</p>

|RF34|Desenvolvimento|
| :---: | :---: |
| Tipos de Elo | Artefatos Relacionados |
| Satisfação | [Especificação Suplementar](../modelagem/especificacao_suplementar.md) |
| Recurso | [Cenários](../modelagem/cenarios.md), [Léxico](../modelagem/lexico.md) |
| Representação | [Casos de Uso](../modelagem/caso_de_uso.md) |
| Alocado | [História de Usuário](../modelagem/agil/historia_de_usuario.md), [Backlog](../modelagem/agil/backlog.md) |
| Agregação | [Requisitos Elicitados](../elicitacao/requisitos_elicitados.md) |

**Autor(es):** [João Pedro Costa](https://github.com/johnaopedro)

<figcaption></figcaption>
</figure>

</details>

### RF35 - Tutoriais Interativos

<details markdown="1">
<summary>Tutoriais interativos para guiar tarefas críticas.</summary>

<figure markdown>

<p style="text-align: center">Tabela 37 - RF35</p>

|RF35|Desenvolvimento|
| :---: | :---: |
| Tipos de Elo | Artefatos Relacionados |
| Satisfação | [Especificação Suplementar](../modelagem/especificacao_suplementar.md) |
| Recurso | [Cenários](../modelagem/cenarios.md), [Léxico](../modelagem/lexico.md) |
| Representação | [Casos de Uso](../modelagem/caso_de_uso.md) |
| Alocado | [História de Usuário](../modelagem/agil/historia_de_usuario.md), [Backlog](../modelagem/agil/backlog.md) |
| Agregação | [Requisitos Elicitados](../elicitacao/requisitos_elicitados.md) |

**Autor(es):** [João Pedro Costa](https://github.com/johnaopedro)

<figcaption></figcaption>
</figure>

</details>

### RF36 - Vídeos Explicativos

<details markdown="1">
<summary>Vídeos explicativos dentro do app.</summary>

<figure markdown>

<p style="text-align: center">Tabela 38 - RF36</p>

|RF36|Desenvolvimento|
| :---: | :---: |
| Tipos de Elo | Artefatos Relacionados |
| Satisfação | [Especificação Suplementar](../modelagem/especificacao_suplementar.md) |
| Recurso | [Cenários](../modelagem/cenarios.md), [Léxico](../modelagem/lexico.md) |
| Representação | [Casos de Uso](../modelagem/caso_de_uso.md) |
| Alocado | [História de Usuário](../modelagem/agil/historia_de_usuario.md), [Backlog](../modelagem/agil/backlog.md) |
| Agregação | [Requisitos Elicitados](../elicitacao/requisitos_elicitados.md) |

**Autor(es):** [João Pedro Costa](https://github.com/johnaopedro)

<figcaption></figcaption>
</figure>

</details>

### RF37 - Assistência por Voz

<details markdown="1">
<summary>Ferramenta de assistência por voz para usuários necessitados.</summary>

<figure markdown>

<p style="text-align: center">Tabela 39 - RF37</p>

|RF37|Desenvolvimento|
| :---: | :---: |
| Tipos de Elo | Artefatos Relacionados |
| Satisfação | [Especificação Suplementar](../modelagem/especificacao_suplementar.md) |
| Recurso | [Cenários](../modelagem/cenarios.md), [Léxico](../modelagem/lexico.md) |
| Representação | [Casos de Uso](../modelagem/caso_de_uso.md) |
| Alocado | [História de Usuário](../modelagem/agil/historia_de_usuario.md), [Backlog](../modelagem/agil/backlog.md) |
| Agregação | [Requisitos Elicitados](../elicitacao/requisitos_elicitados.md) |

**Autor(es):** [João Pedro Costa](https://github.com/johnaopedro)

<figcaption></figcaption>
</figure>

</details>

### RF38 - Modo escuro

<details markdown="1">
<summary>O aplicativo oferece uma opção de modo escuro para melhorar a experiência do usuário em ambientes com pouca luz.</summary>

<figure markdown>

<p style="text-align: center">Tabela 40 - RF38</p>

|RF38|Desenvolvimento|
| :---: | :---: |
| Tipos de Elo | Artefatos Relacionados |
| Satisfação | [Especificação Suplementar](../modelagem/especificacao_suplementar.md) |
| Recurso | [Cenários](../modelagem/cenarios.md), [Léxico](../modelagem/lexico.md) |
| Representação | [Casos de Uso](../modelagem/caso_de_uso.md) |
| Alocado | [História de Usuário](../modelagem/agil/historia_de_usuario.md), [Backlog](../modelagem/agil/backlog.md) |
| Agregação | [Requisitos Elicitados](../elicitacao/requisitos_elicitados.md) |

**Autor(es):** [João Pedro Costa](https://github.com/johnaopedro)

<figcaption></figcaption>
</figure>

</details>

### RF39 - Integração MEI

<details markdown="1">
<summary>Permitir que o sistema converse com demais sistemas para MEIs.</summary>

<figure markdown>

<p style="text-align: center">Tabela 41 - RF39</p>

|RF39|Desenvolvimento|
| :---: | :---: |
| Tipos de Elo | Artefatos Relacionados |
| Satisfação | [Especificação Suplementar](../modelagem/especificacao_suplementar.md) |
| Recurso | [Cenários](../modelagem/cenarios.md), [Léxico](../modelagem/lexico.md) |
| Representação | [Casos de Uso](../modelagem/caso_de_uso.md) |
| Alocado | [História de Usuário](../modelagem/agil/historia_de_usuario.md), [Backlog](../modelagem/agil/backlog.md) |
| Agregação | [Requisitos Elicitados](../elicitacao/requisitos_elicitados.md) |

**Autor(es):** [João Pedro Costa](https://github.com/johnaopedro)

<figcaption></figcaption>
</figure>

</details>

### RF40 - Login via GOV.br

<details markdown="1">
<summary>Permitir que o usuário entre no sistema utilizando o GOV.br e subsequente integração com o GOV.br.</summary>

<figure markdown>

<p style="text-align: center">Tabela 42 - RF40</p>

|RF40|Desenvolvimento|
| :---: | :---: |
| Tipos de Elo | Artefatos Relacionados |
| Satisfação | [Especificação Suplementar](../modelagem/especificacao_suplementar.md) |
| Recurso | [Cenários](../modelagem/cenarios.md), [Léxico](../modelagem/lexico.md) |
| Representação | [Casos de Uso](../modelagem/caso_de_uso.md) |
| Alocado | [História de Usuário](../modelagem/agil/historia_de_usuario.md), [Backlog](../modelagem/agil/backlog.md) |
| Agregação | [Requisitos Elicitados](../elicitacao/requisitos_elicitados.md) |

**Autor(es):** [João Pedro Costa](https://github.com/johnaopedro)

<figcaption></figcaption>
</figure>

</details>

### RNF01 - Desempenho

<details markdown="1">
<summary>Garantir o processamento dos dados e retorno aos municípios em até 48 horas e resposta rápida nas interações do usuário (até 3 segundos).</summary>

<figure markdown>

<p style="text-align: center">Tabela 43 - RNF01</p>

|RNF01|Desenvolvimento|
| :---: | :---: |
| Tipos de Elo | Artefatos Relacionados |
| Satisfação | [Especificação Suplementar](../modelagem/especificacao_suplementar.md) |
| Recurso | [Cenários](../modelagem/cenarios.md), [Léxico](../modelagem/lexico.md) |
| Representação | [Casos de Uso](../modelagem/caso_de_uso.md) |
| Alocado | [História de Usuário](../modelagem/agil/historia_de_usuario.md), [Backlog](../modelagem/agil/backlog.md) |
| Agregação | [Requisitos Elicitados](../elicitacao/requisitos_elicitados.md) |

**Autor(es):** [João Pedro Costa](https://github.com/johnaopedro)

<figcaption></figcaption>
</figure>

</details>

### RNF02 - Segurança

<details markdown="1">
<summary>Garantir a confidencialidade dos dados por meio de termos de responsabilidade e acordos de cooperação técnica, além de implementar mecanismos de autenticação para acesso aos dados.</summary>

<figure markdown>

<p style="text-align: center">Tabela 44 - RNF02</p>

|RNF02|Desenvolvimento|
| :---: | :---: |
| Tipos de Elo | Artefatos Relacionados |
| Satisfação | [Especificação Suplementar](../modelagem/especificacao_suplementar.md) |
| Recurso | [Cenários](../modelagem/cenarios.md), [Léxico](../modelagem/lexico.md) |
| Representação | [Casos de Uso](../modelagem/caso_de_uso.md) |
| Alocado | [História de Usuário](../modelagem/agil/historia_de_usuario.md), [Backlog](../modelagem/agil/backlog.md) |
| Agregação | [Requisitos Elicitados](../elicitacao/requisitos_elicitados.md) |

**Autor(es):** [João Pedro Costa](https://github.com/johnaopedro)

<figcaption></figcaption>
</figure>

</details>

### RNF03 - Escalabilidade

<details markdown="1">
<summary>Suportar o cadastro e atualização de dados de até 19,5 milhões de famílias.</summary>

<figure markdown>

<p style="text-align: center">Tabela 45 - RNF03</p>

|RNF03|Desenvolvimento|
| :---: | :---: |
| Tipos de Elo | Artefatos Relacionados |
| Satisfação | [Especificação Suplementar](../modelagem/especificacao_suplementar.md) |
| Recurso | [Cenários](../modelagem/cenarios.md), [Léxico](../modelagem/lexico.md) |
| Representação | [Casos de Uso](../modelagem/caso_de_uso.md) |
| Alocado | [História de Usuário](../modelagem/agil/historia_de_usuario.md), [Backlog](../modelagem/agil/backlog.md) |
| Agregação | [Requisitos Elicitados](../elicitacao/requisitos_elicitados.md) |

**Autor(es):** [João Pedro Costa](https://github.com/johnaopedro)

<figcaption></figcaption>
</figure>

</details>

### RNF04 - Conformidade Legal

<details markdown="1">
<summary>Atender às regulamentações definidas pela Senarc e portarias relacionadas.</summary>

<figure markdown>

<p style="text-align: center">Tabela 46 - RNF04</p>

|RNF04|Desenvolvimento|
| :---: | :---: |
| Tipos de Elo | Artefatos Relacionados |
| Satisfação | [Especificação Suplementar](../modelagem/especificacao_suplementar.md) |
| Recurso | [Cenários](../modelagem/cenarios.md), [Léxico](../modelagem/lexico.md) |
| Representação | [Casos de Uso](../modelagem/caso_de_uso.md) |
| Alocado | [História de Usuário](../modelagem/agil/historia_de_usuario.md), [Backlog](../modelagem/agil/backlog.md) |
| Agregação | [Requisitos Elicitados](../elicitacao/requisitos_elicitados.md) |

**Autor(es):** [João Pedro Costa](https://github.com/johnaopedro)

<figcaption></figcaption>
</figure>

</details>

### RNF05 - Acessibilidade

<details markdown="1">
<summary>Garantir que o sistema seja acessível para operadores municipais e estaduais.</summary>

<figure markdown>

<p style="text-align: center">Tabela 47 - RNF05</p>

|RNF05|Desenvolvimento|
| :---: | :---: |
| Tipos de Elo | Artefatos Relacionados |
| Satisfação | [Especificação Suplementar](../modelagem/especificacao_suplementar.md) |
| Recurso | [Cenários](../modelagem/cenarios.md), [Léxico](../modelagem/lexico.md) |
| Representação | [Casos de Uso](../modelagem/caso_de_uso.md) |
| Alocado | [História de Usuário](../modelagem/agil/historia_de_usuario.md), [Backlog](../modelagem/agil/backlog.md) |
| Agregação | [Requisitos Elicitados](../elicitacao/requisitos_elicitados.md) |

**Autor(es):** [João Pedro Costa](https://github.com/johnaopedro)

<figcaption></figcaption>
</figure>

</details>

### RNF06 - Disponibilidade

<details markdown="1">
<summary>Garantir que o sistema esteja disponível para uso diário.</summary>

<figure markdown>

<p style="text-align: center">Tabela 48 - RNF06</p>

|RNF06|Desenvolvimento|
| :---: | :---: |
| Tipos de Elo | Artefatos Relacionados |
| Satisfação | [Especificação Suplementar](../modelagem/especificacao_suplementar.md) |
| Recurso | [Cenários](../modelagem/cenarios.md), [Léxico](../modelagem/lexico.md) |
| Representação | [Casos de Uso](../modelagem/caso_de_uso.md) |
| Alocado | [História de Usuário](../modelagem/agil/historia_de_usuario.md), [Backlog](../modelagem/agil/backlog.md) |
| Agregação | [Requisitos Elicitados](../elicitacao/requisitos_elicitados.md) |

**Autor(es):** [João Pedro Costa](https://github.com/johnaopedro)

<figcaption></figcaption>
</figure>

</details>

### RNF07 - Compatibilidade com Aplicativo Off-line

<details markdown="1">
<summary>O sistema deve ser compatível com o aplicativo off-line utilizado pelos municípios para coleta e digitação de dados.</summary>

<figure markdown>

<p style="text-align: center">Tabela 49 - RNF07</p>

|RNF07|Desenvolvimento|
| :---: | :---: |
| Tipos de Elo | Artefatos Relacionados |
| Satisfação | [Especificação Suplementar](../modelagem/especificacao_suplementar.md) |
| Recurso | [Cenários](../modelagem/cenarios.md), [Léxico](../modelagem/lexico.md) |
| Representação | [Casos de Uso](../modelagem/caso_de_uso.md) |
| Alocado | [História de Usuário](../modelagem/agil/historia_de_usuario.md), [Backlog](../modelagem/agil/backlog.md) |
| Agregação | [Requisitos Elicitados](../elicitacao/requisitos_elicitados.md) |

**Autor(es):** [João Pedro Costa](https://github.com/johnaopedro)

<figcaption></figcaption>
</figure>

</details>

### RNF08 - Transmissão via Conectividade Social

<details markdown="1">
<summary>A transmissão de dados deve ser realizada exclusivamente por meio da ferramenta Conectividade Social da CAIXA.</summary>

<figure markdown>

<p style="text-align: center">Tabela 50 - RNF08</p>

|RNF08|Desenvolvimento|
| :---: | :---: |
| Tipos de Elo | Artefatos Relacionados |
| Satisfação | [Especificação Suplementar](../modelagem/especificacao_suplementar.md) |
| Recurso | [Cenários](../modelagem/cenarios.md), [Léxico](../modelagem/lexico.md) |
| Representação | [Casos de Uso](../modelagem/caso_de_uso.md) |
| Alocado | [História de Usuário](../modelagem/agil/historia_de_usuario.md), [Backlog](../modelagem/agil/backlog.md) |
| Agregação | [Requisitos Elicitados](../elicitacao/requisitos_elicitados.md) |

**Autor(es):** [João Pedro Costa](https://github.com/johnaopedro)

<figcaption></figcaption>
</figure>

</details>

### RNF09 - Acesso Restrito

<details markdown="1">
<summary>O acesso à base de dados deve ser restrito a instituições autorizadas e mediante assinatura de termos específicos.</summary>

<figure markdown>

<p style="text-align: center">Tabela 51 - RNF09</p>

|RNF09|Desenvolvimento|
| :---: | :---: |
| Tipos de Elo | Artefatos Relacionados |
| Satisfação | [Especificação Suplementar](../modelagem/especificacao_suplementar.md) |
| Recurso | [Cenários](../modelagem/cenarios.md), [Léxico](../modelagem/lexico.md) |
| Representação | [Casos de Uso](../modelagem/caso_de_uso.md) |
| Alocado | [História de Usuário](../modelagem/agil/historia_de_usuario.md), [Backlog](../modelagem/agil/backlog.md) |
| Agregação | [Requisitos Elicitados](../elicitacao/requisitos_elicitados.md) |

**Autor(es):** [João Pedro Costa](https://github.com/johnaopedro)

<figcaption></figcaption>
</figure>

</details>

### RNF10 - Interface intuitiva e amigável

<details markdown="1">
<summary>O design do aplicativo é simples e de fácil navegação.</summary>

<figure markdown>

<p style="text-align: center">Tabela 52 - RNF10</p>

|RNF10|Desenvolvimento|
| :---: | :---: |
| Tipos de Elo | Artefatos Relacionados |
| Satisfação | [Especificação Suplementar](../modelagem/especificacao_suplementar.md) |
| Recurso | [Cenários](../modelagem/cenarios.md), [Léxico](../modelagem/lexico.md) |
| Representação | [Casos de Uso](../modelagem/caso_de_uso.md) |
| Alocado | [História de Usuário](../modelagem/agil/historia_de_usuario.md), [Backlog](../modelagem/agil/backlog.md) |
| Agregação | [Requisitos Elicitados](../elicitacao/requisitos_elicitados.md) |

**Autor(es):** [João Pedro Costa](https://github.com/johnaopedro)

<figcaption></figcaption>
</figure>

</details>

### RNF11 - Suporte a grande base de usuários

<details markdown="1">
<summary>Suporta um grande número de acessos simultâneos.</summary>

<figure markdown>

<p style="text-align: center">Tabela 53 - RNF11</p>

|RNF11|Desenvolvimento|
| :---: | :---: |
| Tipos de Elo | Artefatos Relacionados |
| Satisfação | [Especificação Suplementar](../modelagem/especificacao_suplementar.md) |
| Recurso | [Cenários](../modelagem/cenarios.md), [Léxico](../modelagem/lexico.md) |
| Representação | [Casos de Uso](../modelagem/caso_de_uso.md) |
| Alocado | [História de Usuário](../modelagem/agil/historia_de_usuario.md), [Backlog](../modelagem/agil/backlog.md) |
| Agregação | [Requisitos Elicitados](../elicitacao/requisitos_elicitados.md) |

**Autor(es):** [João Pedro Costa](https://github.com/johnaopedro)

<figcaption></figcaption>
</figure>

</details>

### RNF12 - Integração com sistemas oficiais

<details markdown="1">
<summary>Integrado com sistemas como o CNIS.</summary>

<figure markdown>

<p style="text-align: center">Tabela 54 - RNF12</p>

|RNF12|Desenvolvimento|
| :---: | :---: |
| Tipos de Elo | Artefatos Relacionados |
| Satisfação | [Especificação Suplementar](../modelagem/especificacao_suplementar.md) |
| Recurso | [Cenários](../modelagem/cenarios.md), [Léxico](../modelagem/lexico.md) |
| Representação | [Casos de Uso](../modelagem/caso_de_uso.md) |
| Alocado | [História de Usuário](../modelagem/agil/historia_de_usuario.md), [Backlog](../modelagem/agil/backlog.md) |
| Agregação | [Requisitos Elicitados](../elicitacao/requisitos_elicitados.md) |

**Autor(es):** [João Pedro Costa](https://github.com/johnaopedro)

<figcaption></figcaption>
</figure>

</details>

### RNF13 - Usabilidade

<details markdown="1">
<summary>Navegação intuitiva e acessibilidade geral.</summary>

<figure markdown>

<p style="text-align: center">Tabela 55 - RNF13</p>

|RNF13|Desenvolvimento|
| :---: | :---: |
| Tipos de Elo | Artefatos Relacionados |
| Satisfação | [Especificação Suplementar](../modelagem/especificacao_suplementar.md) |
| Recurso | [Cenários](../modelagem/cenarios.md), [Léxico](../modelagem/lexico.md) |
| Representação | [Casos de Uso](../modelagem/caso_de_uso.md) |
| Alocado | [História de Usuário](../modelagem/agil/historia_de_usuario.md), [Backlog](../modelagem/agil/backlog.md) |
| Agregação | [Requisitos Elicitados](../elicitacao/requisitos_elicitados.md) |

**Autor(es):** [João Pedro Costa](https://github.com/johnaopedro)

<figcaption></figcaption>
</figure>

</details>

### RNF14 - Compatibilidade com Dispositivos

<details markdown="1">
<summary>Compatível com Android e iOS.</summary>

<figure markdown>

<p style="text-align: center">Tabela 56 - RNF14</p>

|RNF14|Desenvolvimento|
| :---: | :---: |
| Tipos de Elo | Artefatos Relacionados |
| Satisfação | [Especificação Suplementar](../modelagem/especificacao_suplementar.md) |
| Recurso | [Cenários](../modelagem/cenarios.md), [Léxico](../modelagem/lexico.md) |
| Representação | [Casos de Uso](../modelagem/caso_de_uso.md) |
| Alocado | [História de Usuário](../modelagem/agil/historia_de_usuario.md), [Backlog](../modelagem/agil/backlog.md) |
| Agregação | [Requisitos Elicitados](../elicitacao/requisitos_elicitados.md) |

**Autor(es):** [João Pedro Costa](https://github.com/johnaopedro)

<figcaption></figcaption>
</figure>

</details>

### RNF15 - Acessibilidade para pessoas com deficiência visual

<details markdown="1">
<summary>O aplicativo oferece recursos de acessibilidade para deficientes visuais, como leitores de tela.</summary>

<figure markdown>

<p style="text-align: center">Tabela 57 - RNF15</p>

|RNF15|Desenvolvimento|
| :---: | :---: |
| Tipos de Elo | Artefatos Relacionados |
| Satisfação | [Especificação Suplementar](../modelagem/especificacao_suplementar.md) |
| Recurso | [Cenários](../modelagem/cenarios.md), [Léxico](../modelagem/lexico.md) |
| Representação | [Casos de Uso](../modelagem/caso_de_uso.md) |
| Alocado | [História de Usuário](../modelagem/agil/historia_de_usuario.md), [Backlog](../modelagem/agil/backlog.md) |
| Agregação | [Requisitos Elicitados](../elicitacao/requisitos_elicitados.md) |

**Autor(es):** [João Pedro Costa](https://github.com/johnaopedro)

<figcaption></figcaption>
</figure>

</details>

### RNF16 - Backup e restauração de sessão

<details markdown="1">
<summary>O aplicativo deve permitir backup e restauração das sessões do usuário, caso haja interrupção ou falha.</summary>

<figure markdown>

<p style="text-align: center">Tabela 58 - RNF16</p>

|RNF16|Desenvolvimento|
| :---: | :---: |
| Tipos de Elo | Artefatos Relacionados |
| Satisfação | [Especificação Suplementar](../modelagem/especificacao_suplementar.md) |
| Recurso | [Cenários](../modelagem/cenarios.md), [Léxico](../modelagem/lexico.md) |
| Representação | [Casos de Uso](../modelagem/caso_de_uso.md) |
| Alocado | [História de Usuário](../modelagem/agil/historia_de_usuario.md), [Backlog](../modelagem/agil/backlog.md) |
| Agregação | [Requisitos Elicitados](../elicitacao/requisitos_elicitados.md) |

**Autor(es):** [João Pedro Costa](https://github.com/johnaopedro)

<figcaption></figcaption>
</figure>

</details>

### RNF17 - Alta disponibilidade e recuperação de desastres

<details markdown="1">
<summary>O aplicativo deve ter mecanismos de recuperação de dados e funcionamento em caso de falhas ou desastres.</summary>

<figure markdown>

<p style="text-align: center">Tabela 59 - RNF17</p>

|RNF17|Desenvolvimento|
| :---: | :---: |
| Tipos de Elo | Artefatos Relacionados |
| Satisfação | [Especificação Suplementar](../modelagem/especificacao_suplementar.md) |
| Recurso | [Cenários](../modelagem/cenarios.md), [Léxico](../modelagem/lexico.md) |
| Representação | [Casos de Uso](../modelagem/caso_de_uso.md) |
| Alocado | [História de Usuário](../modelagem/agil/historia_de_usuario.md), [Backlog](../modelagem/agil/backlog.md) |
| Agregação | [Requisitos Elicitados](../elicitacao/requisitos_elicitados.md) |

**Autor(es):** [João Pedro Costa](https://github.com/johnaopedro)

<figcaption></figcaption>
</figure>

</details>

### RNF18 - Possibilidade de outros idiomas

<details markdown="1">
<summary>O aplicativo deve estar disponível em vários idiomas, permitindo maior acessibilidade.</summary>

<figure markdown>

<p style="text-align: center">Tabela 60 - RNF18</p>

|RNF18|Desenvolvimento|
| :---: | :---: |
| Tipos de Elo | Artefatos Relacionados |
| Satisfação | [Especificação Suplementar](../modelagem/especificacao_suplementar.md) |
| Recurso | [Cenários](../modelagem/cenarios.md), [Léxico](../modelagem/lexico.md) |
| Representação | [Casos de Uso](../modelagem/caso_de_uso.md) |
| Alocado | [História de Usuário](../modelagem/agil/historia_de_usuario.md), [Backlog](../modelagem/agil/backlog.md) |
| Agregação | [Requisitos Elicitados](../elicitacao/requisitos_elicitados.md) |

**Autor(es):** [João Pedro Costa](https://github.com/johnaopedro)

<figcaption></figcaption>
</figure>

</details>

---


## Bibliografia
> SAYÃO, Miriam; LEITE, Julio. Rastreabilidade de Requisitos. PUC-Rio: Departamento de Informática, ISSN 0103-9741, Rio de Janeiro, 2005. Disponível em: https://www-di.inf.puc-rio.br/~julio/rastre.pdf. Acesso em: 07 de jun de 2025.

> TORANZO, M.; CASTRO, J; MELLO, E. Uma proposta para melhorar o rastreamento de requisitos. PUC-Rio: Workshop em Engenharia de Requisitos, Rio de Janeiro, 2002. Disponível em: http://wer.inf.puc-rio.br/WERpapers/artigos/artigos_WER02/toranzo.pdf. Acesso em: 07 de jun de 2025.

## Histórico de Versão

| Versão |    Data    | Descrição  |   Autor   |  Revisor  |
| :----: | :--------: | :---------:| :-------: | :-------: |
|  1.0   | 07/06/2025 | Criação do Documento   | [João Pedro Costa](https://github.com/johnaopedro) | [Julia Gabriela](https://github.com/JuliaGabP)     |
|  1.1   | 07/06/2025 | Desenvolvimento da introdução e metodologia   | [João Pedro Costa](https://github.com/johnaopedro) | [Julia Gabriela](https://github.com/JuliaGabP)     |
|  1.2   | 07/06/2025 | Desenvolvimento das tabelas e formatação   | [João Pedro Costa](https://github.com/johnaopedro) | [Julia Gabriela](https://github.com/JuliaGabP)     |
|  1.3   | 07/06/2025 | Adição de todos os requisitos do projeto  | [João Pedro Costa](https://github.com/johnaopedro) | [Ryan Salles](https://github.com/RA-Salles)         | 
|  1.4   | 07/06/2025 | Hyperlinks indicando a rastreabilidade dos requisitos   | [João Pedro Costa](https://github.com/johnaopedro) | [Ryan Salles](https://github.com/RA-Salles)         |