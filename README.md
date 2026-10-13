<p align="center">
  <img src="./assets/banner.png" alt="Simone - tzii: practical AI, data and software" width="100%" />
</p>

# Simone Perini

AI and software engineer based in Italy. I hold a Higher Technical Diploma in AI & Data (ITS, EQF level 5, 107/110) and did a three-month internship at InfoCamere building document AI for Italian corporate filings.

I mostly write Python. I also maintain an Android app in Kotlin and a KeePass plugin in C#.

**Portfolio:** [tzii.github.io](https://tzii.github.io/)
<!-- Add when ready: · [LinkedIn](https://www.linkedin.com/in/...) · [CV (PDF)](...) · email -->

## Projects

### [italianRAG](./ITALIANRAG_CASE_STUDY.md)

*internship project, code is private*

Extracts typed fields (share capital, governance, multi-year financials) from financial statements, statutes and registry reports, with page-level citations. Questions outside those fields go to Qdrant retrieval. FastAPI service, SQLite fact store, and a 116-case regression benchmark.

### [Pefforza 4](https://github.com/tzii/Pefforza_4)

*Python · [play in the browser](https://tzii.github.io/Pefforza_4/)*

Connect Four with five opponents: random, heuristic, depth-8 bitboard alpha-beta, an exact solver and a PPO agent trained with Stable-Baselines3. A webcam can read a physical board and draw the suggested move on the live feed.

### [ThystTV](https://github.com/tzii/ThystTV)

*Kotlin, Android*

Twitch client forked from [Xtra](https://github.com/crackededed/Xtra). I added floating chat, gesture controls, live rewind, foldable and tablet layouts, local viewing stats and an in-app updater, and I publish signed APK releases.

### [KeeFetch](https://github.com/tzii/KeeFetch)

*C#, .NET Framework*

KeePass plugin that downloads website icons for password entries. It has seven icon providers and four presets, chosen by benchmarking 19 provider configurations. Covered by unit tests and built in CI.

### [ScrapingStore](https://github.com/tzii/ScrapingStore)

*Python*

Scrapes a 3,000-product sandbox store with Playwright, keeps every run in SQLite and compares runs. It generates static dashboards and CSV exports for Power BI.

## Tools I use

Python, FastAPI, Pydantic, pytest, SQL/SQLite, Qdrant, LangChain/LangGraph, Stable-Baselines3, OpenCV, Docker, GitHub Actions, Kotlin, C#
