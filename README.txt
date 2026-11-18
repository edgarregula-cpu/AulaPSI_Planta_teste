AESSA Virtual 3D - protótipo fictício

Conteúdo: corredor de 16 x 3 metros, quatro salas de 7 x 8 metros (duas de cada lado), secretária de atendimento no centro.

Como executar no PC:
1. Descompactar o ZIP.
2. Na pasta do projeto, executar: python -m http.server 8000
3. Abrir http://localhost:8000 no navegador com Internet.
4. Clicar no cenário e usar WASD + rato.

Meta Quest 3:
1. Publicar o ficheiro index.html num alojamento HTTPS (por exemplo GitHub Pages).
2. Abrir o endereço HTTPS no navegador do Quest 3.
3. Selecionar Enter VR.

Nota: a biblioteca Three.js é carregada da Internet. A versão inicial permite navegação WASD no PC e visualização VR no headset; ainda não tem locomoção com controladores nem colisões físicas.