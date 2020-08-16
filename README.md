# Coronavirus Information
Django open-source Coronavirus tracking app. Powerful data driven web-app, with an awesome UI. Contributions welcomed.

[![Open Source Love](https://badges.frapsoft.com/os/v1/open-source.svg?v=103)](https://github.com/ellerbrock/open-source-badges/)
[![MIT License](https://camo.githubusercontent.com/a307f74a14e41e762300323414ddef81f3d53ae2/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f6c6963656e73652f736f757263657265722d696f2f736f757263657265722d6170702e7376673f636f6c6f72423d666630303030)](https://github.com/BrianRuizy/covid-19-dashboard/blob/master/LICENSE.md)
[![Made with Pthon](https://img.shields.io/badge/Made%20with-Python-1f425f.svg)](https://www.python.org/)


![Dashboard screenshot](https://github.com/JGSangara/coronavirus-info/blob/master/core/static/assets/img/Mockup.jpeg)

## About

> Coronavirus disease (COVID-19) is an infectious disease caused by a newly discovered coronavirus.
> At this time, there are no specific vaccines or treatments for COVID-19. The best way to prevent and slow down transmission is be **well informed** about the COVID-19 virus. [who.int](https://www.who.int/health-topics/coronavirus#tab=tab_1)

## Getting Started

### Prerequisites

* Python
* Pip

### Installing

Get the project up and running locally in just 5 easy steps.

1. Create a personal [Fork](https://github.com/JGSangara/coronavirus-info.git) of this repository.

2. **Clone** the fork with HTTPS, using your local terminal to a preferred location, and **cd** into the project.

```bash
git clone https://github.com/JGSangara/coronavirus-info.git

Cloning into 'coronavirus-info'...
remote: Enumerating objects: 457, done.
remote: Counting objects: 100% (457/457), done.
remote: Compressing objects: 100% (414/414), done.
Rremote: Total 457 (delta 26), reused 447 (delta 23), pack-reused 0KiB/s
Receiving objects: 100% (457/457), 5.84 MiB | 229.00 KiB/s, done.
Resolving deltas: 100% (26/26), done.

cd coronavirus-info/
```

3. Create your virtual environment, and activate it.

```bash
virtualenv env

source env/bin/activate  # Linux/Mac
env/Scripts/activate  # Windows
```

4. Install dependencies

```bash
pip install -r requirements.txt
```

5. Run local server, and **DONE**!

```bash
python manage.py runserver

May 06, 2020 - 11:22:23
Django version 3.0.6, using settings 'core.settings'
Starting development server at http://127.0.0.1:8000/
Quit the server with CONTROL-C.
```

## Deployment

Heroku app is already configured to this repository for *automatic deploys* from any push to the **master** branch. Create a pull request containing your respective changes and wait for merge.

## Built With

* [Django](https://www.djangoproject.com/) Django is a high-level Web framework that encourages rapid development and clean, pragmatic design.
* [Plotly](https://plotly.com/) The leading front-end for ML & data science models in Python, R, and Julia.
* [Appseed](https://appseed.us/)
* [Bootstrap](https://getbootstrap.com/)

## Data Sources

* Johns Hopkins University: [CSSE](https://systems.jhu.edu/) 2019-ncov data repository, found [here](https://github.com/CSSEGISandData/COVID-19).
* Our World in Data: [OWID](https://ourworldindata.org/) Github Data repository, found [here](https://github.com/owid/covid-19-data/tree/master/public/data).
* World Health Organization: [Link to WHO](https://www.who.int/emergencies/diseases/novel-coronavirus-2019?gclid=Cj0KCQjwg8n5BRCdARIsALxKb95mm6ZjJlZs1OAyoBaQKtAkSzLVmkSgoiccOz_KnYOJw0D7cHl1-4MaAvYSEALw_wcB)

## License

[@MIT](https://github.com/JGSangara/coronavirus-info/blob/master/LICENSE.md)
