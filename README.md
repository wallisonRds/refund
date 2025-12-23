# refund

💰 Sistema de Controle de Despesas

Este projeto é um sistema simples de controle de despesas, desenvolvido com HTML, CSS e JavaScript puro, que permite adicionar, listar e remover despesas, além de calcular automaticamente o total gasto.

O foco do projeto é praticar manipulação do DOM, eventos, formatação de valores monetários e boas práticas em JavaScript.
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

✨ Funcionalidades

✅ Adicionar despesas com:

Nome

Categoria

Valor formatado em Real (R$)

✅ Listar despesas dinamicamente

✅ Remover despesas individualmente

✅ Atualização automática:

Quantidade de despesas

Valor total

✅ Formatação automática do valor digitado no input

✅ Interface simples e intuitiva

🧠 Como funciona

As despesas são adicionadas dinamicamente à lista 

O total é recalculado do zero sempre que:

Uma despesa é adicionada

Uma despesa é removida

O cálculo é feito lendo diretamente os elementos existentes no DOM

O sistema usa delegação de eventos para remover itens da lista
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

🛠️ Tecnologias Utilizadas

HTML5

CSS3

JavaScript (Vanilla JS)

📂 Estrutura do Projeto
📁 projeto-despesas
├── 📁 img
│   ├── food.svg
│   ├── transport.svg
│   ├── remove.svg
│   └── ...
├── index.html
├── style.css
├── script.js
└── README.md
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

▶️ Como usar

Clone o repositório:

git clone https://github.com/wallisonRds/refund.git

Abra o arquivo index.html no navegador

Preencha o formulário:

Nome da despesa

Categoria

Valor

Clique em Adicionar

Para remover uma despesa, clique no ícone 🗑️ ao lado do item
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

📌 Aprendizados Aplicados

Manipulação do DOM

Criação dinâmica de elementos HTML

Delegação de eventos

Formatação de moeda com toLocaleString

Organização de código JavaScript

Tratamento de erros com try...catch
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

🚀 Possíveis Melhorias Futuras

🔹 Salvar despesas no localStorage

🔹 Editar despesas

🔹 Filtro por categoria

🔹 Gráficos de gastos

Projeto com fins educacionais e de aprendizado em JavaScript.
