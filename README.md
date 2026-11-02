# 💧 Daily Water Tracker Widget

Um widget leve, moderno e responsivo para rastreamento de consumo diário de água, projetado especialmente para ser incorporado via `/embed` no **Notion** (ou utilizado como web app standalone).

<img width="1625" height="768" alt="tela principal" src="https://github.com/user-attachments/assets/544387c0-c0f3-42b1-b28a-8fa156802e71" />



## ✨ Funcionalidades

- 🔄 **Reset Diário Automático:** O contador zera automaticamente à meia-noite com base na data local.
- 🎯 **Meta Personalizável:** Ajuste a sua meta diária de hidratação (em mL) a qualquer momento.
- ⚡ **Adição Rápida:** Botões de incremento rápido (+200mL, +300mL, +500mL) e entrada manual.
- 📊 **Histórico dos Últimos 7 Dias:** Registro automático do consumo diário para acompanhar a evolução.
- 💾 **Persistência Local:** Todos os dados são salvos no `localStorage` do navegador (sem necessidade de backend ou banco de dados).
- 🎨 **Interface Responsiva & Dark Mode:** Design limpo e adaptável para telas de celular e desktop.

## 🚀 Como usar no Notion

1. Faça o deploy deste projeto (ex: Vercel, Netlify ou GitHub Pages).
2. Copie a URL pública gerada.
3. No seu **Notion**, digite `/embed` e cole o link.
4. Ajuste o tamanho do bloco na página conforme preferir.

## 🛠️ Tecnologias Utilizadas

- **HTML5**
- **Tailwind CSS** (via CDN)
- **JavaScript (ES6+)**
- **Lucide Icons**

## 💻 Como rodar localmente

```bash
# Clone o repositório
git clone [https://github.com/seu-usuario/water-tracker.git](https://github.com/seu-usuario/water-tracker.git)

# Acesse a pasta do projeto
cd water-tracker

# Abra o arquivo index.html no seu navegador favorito
