# 🔢 Até 30 Eu Adivinho

Um jogo matemático interativo onde o computador adivinha o número que você pensou (de 1 a 30) com apenas 5 perguntas! Baseado no clássico algoritmo de adivinhação por soma de pesos (representação binária).

![Prévia do jogo](screenshot.png)  
*Uma versão moderna e animada do algoritmo criado por Anderson Misson em 2016.*

## ✨ Funcionalidades

- 🎮 **Jogabilidade simples**: Pense em um número e responda "SIM" ou "NÃO" para cada lista apresentada.
- 🔄 **Embaralhamento animado**: A cada pergunta, os números dançam por 3 segundos com uma roleta visual – os botões ficam desativados até a animação terminar.
- 🔀 **Ordenação opcional**: Clique em "ORDENAR" para ver os números em ordem crescente (ou volte ao modo embaralhado).
- 🧠 **Explicação matemática**: Ao final, o jogo mostra a soma dos pesos que levou ao resultado (ex: SIM nas perguntas 1, 3 e 5 = 1+4+16 = 21).
- 📜 **Histórico local**: As últimas 5 partidas ficam salvas no seu navegador (aparecem na tela inicial).
- 👥 **Contador de acessos**: Quantas vezes o jogo foi iniciado (armazenado localmente).
- ❓ **Modal explicativo**: Clique no botão "Como funciona?" para entender a lógica por trás das listas.

## 🎯 Como jogar

1. Clique em **INICIAR JOGO**.
2. Pense em um número de **01 a 30**.
3. Para cada uma das 5 perguntas, o jogo mostrará uma lista de números.
4. Responda **SIM** se o número que você pensou estiver na lista, ou **NÃO** caso contrário.
5. Após a quinta pergunta, o jogo revelará o número que você pensou!
6. Você pode ordenar a lista a qualquer momento clicando em **ORDENAR** (a ordenação é apenas visual, não altera o resultado).

## 🧮 A matemágica

Cada pergunta tem um peso: 1, 2, 4, 8 e 16. Quando você responde **SIM**, o peso é somado. Os números em cada lista foram escolhidos de forma que a soma dos pesos das respostas "SIM" seja exatamente o número pensado. É uma representação binária disfarçada!

**Exemplo**: Se você pensou no **21**:
- Pergunta 1 (peso 1) → SIM (lista contém 21)
- Pergunta 2 (peso 2) → NÃO
- Pergunta 3 (peso 4) → SIM
- Pergunta 4 (peso 8) → NÃO
- Pergunta 5 (peso 16) → SIM
Soma = 1 + 4 + 16 = **21** 🎉

## 🛠️ Tecnologias utilizadas

- **HTML5** – estrutura da página
- **CSS3** – estilos, animações e design responsivo
- **JavaScript (ES6)** – lógica do jogo, manipulação do DOM e armazenamento local

## 🚀 Como executar localmente

1. Clone este repositório:
   ```bash
   git clone https://github.com/seu-usuario/ate-30-eu-adivinho.git
