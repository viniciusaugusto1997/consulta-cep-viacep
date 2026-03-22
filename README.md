# 📍 Consulta de CEP - ViaCEP

Aplicação web desenvolvida para a disciplina de **Desenvolvimento Web I (FATEC)**.

O sistema permite consultar informações de endereço a partir de um CEP, utilizando a API pública **ViaCEP**, com atualização dinâmica da interface.

---

## 🚀 Tecnologias Utilizadas

- **Node.js**
- **Express**
- **HTML5**
- **CSS3**
- **JavaScript (Vanilla)**
- **API ViaCEP**

---

## 📁 Estrutura do Projeto

```
app/
├── .env
├── server.js
├── package.json
└── public/
    ├── assets/
    │   ├── css/main.css
    │   └── js/main.js
    └── pages/index.html
```

---

## ⚙️ Funcionalidades

- 🔎 Consulta de CEP em tempo real
- ✔️ Validação de entrada (apenas 8 dígitos numéricos)
- 📡 Consumo de API externa (ViaCEP)
- 🔄 Atualização dinâmica da interface (DOM)

### 📋 Dados exibidos:

- CEP  
- Logradouro  
- Complemento  
- Bairro  
- Cidade  
- UF  
- Estado  
- Região  
- DDD  

### 🎯 Estados da Interface:

- ⏳ Carregando  
- ❌ Erro  
- ✅ Sucesso  

- 🧹 Limpeza automática dos resultados ao apagar o campo

---

## 🔎 Funcionamento

1. O usuário digita um CEP no campo de entrada  
2. Pressiona a tecla **Enter**  
3. A aplicação realiza uma requisição HTTP para:

```
https://viacep.com.br/ws/{cep}/json/
```

4. Os dados retornados são processados e exibidos dinamicamente na interface

---

## ▶️ Como Executar o Projeto

### 1. Instalar dependências
```
npm install
```

### 2. Iniciar o servidor
```
npm start
```

### 3. Acessar no navegador
```
http://localhost:3000
```

---

## 🌐 Deploy

A aplicação pode ser publicada em serviços de hospedagem como:

- **Render**

---

## 📚 Objetivo do Projeto

Este projeto tem como objetivo consolidar os seguintes conceitos:

- Requisições HTTP com `fetch`
- Consumo de APIs externas
- Manipulação do DOM
- Integração entre frontend e backend
- Estruturação de aplicações com Node.js e Express

---

## 👨‍💻 Autor

**Vinicius Pinto**