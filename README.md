# DSA2101 - Essential Data Analytics Tools: Data Visualisation

## Brazilian Companies: How Does Capital Vary Across Brazilian Companies?

### Team Cool Beans

- Cao Yuehan — e1712022
- Guo Xingchen — e1459295
- Jermaine Khor — e1524257
- John Luke Lim Kang — e1525479
- Sin Ke Yi Rachel — e1524876

[GitHub repository](https://github.com/Xingchen722/DSA2101-project)

## Introduction

Share capital refers to the amount shareholders commit to invest in a company (Accounting and Corporate Regulatory Authority [ACRA], 2026). It varies across firms of different size, legal form and ownership structure. This project examines declared capital among Brazilian companies using data from the Cadastro Nacional da Pessoa Jurídica (CNPJ), the national registry of legal entities maintained by the Receita Federal (Receita Federal do Brasil, 2026). The TidyTuesday data (2026) join the registry’s company records with lookup tables, tagging each company with its legal nature, the qualification of its owner or partner, its size category (micro-enterprise, small-enterprise or other) and its declared capital stock in Brazilian reais (BRL). The dataset covers 141,332 companies and keeps only those with capital above BRL 150,000 (TidyTuesday, 2026). Our findings therefore apply to this higher-capital subset rather than to all Brazilian companies.

Our group asks: how do company size, legal structure and owner qualification relate to the distribution and concentration of declared capital among Brazilian companies? We analyse which companies hold the most capital, and if the capital is spread fairly or concentrated amongst a few firms. We answer this with three visualisations: the first compares capital across company sizes; the second shows which legal structures hold the largest shares of total capital; and the third examines how often high-capital companies appear for different combinations of size and owner role. Some capital values appear to be placeholders rather than real figures, hence, we clean the data before drawing conclusions.

## References

Accounting and Corporate Regulatory Authority. (2026, March 6). [Step 4.4: Deciding on share capital & share types](https://www.acra.gov.sg/register/business/registering-different-business-structures/local-company/deciding-on-share-capital-share-types/).

Receita Federal do Brasil. (2026). *Cadastro Nacional da Pessoa Jurídica - CNPJ* [National Registry of Legal Entities - CNPJ] [Data set]. Portal Brasileiro de Dados Abertos. [https://dados.gov.br/dados/conjuntos-dados/cadastro-nacional-da-pessoa-juridica---cnpj](https://dados.gov.br/dados/conjuntos-dados/cadastro-nacional-da-pessoa-juridica---cnpj)

TidyTuesday. (2026, January 27). *Brazilian companies* [Data set]. GitHub. [https://github.com/rfordatascience/tidytuesday/tree/main/data/2026/2026-01-27](https://github.com/rfordatascience/tidytuesday/tree/main/data/2026/2026-01-27)
