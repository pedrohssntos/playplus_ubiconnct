# 🎮 Dashboard de Assinaturas PlayStation Plus & Ubisoft Connect

Dashboard em Excel para acompanhar o faturamento de uma base de **295 assinantes** de PlayStation Plus, com os adicionais **PlayStation Plus Season Pass** e **Ubisoft Connect Season Pass**.

Funciona só com o Excel, sem macros nem instalação. Os números do dashboard vêm de tabelas dinâmicas ligadas à base de dados.

---

## 📦 Conteúdo do repositório

| Arquivo | Descrição |
|---|---|
| `dashboard_playstation_plus_ubisoft.xlsx` | A planilha com o dashboard |
| `README.md` | Este guia |

---

## 🚀 Como usar

1. Baixe o arquivo `.xlsx`.
2. Abra no **Microsoft Excel** (versão 2016 ou mais recente, no desktop).
3. Se aparecer o aviso amarelo de "Modo de Exibição Protegido", clique em **Habilitar Edição**.
4. A planilha abre na aba **Dashboard**. Use o filtro lateral para explorar os dados.

> 💡 Segmentação de dados e tabelas dinâmicas funcionam melhor no Excel para desktop. Visualizadores online e de celular podem não mostrar o filtro.

---

## 🗂️ Estrutura da planilha

| Aba | Para que serve |
|---|---|
| **Dashboard** | Tela principal: cartões de totais, gráfico e filtro por tipo de assinatura |
| **Cálculos** | Tabelas dinâmicas que alimentam o dashboard e respondem às perguntas de negócio |
| **Bases** | Tabela com os dados de cada assinante (a fonte de tudo) |
| **Assets** | Paleta de cores, logos e ícones usados no visual |

---

## 📊 O que o dashboard mostra

- **Total Subscriptions PlayStation Plus Season Pass:** faturamento do adicional PlayStation Plus Season Pass.
- **Total Subscriptions Ubisoft Connect Season Pass:** faturamento do adicional Ubisoft Connect Season Pass.
- **Total Subscriptions PlayStation Plus:** gráfico de barras com o valor total, separado por assinaturas com renovação automática (**Yes**) e sem (**No**).
- **Filtro lateral (Subscription Type):** escolha **Monthly**, **Quarterly** ou **Annual** para recalcular os cartões e o gráfico.

---

## 📝 Base de dados (aba Bases)

Cada linha é um assinante:

| Coluna | Descrição |
|---|---|
| **Subscriber ID** | Identificador do assinante |
| **Name** | Nome |
| **Plan** | Plano: `Essential`, `Extra` ou `Premium` |
| **Start Date** | Data de início da assinatura |
| **Auto Renewal** | Renovação automática: `Yes` ou `No` |
| **Subscription Price** | Preço da assinatura |
| **Subscription Type** | Periodicidade: `Monthly`, `Quarterly` ou `Annual` |
| **PlayStation Plus Season Pass** | Contratou o adicional? `Yes` ou `No` |
| **PlayStation Plus Season Pass Price** | Valor do adicional |
| **Ubisoft Connect Season Pass** | Contratou o adicional? `Yes` ou `No` |
| **Ubisoft Connect Season Pass Price** | Valor do adicional |
| **Coupon Value** | Valor do cupom aplicado |
| **Total Value** | Valor total da venda |

---

## 🔄 Como atualizar os dados

1. Vá na aba **Bases** e adicione as novas linhas logo abaixo da última. A tabela cresce sozinha.
2. Volte ao Excel e clique em **Dados → Atualizar Tudo** (ou `Ctrl + Alt + F5`).
3. Pronto: cartões, gráfico e perguntas de negócio são recalculados.

> ⚠️ As tabelas dinâmicas **não atualizam sozinhas**. Sem o passo 2, o dashboard continua mostrando os números antigos.

---

## ❓ Perguntas de negócio respondidas

Na aba **Cálculos**:

1. Qual o faturamento total de vendas de planos anuais (todas as assinaturas agregadas)?
2. Qual o faturamento total de planos anuais, separado por renovação automática e sem renovação automática?
3. Qual o total de vendas de assinaturas do PlayStation Plus Season Pass?
4. Qual o total de vendas de assinaturas do Ubisoft Connect Season Pass?

---

## ⚙️ Personalização

A planilha **não tem proteção**, então tudo pode ser editado: textos, cores, logos, gráfico e tabelas.

| Quero... | Como fazer |
|---|---|
| Trocar um logo | Clique com o botão direito na imagem → **Alterar Imagem** |
| Mudar as cores | Veja a paleta na aba **Assets** e altere o preenchimento das formas e do gráfico |
| Mudar o nome de um plano | Edite na aba **Bases** e depois **Dados → Atualizar Tudo** |
| Mudar o título | Clique na caixa de texto do cabeçalho e edite |
| Trocar o nome de boas-vindas | Clique no texto "Bem-vindo" no menu lateral e edite |

---

## ❓ Problemas comuns

- **Os números não mudaram depois de editar a base:** use **Dados → Atualizar Tudo**.
- **O filtro lateral não aparece:** ele só funciona no Excel para desktop (2010 ou mais recente).
- **Não consigo editar:** clique em **Habilitar Edição** no aviso amarelo.

---

## ⚖️ Aviso sobre marcas

PlayStation, PlayStation Plus e Ubisoft Connect são marcas de seus respectivos donos. Os logos usados aqui são ilustrativos. Os dados e os nomes dos assinantes são fictícios.

---

## 👤 Autor

**Pedro** · [LinkedIn](https://www.linkedin.com/in/pedrohssntos/)
