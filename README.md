# 💀 A Jornada do Esqueleto na Floresta (Jogo 2D)

Um jogo de plataforma 2D em HTML5 Canvas no estilo clássico de **Super Mario Bros**, onde você controla um simpático esqueleto em uma floresta mágica repleta de desafios!

---

## 🎮 Como Jogar

Você pode jogar de **duas formas simples**:

### Opção 1: Direto no Navegador (Mais Rápido)
Basta dar um duplo clique no arquivo **`index.html`** para abrir o jogo instantaneamente em qualquer navegador moderno (Chrome, Edge, Firefox, etc.).

### Opção 2: Servidor Local Node.js
Se preferir rodar via servidor local:
```bash
node server.js
```
E acesse no seu navegador:  
👉 **http://localhost:3000**

---

## 🕹️ Controles

- **`W`** (ou `Espaço` / `Seta Cima`): **Pular**  
  *(Dica: segure a tecla para um salto mais alto estilo Mario, ou dê um toque rápido para um salto curto)*
- **`A`** (ou `Seta Esquerda`): **Mover para a Esquerda**
- **`D`** (ou `Seta Direita`): **Mover para a Direita**
- **`R`**: **Reiniciar a Fase Atual**
- Também há botões na tela para cliques com mouse ou telas sensíveis ao toque!

---

## 🌲 As 5 Fases da Floresta

1. **Fase 1 (Introdutória)**: 5 obstáculos espaçados (troncos de árvore e caixas de madeira) para se acostumar com a física de pulo.
2. **Fase 2**: 10 obstáculos, introduzindo barris de carvalho e caixas intercaladas.
3. **Fase 3**: 16 obstáculos com ritmo mais rápido e barris duplos.
4. **Fase 4**: 23 obstáculos ágeis que exigem precisão nos saltos.
5. **Fase 5 (O Grande Desafio Final)**: 32 obstáculos densos culminando no **Altar Sagrado**. Ao alcançar o final, o esqueleto conquista a **Maçã Dourada/Vermelha** com uma cutscene especial de comemoração, confetes e fanfarra de vitória!

---

## 🔊 Recursos de Áudio

- **Efeitos Sonoros Retrô**: Sons de pulo 8-bit, chocalho de ossos ao colidir com obstáculos e fanfarras de vitória através da Web Audio API nativa.
- **Música Chiptune**: Trilha ambiente mística de floresta com botão de ligar/desligar no menu superior.
