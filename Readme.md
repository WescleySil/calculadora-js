# 📱 Calculadora

Uma calculadora simples desenvolvida para realizar operações matemáticas básicas de forma rápida e prática. ✨

## 📄 Descrição
Este projeto permite que o usuário realize cálculos de adição, subtração, multiplicação e divisão, além de usar parênteses para definir a ordem das operações. O resultado é exibido em tempo real no display. 📈

## 🛠️ Tecnologias Utilizadas
- HTML5
- CSS3
- JavaScript

## 👨‍💻 Como rodar localmente
1. Clone este repositório:
   ```bash
   git clone https://github.com/WescleySil/calculadora-js.git
   ```
2. Acesse a pasta do projeto:
   ```bash
   cd calculadora-js
   ```
3. Abra o arquivo `index.html` no seu navegador preferido. 🌍

## 📦 Como rodar com Docker
1. Certifique-se de ter o Docker instalado em sua máquina. 🐳
2. No terminal, dentro da pasta do projeto, execute o comando para buildar a imagem:
   ```bash
   docker build -t calculadora-js .
   ```
3. Após o build, rode o container:
   ```bash
   docker run -d -p 5000:5000 --name calculadora-js calculadora-js
   ```
4. Acesse no navegador: [http://localhost:5000](http://localhost:5000) 🎉

## 🖥️ Como acessar localmente
Abra o arquivo `index.html` diretamente no navegador ou utilize uma extensão como Live Server no VS Code para rodar localmente. 💡

---
Desenvolvido com 💖 por WescleySil.
