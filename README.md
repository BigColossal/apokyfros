# Apokyfros

A multiplayer, 2D pixel-art MMORPG with mythical worlds and real-time top-down combat.
Built with Python, Django, Pygame-ce, and React

## Screenshots

...

Empty for now

## About the game

Apokyfros is a real-time MMORPG that brings players into a large mythical world, where control is fought over between two clans. The Selene & the Helios clan. Players fight monsters to become stronger, collect loot to unlock legendary equipment, and interact with friends or foes.

The game focuses on:

- fast, diverse real-time combat
- world story-telling
- cooperative multiplayer
- player progression

## Features

- Real-time multiplayer
- Persistent characters
- Pixel-art graphics
- Dedicated game servers
- Fighting, mining, collecting, trading
- Clans
- Spell Casting
- Diverse weapons
- Skill trees
- and much more!

## Tech Stack

Game Client

- Python
- Pygame-ce

Backend

- Django
- PostgreSQL

Web Client

- React
- Vite
- Typescript

Networking

- WebSockets / TCP sockets

## Architecture

The project is divided into three main components:

Frontend Client
Handles rendering, UI, and player input.

Backend API
Manages authentication, player data, and persistence.

Game Servers
Handle real-time gameplay and multiplayer synchronization.

Diagram:

Client → Game Server → Gameplay

Client → Django API → Database

## Setup

Clone the repository

```
git clone https://github.com/yourname/apokyfros
```

Backend

```
cd backend
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
```

Frontend

```
cd frontend
npm install
npm run dev
```

Game Server

```
cd game_server
python index.py
```

## Controls

...

Empty for now

## Roadmap

Planned features:

...

Empty for now

## Contributing

Contributions are welcome.

Please open an issue to discuss major changes before submitting a pull request.

## License

MIT License
