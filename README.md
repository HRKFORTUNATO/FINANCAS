# Meu Caixa

App de controle financeiro pessoal que roda direto no navegador (iPhone, Android e computador). Sem servidor e sem dependências: é um único arquivo `index.html`.

## Funcionalidades

- Resumo do mês: saldo, entradas, saídas e gastos por categoria
- Lançamentos de entradas e saídas, com navegação entre meses
- Cartões de crédito (vários cartões)
  - Compras novas parceladas
  - Parcelas em andamento
  - Fatura do mês, fatura por cartão e parcelas futuras
- Tema claro e escuro automático

## Como publicar no GitHub Pages

1. Crie um repositório novo no GitHub (por exemplo, `meu-caixa`).
2. Envie os arquivos deste projeto para a branch `main`.
3. No repositório, abra **Settings > Pages**.
4. Em **Build and deployment**, escolha **Deploy from a branch**, selecione `main` e a pasta `/ (root)`, e clique em **Save**.
5. Após alguns minutos, o app estará em `https://SEU-USUARIO.github.io/meu-caixa/`.

## Instalar no celular

- **iPhone (Safari):** Compartilhar > Adicionar à Tela de Início
- **Android (Chrome):** Menu > Instalar app / Adicionar à tela inicial

## Onde os dados ficam

Tudo é salvo no `localStorage` do navegador de cada aparelho. Nada é enviado para servidores.
Limpar os dados do navegador apaga as informações, e cada aparelho tem seus próprios dados.

## Licença

MIT
