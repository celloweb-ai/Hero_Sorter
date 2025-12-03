// Definição de Variáveis e Dados (Entrada)
let heroi = "Felipe";
let xp = 7500;

// O desafio pede Laços de Repetição. 
// Vamos simular um laço simples que poderia processar múltiplos heróis ou batalhas.
// Aqui faremos um loop de 1 volta apenas para demonstrar a estrutura, 
// mas você poderia usar um array de heróis.
let contador = 0;

while (contador < 1) {
    let nivel = "";

    // Estruturas de Decisão (Lógica de Níveis)
    if (xp < 1000) {
        nivel = "Ferro";
    } else if (xp >= 1001 && xp <= 2000) {
        nivel = "Bronze";
    } else if (xp >= 2001 && xp <= 5000) {
        nivel = "Prata";
    } else if (xp >= 5001 && xp <= 7000) {
        nivel = "Ouro";
    } else if (xp >= 7001 && xp <= 8000) {
        nivel = "Platina";
    } else if (xp >= 8001 && xp <= 9000) {
        nivel = "Ascendente";
    } else if (xp >= 9001 && xp <= 10000) {
        nivel = "Imortal";
    } else if (xp >= 10001) {
        nivel = "Radiante";
    } else {
        nivel = "Desconhecido"; // Tratamento de erro ou caso não mapeado
    }

    // Saída
    console.log(`O Herói de nome **${heroi}** está no nível de **${nivel}**`);
    
    contador++;
}
