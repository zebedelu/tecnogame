# Tecnogame

<p align="center">
  <img src="https://img.shields.io/badge/-%20Instituto%20Federal%20Catarinense-006633?style=for-the-badge&logo=google-scholar&logoColor=white">
</p>

O Tecnogame é um jogo da memória interativo desenvolvido especialmente para os totens digitais do evento TecnoEste 2026, realizado no Instituto Federal Catarinense (IFC) – Campus Concórdia.

O projeto tem como objetivo proporcionar uma experiência dinâmica, educativa e acessível ao público do evento, permitindo que visitantes interajam diretamente com a aplicação por meio de interfaces simples e intuitivas.

## Objetivo do Projeto
O sistema foi pensado para funcionar em totens interativos, ou seja, dispositivos de uso público com foco em
- Interface amigável e de fácil compreensão
- Resposta rápida e fluida
- Navegação simplificada (ideal para telas touchscreen)
- Engajamento do público durante o evento

Além disso, o jogo incentiva a participação dos visitantes através de um sistema de pontuação (leaderboard), promovendo competição e interação.

## Funcionalidades
- Jogo da memória interativo com diferentes níveis de dificuldade
- Sistema de pontuação (leaderboard)
- Seleção de dificuldade antes de iniciar a partida
- Tela de fim de jogo com resultado do jogador
- Reinício rápido da partida, ideal para uso contínuo em eventos
- Aplicação web leve, rodando localmente no totem
- Tecnologias Utilizadas

O projeto foi desenvolvido utilizando uma stack simples e eficiente

## Stack

### Backend
- Python
- Flask
### Frontend
- HTML
- CSS
- JavaScript
### Persistência de dados
- Biblioteca pickle (armazenamento local das pontuações)

## Funcionamento
### O backend em Flask é responsável por
- Servir as páginas do jogo
- Gerenciar as rotas (início, jogo, fim, ranking)
- Receber e armazenar pontuações
- Disponibilizar dados do leaderboard via API simples
### Já o frontend
- Controla toda a lógica do jogo da memória
- Gerencia interações do usuário
- Atualiza a interface em tempo real
  
## Créditos e Base do Projeto
O frontend do projeto foi desenvolvido a partir de outro projeto do github
🔗 Base original: memory-game
de https://github.com/isabellatressino/memory-game

## Como executar

### 1° passo
Clonar o projeto
```bash
git clone https://github.com/zebedelu/TecnoGame.git
cd TecnoGame
```

### 2° passo
Executar o back-end
```bash
python index.py
```

### 3° passo
Abrir o navegador no link http://127.0.0.1:5000
```bash
start http://127.0.0.1:5000
```

### 4° passo
divirta-se!

## Contexto de Uso
O projeto foi desenvolvido especificamente para o ambiente do evento TecnoEste 2026, sendo otimizado para
- Execução local (sem dependência de internet)
- Uso contínuo por múltiplos usuários
- Exibição em tela cheia (kiosk/totem mode)
