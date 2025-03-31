# Tetris Game (테트리스 게임)

A classic Tetris game implementation with modern features.
클래식 테트리스 게임에 현대적인 기능을 추가한 구현체입니다.

## Features (기능)
- Clean and modern UI
- Particle effects when clearing lines
- Pleasant sound effects
- Responsive controls
- Score and level system

## How to Play (플레이 방법)
1. Clone this repository
2. Run a local server (e.g., `python3 -m http.server 3000`)
3. Open `http://localhost:3000/game_new.html` in your browser

## Controls (조작법)
- ← → : Move piece left/right (블록 좌우 이동)
- ↑ : Rotate piece (블록 회전)
- ↓ : Soft drop (블록 천천히 떨어뜨리기)
- Space : Hard drop (블록 즉시 떨어뜨리기)
- Esc : Return to menu (메뉴로 돌아가기)

## Technologies Used (사용 기술)
- HTML5 Canvas
- JavaScript
- Web Audio API
- CSS3

## Installation

1. Make sure you have Python 3.x installed on your system
2. Install the required dependencies:
```bash
pip install -r requirements.txt
```

## Game Rules
- Clear lines to score points
- Each line cleared gives you 100 points × current level
- Game speed increases as you level up
- Game ends when pieces stack up to the top 