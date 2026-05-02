🧪 Sintetizador de Fluido Numérico Interativo

Um experimento interativo e áudio-visual criado com JavaScript puro e HTML5 Canvas. Este projeto simula um fluido magnético de partículas de neon que formam números, inspirado na paleta de cores e na identidade visual do Google I/O.

✨ Funcionalidades (Modos de Interação)

A física matemática foi configurada para criar quatro comportamentos dinâmicos distintos:

🌌 Modo Galáxia: Ao trocar de número, as partículas giram numa espiral complexa antes de se alinharem na nova forma.

🌊 Modo Fluido: Passar o rato (ou o dedo) sobre as partículas cria uma onda de luz branca e repele as partículas suavemente, graças à deteção de colisão elástica.

🎉 Modo Celebração: Um clique no fundo escuro dispara uma "onda de choque" mecânica, dispersando as partículas pelo ecrã com um efeito sonoro de sweep (explosão).

🎵 Sintetizador Integrado: Cada número está mapeado para uma nota de uma Escala Pentatónica. A Web Audio API gera ondas senoidais em tempo real para criar uma experiência sensorial completa.

🛠️ Tecnologias Utilizadas

HTML5 <canvas>: Para a renderização aditiva e manipulação de milhares de partículas a 60 FPS.

Vanilla JavaScript (ES6): Toda a lógica de física vetorial, molas elásticas e animação de frames (sem bibliotecas externas como Three.js ou Pixi.js).

Web Audio API: Para a síntese sonora em tempo real (osciladores e envelopes ADSR).

Tailwind CSS: (Via CDN) Para a estilização da interface Glassmorphism sobreposta ao canvas.

🚀 Como correr o projeto localmente

Como o projeto não utiliza dependências ou frameworks complexos de build, executá-lo é extremamente simples:

Clone este repositório:

git clone [https://github.com/Macelo2020/sintetizador-de-fluido-numerico-interativo.git](https://github.com/Macelo2020/sintetizador-de-fluido-numerico-interativo.git)


Abra a pasta do projeto.

Dê um duplo-clique no ficheiro index.html para abri-lo no seu navegador favorito.
(Recomendado o uso de navegadores modernos como Chrome, Edge ou Firefox para melhor performance de renderização no Canvas).

🎨 Como customizar

Se quiser explorar e alterar o código, pode modificar facilmente alguns parâmetros no index.html:

Quantidade de Partículas: Procure por initParticles(3800) e altere o número (reduza se ficar lento no seu computador, aumente se quiser mais densidade).

Cores: Procure pelo array GOOGLE_COLORS = ['#5b9cfc', '#ff5a4d', '#ffce33', '#4ce36f']; e adicione os seus próprios códigos Hex de cores neon.

📄 Licença

Este projeto é de código aberto e está disponível para qualquer pessoa usar, estudar e modificar. Divirta-se a criar!