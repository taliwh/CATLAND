# Trabalho da disciplina prog II: Jogo em Linguagem C 
![Screenshot do jogo](assets/screenshot.png)
## Requisitos
É necessário ter a biblioteca Allegro 5 instalada para compilar e executar o jogo:
```bash
sudo apt update
sudo apt install liballegro5-dev
```

## Execução
```bash
make -C code
./code/catland
```
//colocar outros creditos de outros sprites (musicas tambem etc):
## Controles
WASD : movimento  
SHIFT: correr  
SPACE: pular  
CNTRL: agachar  

## Creditos dos assets
lava:
https://www.nicepng.com/ourpic/u2w7r5y3w7q8a9u2_lava-pixel-lava-art-png/  

background:
https://screamingbrainstudios.itch.io/seamless-space-backgrounds?download  

sprite do gato:
https://last-tick.itch.io/animated-pixel-cats-64x64  

sprite das arvores chao mato: (espinhos e bandeira feitos pormim)
https://cainos.itch.io/pixel-art-platformer-village-props  

inimigos (animais)
https://lyaseek.itch.io/miniffanimals  

peixe:
https://itch.io/queue/c/5419577/pixel-gnome-packs?game_id=3340156&password=  

## Creditos das musicas
cat minecraft https://www.youtube.com/watch?v=WsTb8HYZd-U  

pega o peixe: https://www.youtube.com/watch?v=SoZhpnTuQBo  

explicacao oq cada um dos arquivo faz:  

main: execucao o programa  

cat: funcoes q envolvem o jogador  

land: funcoes q envolvem o mundo do jogo (catland)  

joystick: controle do jogador  

states: eventos do jogo (menu, gameover, etc)  

save:   

