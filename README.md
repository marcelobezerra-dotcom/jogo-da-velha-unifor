# Jogo da Velha UNIFOR

Este projeto implementa um jogo da velha web com interface institucional da UNIFOR, seguindo o caso de uso de jogar o jogo da velha.

## Funcionalidades
- Modo 2 jogadores (PVP)
- Modo contra o computador
- Formato de partida única ou Melhor de 3 (MD3)
- Placar de vitórias
- Indicador de rodada
- Linha de vitória visual
- Confetes ao vencer
- Efeitos sonoros sintéticos via Web Audio API
- Botão para reiniciar a partida

## Estrutura do projeto
- [src/index.html](src/index.html): arquivo principal com HTML, CSS e JavaScript da aplicação
- [docs/cdu_JogarJogodavelha.md](docs/cdu_JogarJogodavelha.md): caso de uso do projeto
- [RELATORIO_PROMPTS.md](RELATORIO_PROMPTS.md): registro de uso de IA no desenvolvimento

## Acesso ao site
- Página publicada: https://marcelobezerra-dotcom.github.io/jogo-da-velha-unifor/

## Como executar
1. Abra a pasta [src](src)
2. Execute um servidor local, por exemplo:
   - `python -m http.server 3000`
3. Acesse no navegador:
   - http://localhost:3000/index.html
