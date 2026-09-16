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

![Home](screenchots/área_inicial_sem_registros1)

![Home 02](screenchots/tela_inicial_sem_transações2)

![Home03](screenchots/tela-inicial-com-valores)

![Home 04](screenchots/
