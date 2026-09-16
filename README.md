# Bobble Finanças

Aplicativo Android de gerenciamento financeiro pessoal desenvolvido com Kotlin e Jetpack Compose.

## Sobre o projeto

O Bobble Finanças é um projeto autoral criado para facilitar a organização da vida financeira pessoal.

A proposta é oferecer uma interface simples, clara e visualmente confortável para que o usuário possa registrar receitas, despesas, dívidas, parcelas e objetivos financeiros.

O projeto também está sendo desenvolvido com foco em funcionamento offline, privacidade e possibilidade de evolução para um produto comercial.

## Funcionalidades

- Cadastro de receitas;
- Cadastro de despesas;
- Organização de gastos por categoria;
- Visualização do saldo disponível;
- Gráfico de distribuição financeira;
- Histórico de movimentações;
- Filtros por período;
- Filtros por tipo de movimentação;
- Cadastro de dívidas;
- Acompanhamento de parcelas;
- Registro de parcelas pagas;
- Atualização automática do valor restante;
- Registro automático de pagamentos no histórico;
- Estratégia de organização por menor ou maior dívida;
- Envelopes financeiros para objetivos;
- Identidade visual própria.

## Tecnologias

- Kotlin;
- Android Studio;
- Jetpack Compose;
- Material 3;
- Navigation Compose;
- Android SDK.

## Identidade visual

O projeto utiliza uma identidade visual própria baseada em cores suaves:

- Azul calmo para textos e ações principais;
- Azul claro pastel para planejamento;
- Branco off-white para o fundo;
- Coral suave para dívidas;
- Verde suave para receitas e valores positivos.

A proposta visual é transmitir organização, tranquilidade e clareza durante o uso do aplicativo.

## Arquitetura planejada

A próxima etapa do projeto é evoluir a estrutura atual para uma arquitetura com separação entre interface, regras de negócio e armazenamento.

```text
Jetpack Compose
      ↓
ViewModel
      ↓
Repository
      ↓
Room
      ↓
SQLite
      ↓
Armazenamento local do Android
```
## Screenshots

###Tela inicial

![Capa](screenshots/capa)

![Home](screenshots/área_inicial_sem_registros1)

![Home 02](screenshots/tela_inicial_sem_transações2)

![Home03](screenshots/tela%20inicial%20com%20valores)

![Home04](screenshots/gr%C3%A1fico%20na%20tela%20inicial%2002)

![Home05](screenshots/gr%C3%A1fico%20na%20tela%20inicial%20com%20valores)

![Movimentações recentes na home](screenshots/movimenta%C3%A7%C3%B5es%20recentes%20na%20tela%20inicial)

### Nova Receita

![Nova Receita](screenshots/Nova%20Receita)

### Nova Despesa

![Nova Despesa](screenshots/nova_despesa)

![Catégorias de despesa](screenshots/tela%20de%20nova%20despesa%20com%20cat%C3%A9gorias)


### Envelopes

![Tela principal](screenshots/tela%20principal%20de%20envelopes)

![Criação de envelope](screenshots/tela%20de%20cria%C3%A7%C3%A3o%20de%20envelopes)

![Tela de envelope criado](screenshots/tela%20de%20envelope%20criado%20sem%20valor)

![Tela de envelope criado e com valor adicionado](screenshots/tela%20de%20envelope%20criado%2C%20com%20valor%20adicionado%20e%20porcentagem%20atualizada)

### Histórico

![Tela inicial de histórico](screenshots/tela%20principal%20do%20hist%C3%B3rico)

![Filtro de data](screenshots/tela%20de%20hist%C3%B3rico%20com%20filtro%20de%20data)

![Filtro 02](screenshots/filtro%20por%20data%20no%20hist%C3%B3rico%2002)

![Filtro por catégoria](screenshots/filtro%20por%20cat%C3%A9goria%20no%20hist%C3%B3rico)


### Divídas 

![Tela de divídas](screenshots/tela%20de%20div%C3%ADdas%20sem%20valor)

![Tela de estratégias de divídas](screenshots/tela%20de%20estrat%C3%A9gias%20na%20tela%20de%20d%C3%ADvidas)

![Tela de divída criada](screenshots/tela%20de%20div%C3%ADdas%20adicionada%20com%20valor)

![Tela com divída paga adicionada](screenshots/tela%20de%20d%C3%ADvidas%20com%20parcela%20paga%20adicionada)

![Tela com divída quitada](screenshots/tela%20de%20div%C3%ADda%20com%20div%C3%ADda%20quitada)
