<div align="center">
  <h1>⚖️ App Expurgos (Cloud)</h1>
  <p><strong>Automação Inteligente de Expurgos Inflacionários para Advocacia Previdenciária</strong></p>
  
  [![Vercel](https://vercelbadge.vercel.app/api/ezaiex/app-expurgos)](https://app-expurgos.vercel.app)
  [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
</div>

<br>

## 📋 Sobre o Projeto

O **App Expurgos** é uma aplicação web focada na automação e análise de dados referentes a expurgos inflacionários (Planos Econômicos Brasileiros: Bresser, Verão, Collor I e II). Desenvolvido especificamente para atender às demandas do ramo da **Advocacia Previdenciária**, o sistema visa acelerar a análise de extratos, cálculos e identificação de direitos, poupando horas de trabalho manual para os advogados.

_⚠️ Status: Em Desenvolvimento Contínuo_

## ✨ Principais Funcionalidades

- **Análise Automatizada de Documentos**: Integração com a API do Google Generative AI para processamento e extração inteligente de dados.
- **Processamento de Extratos Antigos**: Leitura e interpretação de padrões complexos em extratos bancários de décadas passadas.
- **Eficiência e Escala**: Minimiza o erro humano e maximiza a produtividade na análise de múltiplos processos simultaneamente.
- **Interface Intuitiva**: Interface front-end simples para uso rápido através do navegador (Hospedado na Vercel).

## 🧰 Tecnologias Utilizadas

- **Frontend**: HTML5, CSS3, JavaScript (Vanilla)
- **Backend / Serverless**: Node.js via Vercel Serverless Functions (`api/analisar.js`)
- **Inteligência Artificial**: Google Gemini AI (`@google/generative-ai`)
- **Deploy**: Vercel

## 🚀 Como Executar Localmente

### Pré-requisitos
- [Node.js](https://nodejs.org/) instalado.
- Uma chave de API válida do [Google Gemini](https://aistudio.google.com/).

### Instalação

1. Clone o repositório:
```bash
git clone https://github.com/ezaiex/app-expurgos.git
```

2. Acesse o diretório do projeto:
```bash
cd app-expurgos
```

3. Instale as dependências relacionadas ao back-end (Serverless function API):
```bash
npm install
```

4. Configure as variáveis de ambiente:
Crie um arquivo `.env` na raiz do projeto e adicione sua API Key do Google Gemini:
```env
GEMINI_API_KEY=sua_chave_de_api_aqui
```

5. Para simular o ambiente da Vercel localmente, recomendamos usar o [Vercel CLI](https://vercel.com/cli):
```bash
npm i -g vercel
vercel dev
```

Visite `http://localhost:3000` em seu navegador para ver a aplicação rodando.

## 🤝 Contribuindo

Este projeto está focado em melhorar a rotina de profissionais de direito, portanto, melhorias e sugestões são muito bem-vindas! Sinta-se à vontade para abrir uma *Issue* detalhada ou enviar um *Pull Request* para melhorias no código.

---
<div align="center">
  Desenvolvido por <a href="https://github.com/ezaiex">ezaiex</a>
</div>
