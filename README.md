# Hi !

* 👋 I’m **Charles-Meldhine Madi Mnemoi**. I am a **Data Scientist** in Co-op by day and a **full-stack developper** for [eMush](https://emush.eternaltwin.org) by night.
* 🛠️ Skills 
   * proficient in **data analysis** (Pandas, Matplotlib, Seaborn, Plotly) and **machine learning** (Scikit-learn, PyTorch) with **Python** and **SQL** ;
   * familiar with **DevOps/MLOps** (Docker, GitHub Actions, GitLab CI, unit testing with pytest), **API development** (FastAPI), **GCP cloud** (Big Query, Cloud Run, Vertex AI) and **agile development methods** (Scrum, Kanban) ;
   * acculturated to **Retrieval-Augmented Generation (RAG)** with 
* 📫 Reach me by [mail](mailto:charlesmeldhine.madimnemoi@gmail.com) or [Linkedin](https://www.linkedin.com/in/madi-mnemoi-charles-meldhine-data-scientist-machine-learning-engineer-python-developer)

Below are some projects I've worked on.

## Ask NERON

A chatbot [web application](https://askneron.netlify.app/) which can answer question about [eMush](https://emush.eternaltwin.org/) with 

[![Netlify Status](https://api.netlify.com/api/v1/badges/49ec8f74-e14b-4a9d-ac0e-a3947e403301/deploy-status)](https://app.netlify.com/sites/askneron/deploys)
[![API Continuous Integration](https://github.com/cmnemoi/emush_rag/actions/workflows/continuous_integration.yaml/badge.svg)](https://github.com/cmnemoi/emush_rag/actions/workflows/continuous_integration.yaml)
[![API Continuous Delivery](https://github.com/cmnemoi/emush_rag/actions/workflows/create_github_release.yaml/badge.svg)](https://github.com/cmnemoi/emush_rag/actions/workflows/create_github_release.yaml)
[![API Code coverage](https://codecov.io/gh/cmnemoi/emush_rag/graph/badge.svg?token=FLAARH38AG)](https://codecov.io/gh/cmnemoi/emush_rag)

- [API repository](https://github.com/cmnemoi/emush_rag/)
- [Web app repository](https://github.com/cmnemoi/ask_neron_front)

## [cmnemoi-learn](https://github.com/cmnemoi/cmnemoi-learn)

[![CI Status](https://github.com/cmnemoi/cmnemoi-learn/actions/workflows/continous_integration.yaml/badge.svg?branch=main)](https://github.com/cmnemoi/cmnemoi-learn/actions/workflows/continous_integration.yaml)
[![CD Status](https://github.com/cmnemoi/cmnemoi-learn/actions/workflows/create_github_release.yaml/badge.svg?branch=main)](https://github.com/cmnemoi/cmnemoi-learn/actions/workflows/create_github_release.yaml)
[![Coverage Status](https://coveralls.io/repos/github/cmnemoi/cmnemoi-learn/badge.svg?branch=main)](https://coveralls.io/github/cmnemoi/cmnemoi-learn?branch=main) 
[![PyPI version](https://badge.fury.io/py/cmnemoi-learn.svg)](https://badge.fury.io/py/cmnemoi-learn)

`cmnemoi-learn` is a Python package which reimplements machine learning algorithms from scratch (using only `numpy`) with high quality development practices :
- unit testing with `pytest`
- code quality checking with `black`, `pylint` and `mypy`
- CI/CD pipeline with GitHub Actions to version and publish the package automatically to PyPI

## [eMush](https://github.com/cmnemoi/eMush/)

[![pipeline](https://gitlab.com/eternaltwin/mush/mush/badges/develop/pipeline.svg)](https://gitlab.com/eternaltwin/mush/mush/-/pipelines?ref=develop)
[![coverage](https://gitlab.com/eternaltwin/mush/mush/badges/develop/coverage.svg?job=api-test-develop&key_text=Backend+Coverage&key_width=130)](https://gitlab.com/eternaltwin/mush/mush/-/graphs/develop/charts)
[![discord](https://user-content.gitlab-static.net/7e2a439cd72fbe75267ad51eece2abd136f004b2/68747470733a2f2f696d672e736869656c64732e696f2f646973636f72642f363933303832303131343834363834333438)](https://discord.com/channels/693082011484684348/746873392463872071)

Stack : **PHP 8.3 (Symfony 6.4, PHPUnit, Codeception), Vue.js 3, PostgreSQL, GitLab, Docker, GitLab CI**

[eMush](https://emush.eternaltwin.org/) is an open source remake of Mush: the greatest space opera epic of Humanity, directly on your browser! 

I am a full-stack developer for the project [since July 2022](https://github.com/cmnemoi/eMush/commits?author=cmnemoi).

KPIs : 
- 1500+ users (100+ daily)
- contribution to 100 000+ lines of code

Missions :
- feature development, bugfixes and testing
- enhancement of CI pipelines
- implementing good practices (TDD, BDD, Clean Architecture)
- participation in discussions on project direction and features to be developed
- writing monthly news and patchnotes
- animating alpha tests

I've done the projects below when I was starting in Data Science and software engineering, they deserve a reboot now...

## [Predicting NYC Taxi Fare](https://github.com/cmnemoi/NYCTaxiFareLPSID)

[![Continous Integration](https://github.com/cmnemoi/NYCTaxiFareLPSID/actions/workflows/ci.yaml/badge.svg)](https://github.com/cmnemoi/NYCTaxiFareLPSID/actions/workflows/ci.yaml) 
[![Open in Streamlit](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://cmnemoi-nyc-taxi-fare.streamlit.app/)

Data Science project of Lille's Bachelor of Economics, which consists of participating in the Kaggle competition [New York City Taxi Fare Prediction](https://www.kaggle.com/c/new-york-city-taxi-fare-prediction).

* Developed a web application that estimates the price of a ride within a $1.4 range
* Cleaned and analyzed a dataset with 340,000+ rows to remove outliers and noise from data with normalization
* Created new variables based on ride duration and destinations
* Built the web application using Streamlit
* Quality "CI" pipeline with git hooks and Github Actions (lint with Ruff, test with Pytest)

<!---
cmmm976/cmmm976 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
