# SAVI — Logística e Estoque

Painel de demonstração para acompanhar o estoque de materiais do SAVI, projeto relacionado à automação por voz e IoT aplicado à Indústria 4.0. A interface tem visual inspirado em terminal e foi preparada para a Feira Tecnológica da Etec da Zona Leste 2026.

## Funcionalidades

- Exibe o total de unidades, entradas e saídas do dia, produtos críticos, capacidade ocupada, abastecimento médio e movimentações.
- Lista os materiais com quantidade atual, estoque mínimo, nível de abastecimento e situação.
- Registra entradas e saídas, validando a quantidade, o saldo disponível e o limite do depósito.
- Mostra a ocupação do depósito, configurado inicialmente para **500 unidades**.
- Mantém um histórico das movimentações recentes.
- Salva os dados no armazenamento local do navegador (`localStorage`), para que continuem disponíveis quando a página for aberta novamente no mesmo navegador e dispositivo.
- Adapta o layout para telas menores, como celulares.

## Como abrir

1. Baixe ou clone este projeto.
2. Abra o arquivo `estoque.html` em um navegador atualizado.
3. Escolha um produto, informe a quantidade e selecione **Entrada** ou **Saída** para registrar uma movimentação.

Não é necessário instalar dependências nem iniciar um servidor para usar a demonstração.

## Tecnologias

- HTML
- CSS
- JavaScript
- `localStorage` do navegador para persistência local


## Imagens
![alt text](<Screenshot From 2026-11-15 11-48-23.png>)

## Objetivo

Esse layout tem como objetivo ser implementado junto com outras partes do sistema SAVI. Onde vamos conseguir demonstrar melhor a funcionabilidade do nosso projeto. Esse layout não é o único. Os outros serão implementados e posteriormente postados nesse repositório.

## Observação

Esta versão é uma demonstração de controle de estoque no navegador. Ela não se conecta a sensores, dispositivos IoT, assistentes de voz, banco de dados ou servidor. Os dados ficam somente no navegador e dispositivo em que foram registrados; limpar os dados do navegador pode apagá-los.
