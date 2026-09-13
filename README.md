<!-- DevSponsors Badges -->
<p align="center">
  <a href="https://devsponsors.github.io"><img src="https://img.shields.io/badge/DevSponsors-Verified_OSS-6366f1?style=for-the-badge&logo=github" alt="DevSponsors Verified"></a>
  <a href="https://devsponsors.github.io"><img src="https://img.shields.io/badge/Sponsor-DevSponsors_Hub-emerald?style=for-the-badge&logo=github-sponsors" alt="DevSponsors Sponsor"></a>
  <a href="https://devsponsors.github.io/mediakit.html"><img src="https://img.shields.io/badge/Infrastructure-DevSponsors_Cloud-ec4899?style=for-the-badge&logo=server" alt="DevSponsors Cloud"></a>
</p>

# Raha Project

[فارسی](README-FA.md)

Reaha project provide you micro-service based applications to use must powerfull anti-internet-sensorship platforms.

It contains serveral parts:
1. [Raha-Xray](https://github.com/Raha-Project/raha-xray) : A backend api server for run and control [xray-core](https://github.com/XTLS/Xray-core)
2. `Raha-*` : Reserved for other backend api apps
3. `Raha-Panel` (coming soon...) : A unified multi server web panel to control all servers' api backends
4. [Raha-Docs](https://github.com/Raha-Project/raha-docs) (TEMPORARY) : A simple documentation for using all parts of `Raha-Project`
5. [Raha-Project.github.io](https://raha-project.github.io) (coming soon...) : Documentation website

## Raha-Xray
* This app will control and configure all you need from `xray-core` and provide you an api.
* You can install it several servers and control it by a web pannel or application server.
* It support `SQLite` simple database and optional `MySQL` database for advanced ussage.

### Installation methods

You can use these links for installation and update to lates version.

#### 1. Install `raha-xray` using `SQLite` database

```sh
bash <(curl -Ls https://raw.githubusercontent.com/Raha-Project/Raha/master/install.sh)
```

#### 2. Install `raha-xray` with `MySQL` database

```sh
bash <(curl -Ls https://raw.githubusercontent.com/Raha-Project/Raha/master/linuxMySQL/install.sh)
```

#### 3. Install `raha-xray` + `MySQL` using `docker` and `docker-compose` (Recommended for Test)

```sh
bash <(curl -Ls https://raw.githubusercontent.com/Raha-Project/Raha/master/dockerMySQL/install.sh)
```
