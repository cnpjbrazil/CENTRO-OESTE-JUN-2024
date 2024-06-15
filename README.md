# Dados Públicos do CNPJ da Receita Federal
**Versão: 10/06/2024**

---

## Resumo das Tabelas e Registros

- **EMPRESAS**: 57.640.850 registros
- **ESTABELECIMENTOS**: 60.613.669 registros
- **SIMPLES**: 39.065.196 registros
- **SÓCIOS**: 24.148.897 registros
- **PAÍSES**: 255 registros
- **MUNICÍPIOS**: 5.571 registros
- **QUALIFICAÇÃO DE SÓCIOS**: 68 registros
- **NATUREZA JURÍDICA**: 90 registros
- **CNAES**: 1.359 registros
- **FAIXA ETÁRIA DO SÓCIO**: 10 registros
- **IDENTIFICADOR DO SÓCIO**: 3 registros
- **MATRIZ E FILIAL**: 2 registros
- **MOTIVOS**: 61 registros
- **OPÇÃO SIMPLES/MEI**: 2 registros
- **PORTE DA EMPRESA**: 4 registros
- **SITUAÇÃO CADASTRAL**: 5 registros

---

## Detalhamento dos Dados Disponíveis

Este repositório contém dados detalhados de empresas e estabelecimentos, incluindo:

- **CNPJ**
- **Matriz ou Filial**
- **Razão Social**
- **Nome Fantasia**
- **Situação Cadastral** (Ativa, Baixada, Inapta, Nula ou Suspensa)
- **Data da Situação Cadastral**
- **Motivo da Situação Cadastral**
- **Início da Atividade**
- **Atividade Principal**
- **Código da Atividade Principal (CNAE)**
- **CNAEs Secundários**
- **Endereço, CEP, Telefones, Fax e E-mail**
- **Natureza Jurídica**
- **Capital Social**
- **Porte da Empresa**
- **Dados do Simples Nacional**

---

## Quadro Societário

- **CNPJ**
- **Nome do Sócio**
- **CPF do Sócio** (com os 3 primeiros e os 2 últimos dígitos ocultos, conforme LGPD)
- **Qualificação do Sócio**
- **Data de Entrada na Sociedade**
- **País**
- **CPF do Representante Legal** (com os 3 primeiros e os 2 últimos dígitos ocultos, conforme LGPD)
- **Nome do Representante Legal**
- **Qualificação do Representante Legal**
- **Faixa Etária do Sócio**

---

## Organização dos Arquivos

Os dados são organizados por região do país, por exemplo, Centro-Oeste, Nordeste, Norte, Sudeste e Sul. Para cidades com mais de 1 milhão de registros, os dados estão divididos em 10 arquivos, conforme exemplo abaixo para Belo Horizonte:

- **BELO HORIZONTE_CNPJ_0.xlsx**: Contém somente CNPJs que começam com '0'
- **BELO HORIZONTE_CNPJ_1.xlsx**: Contém somente CNPJs que começam com '1'
- **BELO HORIZONTE_CNPJ_2.xlsx**: Contém somente CNPJs que começam com '2'
- **BELO HORIZONTE_CNPJ_3.xlsx**: Contém somente CNPJs que começam com '3'
- **BELO HORIZONTE_CNPJ_4.xlsx**: Contém somente CNPJs que começam com '4'
- **BELO HORIZONTE_CNPJ_5.xlsx**: Contém somente CNPJs que começam com '5'
- **BELO HORIZONTE_CNPJ_6.xlsx**: Contém somente CNPJs que começam com '6'
- **BELO HORIZONTE_CNPJ_7.xlsx**: Contém somente CNPJs que começam com '7'
- **BELO HORIZONTE_CNPJ_8.xlsx**: Contém somente CNPJs que começam com '8'
- **BELO HORIZONTE_CNPJ_9.xlsx**: Contém somente CNPJs que começam com '9'

---

## Notas Importantes

- **Arquivos Grandes**: Os arquivos com mais de 50MB estão compactados em formato `.rar` e divididos em partes de até 50MB, conforme limite do GitHub.

---

Este repositório oferece uma visão abrangente e detalhada das informações empresariais brasileiras, facilitando a análise e o acesso a dados críticos.
