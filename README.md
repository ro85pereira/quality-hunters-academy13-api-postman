# 🚀 Projeto de Automação de Testes de API com Postman, GitHub Actions e Pages

Bem-vindo ao **Projeto de Automação** da Qa.Coders Academy T-13! 🎉

## 📜 Descrição

Este projeto consiste em uma **coleção de testes de API** desenvolvidos utilizando o **Postman**. O objetivo é fornecer um ambiente prático e eficiente para os alunos do **QA.Coders** testarem as funcionalidades da API do curso da Academy. 🔍

Este repositório contém:
- Uma coleção de testes Postman (`TQA13-QualityHunters.postman_collection.json`)
- Um ambiente Postman configurado (`TQA13.postman_environment.json`)
- Workflow de CI/CD para execução automática dos testes (`.github/workflows/main.yml`)

O objetivo é facilitar a validação das APIs do projeto, tanto manualmente pelo Postman quanto de forma automatizada via linha de comando (Newman) e CI/CD.

## ⚙️ Especificações

- **API alvo**: Os testes são realizados na API da aplicação web **QA.Coders**.
- **Ferramenta utilizada**: O **Postman** é utilizado para a execução dos testes.
- **Linguagem de teste**: Os testes são escritos em **JavaScript**, utilizando a sintaxe do Postman.
- **Integração contínua (CI/CD)**: Os testes são executados em uma pipeline de CI/CD utilizando **GitHub Actions**.
- **Relatórios**: Os resultados das execuções dos testes são disponibilizados no **GitHub Pages**, através do link:
- https://ro85pereira.github.io/quality-hunters-academy13-api-postman/report.html  📊

## 🔧 Pré-requisitos

Antes de executar os testes, certifique-se de que você tem os seguintes requisitos instalados:

- **Postman**: Para executar a coleção de testes. 🖥️
- **Git**: Para clonar este repositório. 💻

## 📝 Como Executar os Testes

1. **Clone o repositório abaixo** para o seu ambiente local:

   https://github.com/ro85pereira/quality-hunters-academy13-api-postman

2. Abra o Postman.
3. Importe a coleção de testes:
- Clique no botão "Import" no canto superior esquerdo do Postman.
- Selecione o arquivo TQA13-QualityHunters.postman_collection.json dentro da pasta do repositório clonado.
4. Importe as variáveis de ambiente
- Clique no botão "Import" novamente.
- Selecione o arquivo TQA13.postman_environment dentro da pasta do repositório clonado.
5. Selecione a variável de ambiente importada na barra lateral do Postman.
6. Execute a coleção de testes:
- Selecione a coleção "TQA13-QualityHunters" e depois no botão "Run" no canto superior direito da tela.
- Na nova aba chamada "Runner", clique em " Run TQA13-QualityHunters no botão inferior do lado direito da tela" e aguarde a execução dos testes.
7. Será aberta uma nova aba chamada "TQA13-QualityHunters- Run results", nela visualize os resultados dos testes.

## 🔄 Integração Contínua (CI/CD)

- O projeto possui um workflow configurado em `.github/workflows/main.yml`.
- A cada push ou pull request, os testes são executados automaticamente via GitHub Actions.
- O status da execução pode ser acompanhado na aba **Actions** do repositório no GitHub.

---

## 📁 Estrutura do Projeto

```
quality-hunters-academy13-api-postman/
├── .github/workflows/main.yml         # Workflow de CI/CD
├── README.md                         # Documentação do projeto
├── TQA13-QualityHunters.postman_collection.json  # Coleção de testes Postman
├── TQA13.postman_environment.json    # Ambiente Postman
```

## 🤝 Contribuição

- Sinta-se à vontade para abrir issues ou pull requests com sugestões, melhorias ou correções.
- Mantenha a padronização dos arquivos e atualize o README se necessário.
  

## 👥 Squad
- Quality Hunters

## 👩‍💻 Tech Lead
- [Cleberson Osório](https://github.com/clestonv)
- [Nara Cyntia](https://github.com/naracyntia)

## 👑 Líder
- [Raphaela Teada](https://github.com/Rapha3la)

## 👨‍💻 Equipe
- [Andreza Menezes Veloso Pipolo](https://github.com/andrezapipolo)
- [Beatriz Ferreira Franco](https://github.com/BeatrizFFranco)
- [Fernanda Ferreira dos Santos](https://github.com/20220512)
- [Luciene Lima Watzel](https://github.com/Luciene-Watzel)
- [Paulo Gustavo de Andrade Porcaro](https://github.com/pgporcaro)
- [Rodrigo Pereira Ramos Cabral](https://github.com/ro85pereira)
