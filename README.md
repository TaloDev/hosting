# Talo: self-hostable game dev tools

Talo is a collection of tools and APIs designed to make game development easier and to help you make better data-driven decisions.

From essentials like player management, stats and leaderboards to advanced APIs for game saves, event tracking and player authentication.

Talo is available to use via our [Godot plugin](https://github.com/TaloDev/godot), [Unity package](https://github.com/TaloDev/unity) or [REST API](https://docs.trytalo.com/docs/http/authentication).

## Choose your own adventure

Talo is designed to be easily self-hosted and we've included some examples in this repo. To get started: 

* Clone the repo
* Pick an example
* Rename `.env.sample` to `.env`
* Replace the important entries in your `.env` file (like your domain name and other entries marked with "replace-me")
* Run `docker-compose up -d`

See the [self-hosting docs](https://docs.trytalo.com/docs/selfhosting/overview) for a more detailed look into the examples, setting up emails and third-party services.

## Talo's key features

- 👥 [Player management](https://trytalo.com/players): Persist player data across sessions, create segments and handle authentication.
- ⚡️ [Event tracking](https://trytalo.com/events): Track in-game player actions individually and globally.
- 🎮 [Godot plugin](https://trytalo.com/godot): Easily integrate Talo into your Godot game.
- 🎮 [Unity package](https://trytalo.com/unity): Easily integrate Talo into your Unity game.
- 🗃️ **Data exports**: Create CSVs of your Talo data like players, events and feedback.
- 🕹️ [Leaderboards](https://trytalo.com/leaderboards): Highly customisable leaderboards that can sync with Steamworks.
- 💾 [Game saves](https://trytalo.com/saves): A simple and flexible way to load/save game state; also works offline.
- 📊 [Game stats](https://trytalo.com/stats): Track global or per-player stats across your game; also syncs with Steamworks.
- 💬 [Game channels](https://trytalo.com/channels): Send real-time messages between players subscribed to specific topics.
- ⚙️ [Live config](https://trytalo.com/live-config): Update game settings from the web with zero downtime.
- 🔧 [Steamworks integration](https://trytalo.com/steamworks-integration): Hook into Steamworks for authentication and ownership checks.
- 🗣️ [Game feedback](https://trytalo.com/feedback): Collect and manage feedback from your players.
- 🔔 [Player presence](https://trytalo.com/players#presence): See if players are online and set custom statuses.

## Join our community

Have questions, want to share feedback or show off your game? [Join us on Discord](https://trytalo.com/discord) to connect with other developers and get help from the Talo team.

---

Find all the details about Talo on our [website](https://trytalo.com)!
