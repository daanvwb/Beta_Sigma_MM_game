# Beta Sigma MM Game

A live, multiplayer **market making game** to play with friends.

Players join a shared game session, quote bid/ask prices on one or more
instruments, trade against each other in real time, and are scored on their
P&L when the round settles.

The game is played in the browser, on a computer or a phone.

> **Status:** early setup. Game rules are still being written.

## Tech stack

- **Backend:** Python, which runs the game logic, order matching and scoring.
- **Frontend:** a mobile-friendly web page that talks to the backend over
  WebSockets for live updates.
- **Language:** English.

## Repository layout

```
.
├── docs/
│   └── RULES.md      # The game rules (source of truth for how the game works)
├── README.md
└── ...               # Code to be added once the stack is chosen
```

## Getting started

_Setup instructions will be added once the tech stack is chosen._

## Working together

- `main` should always be in a playable state.
- Make changes on a feature branch (`git checkout -b feature/order-book`) and
  merge through a pull request so the other person can review.
- Keep `docs/RULES.md` up to date whenever game mechanics change.
