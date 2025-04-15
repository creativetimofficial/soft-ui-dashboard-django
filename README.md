# [Soft UI Dashboard Django](https://www.creative-tim.com/product/soft-ui-dashboard-django) [![Tweet](https://img.shields.io/twitter/url/http/shields.io.svg?style=social&logo=twitter)](https://twitter.com/home?status=Material%20Dashboard,%20a%20free%20Material%20Bootstrap%204%20Admin%20Template%20%E2%9D%A4%EF%B8%8F%20https%3A//bit.ly/2Lyat1Y%20%23bootstrap%20%23material%20%23design%20%23developers%20%23freebie%20%20via%20%40CreativeTim)

 ![version](https://img.shields.io/badge/version-1.0.0-blue.svg) [![GitHub issues open](https://img.shields.io/github/issues/creativetimofficial/soft-ui-dashboard-django.svg?maxAge=2592000)](https://github.com/creativetimofficial/soft-ui-dashboard-django/issues?q=is%3Aopen+is%3Aissue) [![GitHub issues closed](https://img.shields.io/github/issues-closed-raw/creativetimofficial/soft-ui-dashboard-django.svg?maxAge=2592000)](https://github.com/creativetimofficial/soft-ui-dashboard-django/issues?q=is%3Aissue+is%3Aclosed) [![Join the chat at https://gitter.im/NIT-dgp/General](https://badges.gitter.im/NIT-dgp/General.svg)](https://gitter.im/creative-tim-general/Lobby) [![Chat](https://img.shields.io/badge/chat-on%20discord-7289da.svg)](https://discord.gg/E4aHAQy)

Open-source **[Django Template](https://www.creative-tim.com/templates/django)** crafted on top of **Soft UI Dashboard**, a modern Bootstrap 5 design. Start your development with a modern Bootstrap 5 Admin template for Django. Soft UI Dashboard is built with over 70 individual components, giving you the freedom of choosing and combining. If you want to code faster, with a smooth workflow, then you should try this template carefully developed with Django, a well-known Python Framework.

> NOTE: Starter provided in partnership with [App-Generator](https://app-generator.dev/), an open-source platform for developers

<br />

## Features: 

- Simple, Easy-to-Extend Codebase
- Soft UI Dashboard Design Integration
- [Dynamic DataTables](https://django-soft-dash.onrender.com/dynamic-dt/product/) - [Generate Data Tables with Django](https://app-generator.dev/docs/developer-tools/dynamic-datatables.html) (no coding)
- [Dynamic API](https://django-soft-dash.onrender.com/api/product/) - [Generate API Endpoints with Django](https://app-generator.dev/docs/developer-tools/dynamic-api.html) (no coding)
- [Charts](https://django-soft-dash.onrender.com/charts/) via ApexCharts.js 
- Session-based Authentication, Password recovery
- DB Persistence: SQLite (default), can be used with MySql, PgSql
- Docker 
- CI/CD integration for [Render](https://app-generator.dev/docs/deployment/render/index.html) 

<br />

[![Django Soft UI Dashboard - Seed project generated by AppSeed.](https://s3.amazonaws.com/creativetim_bucket/products/541/original/soft-ui-dashboard-django.jpg)](https://www.creative-tim.com/product/soft-ui-dashboard-django)

<br />

## Table of Contents

* [Versions](#versions)
* [Demo](#demo)
* [Quick Start](#quick-start)
* [Documentation](#documentation)
* [File Structure](#file-structure)
* [Browser Support](#browser-support)
* [Resources](#resources)
* [Reporting Issues](#reporting-issues)
* [Technical Support or Questions](#technical-support-or-questions)
* [Licensing](#licensing)
* [Useful Links](#useful-links)

<br />

## Demo

> To authenticate use the default credentials ***test / PaSS_123*** or create a new user on the **registration page**.

- **Soft UI Dashboard Django** [Login Page](https://www.creative-tim.com/live/soft-ui-dashboard-django)

<br />

## Quick start

> 👉 Download the code  

```bash
$ git clone https://github.com/creativetimofficial/soft-ui-dashboard-django.git
$ cd soft-ui-dashboard-django
```

<br />

> 👉 Install modules via `VENV`  

```bash
$ virtualenv env
$ source env/bin/activate
$ pip install -r requirements.txt
```

<br />

> 👉 Set Up Database

```bash
$ python manage.py makemigrations
$ python manage.py migrate
```

<br />

> 👉 Create the Superuser

```bash
$ python manage.py createsuperuser
```

<br />

> 👉 Start the app

```bash
$ python manage.py runserver
```

At this point, the app runs at `http://127.0.0.1:8000/`. 

<br />

## Documentation

The documentation for the **Soft UI Dashboard Django** is hosted at our [website](https://app-generator.dev/docs/products/django/soft-ui-dashboard/index.html).

<br />

## Codebase structure

The project is coded using a simple and intuitive structure presented below:

```bash
< PROJECT ROOT >
   |
   |-- config/                            
   |    |-- settings.py                  # Project Configuration  
   |    |-- urls.py                      # Project Routing
   |
   |-- apps/
   |    |-- charts                        
   |    |-- dyn_api                      # APP Routing
   |    |-- dyn_dt                       # APP Models 
   |    |-- pages                        # Tests  
   |     
   |-- requirements.txt                  # Project Dependencies
   |
   |-- env.sample                        # ENV Configuration (default values)
   |-- manage.py                         # Start the app - Django default start script
   |
   |-- ************************************************************************
```

<br />

## Deploy on [Render](https://render.com/)

- Create a Blueprint instance
  - Go to https://dashboard.render.com/blueprints this link.
- Click `New Blueprint Instance` button.
- Connect your `repo` which you want to deploy.
- Fill the `Service Group Name` and click on `Update Existing Resources` button.
- After that your deployment will start automatically.

At this point, the product should be LIVE.

<br />

## Reporting Issues

We use GitHub Issues as the official bug tracker for the **Soft UI Dashboard Django**. Here are some advices for our users that want to report an issue:

1. Make sure that you are using the latest version of the **Soft UI Dashboard Django**. Check the CHANGELOG from your dashboard on our [website](https://www.creative-tim.com/).
2. Providing us reproducible steps for the issue will shorten the time it takes for it to be fixed.
3. Some issues may be browser-specific, so specifying in what browser you encountered the issue might help.

<br />

## Support

Being a product that is actively supported and improved, feel free to contact us using these funnels: 

- **Creative-Tim** [Discord](https://discord.gg/haJ7ErsNY3) Server - for general product assistance and UI/UX
- **App Generator** [Discord](https://discord.gg/fZC6hup) Server - for **Django specific questions** and assistance. 

<br />

## Licensing

- Copyright 2019 - present [Creative Tim](https://www.creative-tim.com/)
- Licensed under [Creative Tim EULA](https://www.creative-tim.com/license)

<br />

## Useful Links

- [More products](https://www.creative-tim.com/bootstrap-themes) from Creative Tim
- [Tutorials](https://www.youtube.com/channel/UCVyTG4sCw-rOvB9oHkzZD1w)
- [Freebies](https://www.creative-tim.com/bootstrap-themes/free) from Creative Tim
- [Affiliate Program](https://www.creative-tim.com/affiliates/new) (earn money)

<br />

## Social Media

- Twitter: <https://twitter.com/CreativeTim>
- Facebook: <https://www.facebook.com/CreativeTim>
- Dribbble: <https://dribbble.com/creativetim>
- Instagram: <https://www.instagram.com/CreativeTimOfficial>

<br />

## [PRO Version](https://www.creative-tim.com/product/soft-ui-dashboard-pro-django)   

This design is a pixel-perfect [Bootstrap 5](https://www.admin-dashboards.com/bootstrap-5-templates/) Dashboard with a fresh, new design concept. `Soft UI Dashboard PRO` is built with over 300 frontend individual elements, like buttons, inputs, navbars, nav tabs, cards, or alerts, giving you the freedom of choosing and combining.

> Features: 

- Simple, Easy-to-Extend Codebase
- Soft UI Dashboard Design - PRO Version Integration
- [Dynamic DataTables](https://django-soft-dash-pro.onrender.com/dynamic-dt/product/) - [Generate Data Tables with Django](https://app-generator.dev/docs/developer-tools/dynamic-datatables.html) (no coding)
- [Dynamic API](https://django-soft-dash-pro.onrender.com/api/product/) - [Generate API Endpoints with Django](https://app-generator.dev/docs/developer-tools/dynamic-api.html) (no coding)
- [Charts](https://django-soft-dash-pro.onrender.com/charts/) via ApexCharts.js
- Media Files Manager
- Async Tasks (celery)
- [CLI Tools for Django](https://app-generator.dev/docs/developer-tools/django-cli/index.html) - migrate DB, manage GIT commits and   
- Session-based Authentication, Password recovery
- DB Persistence: SQLite (default), can be used with MySql, PgSql
- Docker 
- CI/CD integration for [Render](https://app-generator.dev/docs/deployment/render/index.html) 

<br />

[![Django - Soft UI Dashboard PRO (premium starter by AppSeed & Creative-Tim](https://user-images.githubusercontent.com/51070104/215022735-dec8e82e-ea91-4494-a521-db421e8637be.png)](https://www.creative-tim.com/product/soft-ui-dashboard-pro-django)

<br />

---
[Soft UI Dashboard - Django Template](https://www.creative-tim.com/product/soft-ui-dashboard-django) - Provided by [Creative Tim](https://www.creative-tim.com/) and [App-Generator](https://app-generator.dev/).
