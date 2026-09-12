<p align="center">
  <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSm1Z7752bOKmBssX_FeVMtjmgG9ghBpxjfvA9DsNsGkQ&s=10" alt="UniCesumar" height="90">
</p>

<h1 align="center">RPG Game Class — Unity 2D</h1>
<p align="center"><em>Material de aula — top-down com Menu, Game e Game Over</em></p>

---

## Para que serve este repositório?

Projeto de **RPG/top-down 2D** usado em sala, com fluxo completo de cenas:

- Menu → Game → Game Over  
- Player com vida (Slider), animação e movimento nos eixos  
- Inimigo (`EnemyController`)  
- Power-up e retorno ao jogo (`PowerUp`, `ReturnGame`, `GameManager`)

## Tecnologias

| Item | Detalhe |
|------|---------|
| Engine | **Unity 2022.3.16f1** (LTS) |
| Linguagem | C# |
| UI | Slider de vida / SceneManager |

## Estrutura principal

```
Assets/
├── Scripts/
│   ├── PlayerController.cs
│   ├── EnemyController.cs
│   ├── GameManager.cs
│   ├── PowerUp.cs
│   └── ReturnGame.cs
└── Scenes/
    ├── Menu.unity
    ├── Game.unity
    └── Game Over.unity
```

## Como abrir (aluno)

1. Unity **2022.3.16f1**  
2. Clone:
   ```bash
   git clone https://github.com/UniCesumarGames/rpg_game_class_unity.git
   ```
3. Comece por `Assets/Scenes/Menu.unity` → **Play**

## Controles

| Ação | Controle |
|------|----------|
| Mover | Horizontal / Vertical |
| Observar vida | Slider na UI |

## Exercícios sugeridos

1. Fazer o dano do inimigo reduzir `playerHealth` e atualizar o Slider  
2. Trocar de cena ao chegar em 0 de vida (`SceneManager`)  
3. Documentar no caderno o fluxo Menu → Game → Game Over

---

<p align="center">UniCesumar — Jogos Digitais / Desenvolvimento de Games</p>
