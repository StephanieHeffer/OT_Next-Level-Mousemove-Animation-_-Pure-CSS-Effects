https://www.youtube.com/watch?v=FY_gvvZtMSM&ab_channel=OnlineTutorials
### CSS:

1. `.container`: Define as propriedades do contêiner.
   - `position: relative;`: Define a posição relativa para o contêiner.
   - `width: 100%;`: Define a largura do contêiner como 100% da largura do seu contêiner pai.
   - `height: 100vh;`: Define a altura do contêiner como 100% da altura da janela de visualização.
   - `display: flex;`: Define o contêiner como um contêiner flexível.
   - `justify-content: center;`: Centraliza os elementos horizontalmente dentro do contêiner.
   - `align-items: center;`: Centraliza os elementos verticalmente dentro do contêiner.
   - `flex-wrap: wrap;`: Permite que os elementos flexíveis sejam dispostos em várias linhas dentro do contêiner.
   - `background: #001300;`: Define o plano de fundo do contêiner como uma cor verde escuro.
   - `overflow: hidden;`: Oculta o conteúdo que estiver fora dos limites do contêiner.
   - `animation: animateColor 5s linear infinite;`: Aplica uma animação chamada `animateColor` ao contêiner, com uma duração de 5 segundos, função de temporização linear e loop infinito.

2. `@keyframes animateColor`: Define a animação `animateColor`.
   - `0%`: Define o estado inicial da animação, onde a propriedade `filter` é aplicada com `hue-rotate(0deg)`.
   - `100%`: Define o estado final da animação, onde a propriedade `filter` é aplicada com `hue-rotate(360deg)`.

3. `.container span`: Define as propriedades dos elementos `<span>` dentro do contêiner.
   - `position: relative;`: Define a posição relativa para os elementos `<span>`.
   - `display: block;`: Define os elementos `<span>` como elementos de bloco.
   - `width: 40px; height: 40px;`: Define a largura e a altura dos elementos `<span>` como 40 pixels cada.

4. `.container span::before`: Define as propriedades dos pseudo-elementos `::before` dos elementos `<span>`.
   - `content: '';`: Adiciona conteúdo aos pseudo-elementos.
   - `position: absolute;`: Define a posição absoluta para os pseudo-elementos.
   - `top: 0; left: 0;`: Posiciona os pseudo-elementos no canto superior esquerdo dos elementos `<span>`.
   - `width: 200%; height: 200%;`: Define a largura e a altura dos pseudo-elementos como o dobro da largura e altura dos elementos `<span>`.
   - `background: #00ff0a;`: Define o fundo dos pseudo-elementos como uma cor verde claro.
   - `box-shadow`: Aplica várias sombras ao redor dos pseudo-elementos, criando um efeito de brilho.
   - `border-radius: 50%;`: Define o raio da borda dos pseudo-elementos como 50%, criando um círculo perfeito.
   - `transition: 2s;`: Define uma transição suave de 2 segundos para o efeito de escala.
   - `transform: scale(0);`: Define uma escala inicial de 0 para os pseudo-elementos, tornando-os invisíveis.

5. `.container span:hover::before`: Define as propriedades dos pseudo-elementos `::before` quando o mouse está sobre os elementos `<span>`.
   - `transition: 0s;`: Remove a transição para que o efeito de escala ocorra instantaneamente.
   - `transform: scale(1);`: Define uma escala de 1 para os pseudo-elementos, fazendo com que eles apareçam.

### HTML:
- `<section class="container">`: Define uma seção com a classe `.container`.
  - `<span></span>`: Define um elemento `<span>` dentro da seção.

Esse código cria um efeito visual atraente que faz com que círculos verdes apareçam e se expandam ao passar o mouse sobre eles. A animação de cor de fundo do contêiner adiciona um toque adicional de dinamismo à interface.
