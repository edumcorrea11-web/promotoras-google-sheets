# Promotoras – Integração com Google Sheets

## Objetivo

Este projeto consiste em um formulário web desenvolvido para coletar informações operacionais de promotoras em campo e enviar automaticamente os dados para uma planilha no Google Sheets.

O objetivo é centralizar as informações em tempo real, eliminando processos manuais e melhorando o controle e a visibilidade da operação.

---

## Como funciona

1. A promotora acessa o formulário via navegador (desktop ou celular)
2. Preenche os campos solicitados
3. Ao clicar em "Enviar", os dados são transmitidos automaticamente
4. As informações são registradas instantaneamente no Google Sheets

---

## Estrutura do projeto

- index.html  
  Interface do formulário

- script.js  
  Responsável pelo envio dos dados ao Google Apps Script

- style.css (se aplicável)  
  Responsável pela formatação visual

- README.md  
  Documentação do projeto

---

## Integração

Este projeto utiliza:

- Google Apps Script como endpoint de recebimento
- Google Sheets como base de dados
- JavaScript para envio dos dados via requisição HTTP

---

## Aplicação prática

Este formulário pode ser utilizado para:

- Cadastro de promotoras
- Relatórios de visitas
- Coleta de dados em campo
- Controle operacional

---

## Manutenção

Para alterar o destino dos dados, editar o endpoint no arquivo script.js.

---

## Responsável

Projeto implementado para controle operacional e automação de coleta de dados.
