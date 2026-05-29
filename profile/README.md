<p align="center">
  <img src="https://raw.githubusercontent.com/laradock/laradock/master/.github/home-page-images/laradock-logo.png" alt="Laradock" width="520">
</p>

<h3 align="center">Use Docker First. Learn About It Later.</h3>

<p align="center">
  Laradock is a full PHP development environment for Docker. It ships pre-configured,
  ready-to-use containers for everything a PHP app needs (Nginx, PHP-FPM, MySQL, Redis,
  and 70+ more), so you can launch a complete local stack in seconds. Works with any PHP
  project (Laravel, Symfony, WordPress, or plain PHP) and runs the same on Linux, macOS,
  and Windows.
</p>

<p align="center">
  <a href="https://laradock.io">Website</a> ·
  <a href="https://laradock.io/docs/Intro">Documentation</a> ·
  <a href="https://github.com/laradock/laradock">GitHub</a>
</p>

---

```bash
git clone https://github.com/laradock/laradock.git
cp .env.example .env
docker-compose up -d nginx mysql redis workspace
```
