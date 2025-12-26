// ==========================================
// Desafio Classificador de Nível de Herói
// Plataforma: DIO
// Linguagem: JavaScript (Node.js)
// ==========================================

// Variáveis principais
let nomeHeroi = "Denise";
let xpHeroi = 5000;

// Variável para armazenar o nível
let nivelHeroi;

// Estrutura de decisão para classificar o nível
if (xpHeroi <= 1000) {
  nivelHeroi = "Ferro";
} else if (xpHeroi <= 2000) {
  nivelHeroi = "Bronze";
} else if (xpHeroi <= 5000) {
  nivelHeroi = "Prata";
} else if (xpHeroi <= 7000) {
  nivelHeroi = "Ouro";
} else if (xpHeroi <= 8000) {
  nivelHeroi = "Platina";
} else if (xpHeroi <= 9000) {
  nivelHeroi = "Ascendente";
} else if (xpHeroi <= 10000) {
  nivelHeroi = "Imortal";
} else {
  nivelHeroi = "Radiante";
}

// Exibição da mensagem final
console.log(`O Herói de nome ${nomeHeroi} está no nível de ${nivelHeroi}`);
