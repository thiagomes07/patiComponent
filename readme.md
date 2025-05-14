# PATI - Plataforma de Adequação de Tipo de Investidor

## 📌 Descrição do Projeto

Este repositório contém o desenvolvimento de um componente da aplicação **PATI (Plataforma de Adequação de Tipo de Investidor)** como atividade da matéria de UX.

O componente desenvolvido faz parte do frontend da aplicação, que é construída em **HTML e Tailwind CSS 4**, configurado com **PostCSS**.

---

## 🚀 Como Executar o Projeto

### 1️⃣ Pré-requisitos

* Navegador atualizado (Google Chrome, Firefox, Edge)
* Git
* Node.js e npm (para utilizar Tailwind CSS 4)

### 2️⃣ Clonando o Repositório

```bash
# Clone o repositório
git clone https://github.com/thiagomes07/patiComponent

# Acesse o diretório do projeto
cd patiComponente
```

### 3️⃣ Instalando Dependências

```bash
# Instale as dependências do Tailwind CSS
npm install
```

### 4️⃣ Gerando o CSS com Tailwind

```bash
# Executar o Tailwind para gerar o CSS
npx tailwindcss -i ./input.css -o ./output.css --watch
```

### 5️⃣ Executando o Projeto

Abra o arquivo `index.html` diretamente em seu navegador.

---

## 📐 Estrutura do Projeto

* `index.html`: Contém a estrutura do componente.
* `input.css`: Configurações e personalizações do Tailwind CSS.
* `output.css`: Arquivo CSS gerado automaticamente pelo Tailwind.
* `package.json` e `package-lock.json`: Gerenciamento de dependências do Tailwind CSS.
* `README.md`: Instruções e informações do projeto.

---

## 🎨 Link do Figma

* [Link para o Protótipo no Figma](https://www.figma.com/design/doPDJMfPKWiB727qmClFid/Untitled?node-id=0-1&m=dev)

---

## 🚧 Relato do Desenvolvimento

### O que deu certo

* No geral a experiência de utilização do Figma foi bastante positiva porque a dupla já tinha certa afinidade com a ferramente, mas mesmo no caso do dev mode que foi uma novidade, sua utilização foi bastante fluida.
* A extração de estilos por meio do dev mode do Figma deu surpreendentemente certo, tivemos que fazer poucos ajustes.

### Dificuldades encontradas

* Um ponto que não deu totalmente certo foi porque o código extraído do Figma utilizava a fonte Roboto, mas não a tínhamos presente.
* Outro aspecto problemático foi que o código gerado não lida bem com a quebra de componente quando um texto longo é passado, e o texto original: "Emissor: XP Investimentos" acabou quebrando o estilo. Aprendemos que precisamos, portanto, ajustar o código para impedir que isso aconteça por meio de truncate do texto.

---

## 👥 Autores

<div align="center">
<table>
  <tr>
    <td align="center">
      <a href="https://www.linkedin.com/in/lucas-nunes-matheus/">
        <img src="https://media.licdn.com/dms/image/v2/D4D03AQHN4SR2WsAIdA/profile-displayphoto-shrink_200_200/profile-displayphoto-shrink_200_200/0/1710163486566?e=1750896000&v=beta&t=o-9q_kscwkEexlcm92Cobx197j0MsiztrpiTQgiJ9Kg" width="100px;" alt="Foto de Lucas Matheus Nunes" style="border-radius:50%"/>
        <br />
        <b>Lucas Matheus Nunes</b>
      </a>
      <br />
      <a href="https://github.com/lucas-nunes-matheus">
        <img src="https://img.shields.io/badge/GitHub-%23121011.svg?logo=github&logoColor=white)" alt="GitHub" height="25"/>
      </a>
      <a href="https://www.linkedin.com/in/lucas-nunes-matheus/">
        <img src="https://custom-icon-badges.demolab.com/badge/LinkedIn-0A66C2?logo=linkedin-white&logoColor=fff" alt="LinkedIn" height="25"/>
      </a>
    </td>
    <td align="center">
      <a href="https://www.linkedin.com/in/thiagogomesalmeida/">
        <img src="https://media.licdn.com/dms/image/v2/D4D03AQHh3rHCD36uKA/profile-displayphoto-shrink_200_200/profile-displayphoto-shrink_200_200/0/1711828725384?e=1750896000&v=beta&t=Kggq5QNqIQ66GqL7_dT37fq5YO3NQAGBwX9BF0Fq8oU" width="100px;" alt="Foto de Thiago Gomes" style="border-radius:50%"/>
        <br />
        <b>Thiago Gomes</b>
      </a>
      <br />
      <a href="https://github.com/thiagomes07">
        <img src="https://img.shields.io/badge/GitHub-%23121011.svg?logo=github&logoColor=white)" alt="GitHub" height="25"/>
      </a>
      <a href="https://www.linkedin.com/in/thiagogomesalmeida/">
        <img src="https://custom-icon-badges.demolab.com/badge/LinkedIn-0A66C2?logo=linkedin-white&logoColor=fff" alt="LinkedIn" height="25"/>
      </a>
    </td>
  </tr>
</table>
</div>

