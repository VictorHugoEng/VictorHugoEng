# Victor Hugo

**Software Engineering student · Backend / Full-stack (Node.js + SQLite)**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/victorhugoeng)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/VictorHugoEng)

Software engineering student based in Brazil (UTC-3). I design, build and **operate** a
production inventory system end-to-end — database, API, frontend, deployment, backups and
updates. I care about software that stays up and doesn't lose data.

Open to **remote internship / junior** roles. English C1 · Spanish B2.

---

## What I focus on

- **Backend & APIs** — Node.js, Express, REST, authentication and authorization.
- **Data** — SQLite (WAL + `synchronous=FULL`), schema design, migrations, backup/restore.
- **Reliability** — automated backups, boot-time recovery, over-the-air updates.
- **Quality** — lint, formatting and tests wired into CI; pull requests required on `main`.

---

## Featured project — [Almoxarifado Inteligente](https://github.com/VictorHugoEng/AlmoxarifadoProject)

Inventory management system in production use by a small industrial team. Built from scratch
and still maintained by me.

[![Almoxarifado Inteligente — dashboard](https://raw.githubusercontent.com/VictorHugoEng/AlmoxarifadoProject/main/docs/screenshots/dashboard.png)](https://github.com/VictorHugoEng/AlmoxarifadoProject)

- **Modules:** stock control, equipment/calibration, purchase requests, private 1-to-1 chat.
- **Roles:** admin, operator, purchasing, read-only.
- **Persistence:** SQLite via the built-in `node:sqlite` module (WAL, ACID, auto-checkpoint).
- **Reliability:** local backups + continuous Google Drive sync, automatic recovery on boot,
  over-the-air updates published to Drive.
- **Security:** scrypt password hashing, 256-bit opaque session tokens, per-route rate
  limiting, account lockout after repeated failed logins, strict CSP/HSTS, and an audit log.
- **Frontend:** installable PWA (vanilla JS + Service Worker) with an offline app shell.
- **Quality:** smoke tests with `node:test`, plus lint/format/audit/build checks in GitHub
  Actions.

`Node.js` `Express` `SQLite` `JavaScript` `PWA` `GitHub Actions` `ESLint` `Prettier`

---

## Tools

`Node.js` `Express` `SQLite` `REST APIs` `Git` `GitHub Actions` `ESLint` `Prettier` `Linux` `PM2` `Docker (basics)`

## Currently learning

- PostgreSQL and relational data modeling.
- Software design and testing practices.

---

## Background

- **B.Sc. Software Engineering** — in progress.
- Self-taught on the stack above; the featured project is where most of it was learned.

---

## Contact

- LinkedIn: [linkedin.com/in/victorhugoeng](https://linkedin.com/in/victorhugoeng)
- GitHub: [@VictorHugoEng](https://github.com/VictorHugoEng)
