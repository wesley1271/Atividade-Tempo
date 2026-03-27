# 📌 Sobre o projeto

### Este projeto exibe o horário atual de Brasília de forma dinâmica e altera automaticamente:

- Saudação **(Bom dia / Boa tarde / Boa noite)**;
- Cores do site;
- Imagem de acordo com o período do dia;

Tudo isso utilizando **JavaScript + manipulação do DOM**.

---

# 🚀 Funcionalidades

- Exibe o horário em tempo real (Brasília);
- Muda a mensagem conforme o horário;
- Altera o background dinamicamente;
- Troca imagens de acordo com o período;

---

  # 💡 Como funciona

O JavaScript captura o horário atual utilizando:

new Date().toLocaleTimeString("pt-BR", {
  timeZone: "America/Sao_Paulo"
})

### Com base na hora:

- 06h–12h → Bom dia
- 13h–17h → Boa tarde
- 18h-05h → Boa noite

E então altera o conteúdo da página dinamicamente.

---

# 📂 Estrutura do projeto

📁 Atividade-Tempo
 ├── Ex015.html
 ├── style15.css
 ├── script.js
 └── img/
     ├── manha.png
     ├── tarde.png
     └── noite.png


# ▶️ Como executar

### Clone o repositório
[git clone https://github.com/seu-usuario/seu-repositorio.git](https://github.com/wesley1271/Atividade-Tempo.git)

### Acesse a pasta
cd seu-repositorio

# Abra no navegador
index.html
     
# ⭐ Apoie

Se gostou do projeto, deixe uma ⭐ no repositório!
