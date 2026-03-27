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

**obs:** Caso queira ver as outras páginas, mude a var number por um número.
Por ex:

var hora = 12;


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
     
---

# ▶️ Como executar

### Clone o repositório
https://github.com/wesley1271/Atividade-Tempo.git

### Acesse a pasta
cd seu-repositorio

# Abra no navegador
index.html

---

# 🖥️ Imagens

<img width="998" height="672" alt="image" src="https://github.com/user-attachments/assets/106d4586-c592-48c8-b27b-bc9f798e731e" />

---

<img width="1025" height="708" alt="image" src="https://github.com/user-attachments/assets/6949983b-153e-445a-9872-25968dddb63b" />

---

<img width="1124" height="654" alt="image" src="https://github.com/user-attachments/assets/e8d95045-de96-445f-ba6f-f1a327c99ac9" />

  ---
  
# ⭐ Apoie

Se gostou do projeto, deixe uma ⭐ no repositório!
