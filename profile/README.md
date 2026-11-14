<img src="https://raw.githubusercontent.com/veryshyjelly-learns/.github/main/assets/learning-jellyfish.png" align="right" width="128" height="128" alt="A mint jellyfish above an open book: Ayush’s learning shelf" />

# Ayush's learning shelf

Course projects, systems implementations, and experiments by [Ayush Biswas (@veryshyjelly)](https://github.com/veryshyjelly).

I learn by building the pieces: parsers, protocols, interpreters, and the tools around them. This directory groups related projects and explains how the components fit together.

[Courses](#courses) · [Systems & languages](#systems--languages) · [Quantitative finance](#quantitative-finance) · [Messaging experiments](#messaging-experiments) · [Earlier developer tools](#earlier-developer-tools) · [Practice & experiments](#practice--experiments)

## Courses

### Boot.dev

[Browse this group →](https://github.com/search?q=org%3Averyshyjelly-learns+topic%3Aboot-dev&type=repositories)

- [BookBot](https://github.com/veryshyjelly-learns/bookbot) — text analysis in Python.
- [Asteroids](https://github.com/veryshyjelly-learns/asteroids-pygame) — an arcade game with Python and Pygame.
- [AI agent](https://github.com/veryshyjelly-learns/ai-agent-boots) — the Python agent project.
- [Web scraper](https://github.com/veryshyjelly-learns/webscraper-python-boots) — crawling and reporting in Python.
- [HTTP from TCP](https://github.com/veryshyjelly-learns/httpfromtcp) — HTTP/1.1 from raw TCP in Go.
- [Megacorp](https://github.com/veryshyjelly-learns/megacorp) — Git course exercises.

### CodeCrafters

[Browse this group →](https://github.com/search?q=org%3Averyshyjelly-learns+topic%3Acodecrafters&type=repositories)

- Build your own Redis in [Rust](https://github.com/veryshyjelly-learns/redis-rust) and [Clojure](https://github.com/veryshyjelly-learns/redis-clojure).
- Build your own shell in [Rust](https://github.com/veryshyjelly-learns/shell-rust), [Go](https://github.com/veryshyjelly-learns/shell-go), and [Gleam](https://github.com/veryshyjelly-learns/shell-gleam).

### Nand2Tetris

[Browse this group →](https://github.com/search?q=org%3Averyshyjelly-learns+topic%3Anand2tetris&type=repositories)

[Hack assembler](https://github.com/veryshyjelly-learns/hack_assembler) → [VM translator](https://github.com/veryshyjelly-learns/vm_translator) → [Jack compiler](https://github.com/veryshyjelly-learns/jack_compiler).

## Systems & languages

[Browse this group →](https://github.com/search?q=org%3Averyshyjelly-learns+topic%3Asystems&type=repositories)

- [Lox interpreter](https://github.com/veryshyjelly-learns/lox-interpreter-rust) — following *Crafting Interpreters*.
- [RISC-V emulator](https://github.com/veryshyjelly-learns/riscv_emulator).
- [Thunder](https://github.com/veryshyjelly-learns/thunder) — implementing TCP in Rust.

## Quantitative finance

[Browse this group →](https://github.com/search?q=org%3Averyshyjelly-learns+topic%3Aquantitative-finance&type=repositories)

- [Regime-aware trading](https://github.com/veryshyjelly-learns/regime-aware-trading) — multi-task trading agents, market regimes, and ablation experiments.
- [Pairs-trading filters](https://github.com/veryshyjelly-learns/pairs_trading_filter) — comparing pair selection and mean-reversion filters.
- [SSD pairs trading](https://github.com/veryshyjelly-learns/ssd_pair_trading) — cointegration and stochastic-dominance experiments.

## Messaging experiments

[Browse this group →](https://github.com/search?q=org%3Averyshyjelly-learns+topic%3Amessaging-experiments&type=repositories)

### Setu: a shared-bot group bridge

[Browse this group →](https://github.com/search?q=org%3Averyshyjelly-learns+topic%3Asetu&type=repositories)

Setu explored connecting groups through a shared bot, with separate platform adapters and a bridge engine. These three archived repositories form one system:

- [Setu Engine](https://github.com/veryshyjelly-learns/setu-engine) — connects chat endpoints exposed by the adapters.
- [Telegram adapter](https://github.com/veryshyjelly-learns/telegram-ki-maya) — exposes Telegram chat events and messaging through WebSockets.
- [WhatsApp adapter](https://github.com/veryshyjelly-learns/whatsapp-ki-maya) — exposes WhatsApp chat events and messaging through WebSockets.

Setu is a separate architectural experiment from [Bifrost](https://github.com/veryshyjelly/bifrost). Bifrost is my current messaging project, using management topics, contact bots, and mirror groups with durable delivery and recovery state.

### Earlier bridge components

[Browse this group →](https://github.com/search?q=org%3Averyshyjelly-learns+topic%3Abridge-prototypes&type=repositories)

- [go_whatsapp_api](https://github.com/veryshyjelly-learns/go_whatsapp_api) — an archived whatsmeow wrapper.
- [go_telegram_api](https://github.com/veryshyjelly-learns/go_telegram_api) — an archived Telegram Bot API wrapper.

These two wrappers were built to work together in an earlier WhatsApp–Telegram bridging experiment.

## Earlier developer tools

[Browse this group →](https://github.com/search?q=org%3Averyshyjelly-learns+topic%3Aearlier-developer-tools&type=repositories)

My competitive programming tooling evolved through [CF-Assist](https://github.com/veryshyjelly-learns/CF-Assist) → [CP-Assist](https://github.com/veryshyjelly-learns/cp-assist) → **[Eitri](https://github.com/veryshyjelly/eitri)**.

CF-Assist and CP-Assist are archived desktop implementations, preserved here as earlier iterations. Development continues in Eitri, the terminal companion on my personal account.

## Practice & experiments

[Practice repositories](https://github.com/search?q=org%3Averyshyjelly-learns+topic%3Apractice&type=repositories) · [Experiments](https://github.com/search?q=org%3Averyshyjelly-learns+topic%3Aexperiments&type=repositories)

- [Exercism](https://github.com/veryshyjelly-learns/exercism-codes) — language practice.
- [VocabTrainer](https://github.com/veryshyjelly-learns/vocabtrainer-rs) — vocabulary practice in the terminal and on an e-reader.

These repositories document learning and experimentation; completion varies by project. Platform names identify the courses and challenges followed.

For Eitri, Bifrost, Vocabulary Studio, Dih Dah Dojo, and my other tools, visit [my personal profile](https://github.com/veryshyjelly).
