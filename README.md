# Projeto: Função de Saudação em JavaScript

Este projeto demonstra o uso de **funções em JavaScript** com **parâmetros opcionais** e **valores padrão** para criar mensagens personalizadas.

---

## Código

```javascript
function saudacao(nome = "") {
    if (nome) {
        console.log(`Olá, ${nome}! Boas vindas!`);
    } else {
        console.log("Olá! Boas vindas!");
    }
}

saudacao("Lucas");
saudacao();
