# Hi !

* 👋 I’m **Charles-Meldhine Madi Mnemoi**, **Data Analyst in apprenticeship** the day, **Backend developper** the night.
* 🌱 I’m currently contributing to [mush.vg](http://mush.vg) Eternal Twin presevation project : [eMush](https://gitlab.com/eternaltwin/mush/mush)
* 🛠️ Skills 
* Proficient :  **Python (Pandas, Scikit-Learn, Matplotlib, Plotly, Flask, Beautiful Soup, Streamlit), PL/SQL** 
* Familiar : **Git, R, VBA, SAS, API, Web Scrapping** 
* Notions : **C, C++/Qt, Java, Rust, AWS, Docker** 
* 📫 Reach me by mail (charlesmeldhine.madimnemoi@gmail.com) or LinkedIn (https://www.linkedin.com/in/madi-mnemoi-charles-meldhine-alternant-data-analyst/)

# Data Science Projects

## [OWR Predictor](https://github.com/cmmm976/OWREstimator)
[![Open in Streamlit](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://bit.ly/TASPredictor)

This is a personal project in which I created a web application to predict the best possible time for a game speedrun.

Stack : **Python 3.9, pandas, numpy, sklearn, matplotlib, seaborn, beautiful soup, flask, streamlit, joblib**

* Created a web app that estimates the best possible time of a speedrun (MAE ~ 388 seconds).
* Extracted 3800+ game runs from Speedrun.com using its API and Python.
* Scrapped 2000+ game runs from TASvideos using Beautiful Soup and Python.
* Engineering features from the time of the world records, number of runners and released year for each game put on Python, Libre Office Calc/Excel and Streamlit.
* Optimized linear, lasso, ridge, random forest, gradient boost regressor using GridSearchCV to find the best model.
* Built the web app using Streamlit.

## [YT Channel data analysis](https://github.com/cmmm976/LinearRegressionsYTChannel)

A school project in which I decided to analyse the data of my Youtube channel.

Stack : **R, Python, LateX**

* Found that likes predicts very well the number of views (R² = 0.91)
* Wrote of a report of 16 pages showing how I collected the data, which variables I chose to analyse, the methods used, the limits and problems encountered and possible improvements
* Collected 1 year of data from the Youtube Channel using Youtube API
* Analyzed 5 variables : number of views, likes, shares, comments, minutes watched
* Built univariate and multivariate linear regressions from scratch in R (least squares method)
* Analyzed the statistics from the regressions : residuals, F-statistic, R-squared to determine the quality of the models

## [TECCO trial analysis](https://github.com/cmmm976/EtudeDeCas)

A school project in which I had to analyse the result of a randomised trial to determine which treatment is better for reparing the Common Femoral Artery.

Stack : **SAS**

* Found that chirurgy is better (AOC = 0.72)
* Engineering features (One Hot Encoding)
* Compared Odd-ratios to determine which features have the most impact on healings as confusion factors
* Ran univariate and multivariate logistic regressions
* Determined which confusion factors to keep in the model with p-values and odd-ratios
* Determined the quality of the model with ROC and AUC

# Data Analysis projects

## [Lyrics Explorer](https://github.com/cmmm976/LyricsExplorator)

[![Open in Streamlit](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://bit.ly/LyricsExplorer)

A web app allowing you to compare French Hip-Hop lyrics.

Stack : **Python, Streamlit, Pandas, Plotly, Matplotlib, LyricsGenius, SQLAlchemy, MySQL, AWS RDS**

* 21723 songs collected through LyricsGenius API
* MySQL database hosted on a AWS RDS DB instance
* Nice looking charts automatically generated from data and user entries
* Web app with Streamlit

## [SpeeDons Twitch Chat Analysis](https://github.com/cmnemoi/SpeeDonsChatAnalysis)

Analysis of SpeeDons 2022 Twitch chat.
 
[Twitter thread with insights (archive)](https://github.com/cmnemoi/cmnemoi/files/9331785/ThreadReader_0_cmnemoi_1518210494095671296.pdf)

![](https://camo.githubusercontent.com/c74af89052649936e9a97f9e86f7591d968e39ea01f058c08ce43778704ea3d2/68747470733a2f2f7062732e7477696d672e636f6d2f6d656469612f465248444e53465849414d323449683f666f726d61743d6a7067266e616d653d39303078393030)

## [Projet d'analyse des données](https://github.com/cmnemoi/AnalyseDesDonn-es)
A school project in which we had to apply tools of multidimensional analysis (clustering, PCA, MCA, HCPC...) to extract insights of hobbies and german credit datasets.

Stack : **R (FactoMineR, plotly)**

* Used HCPC, PCA, MCA and clustering
* Analysed correlation circles, dendograms and factorial design plots to identify profiles in the datasets

# Other

## Open source contributions

### [Eternal Twin](https://gitlab.com/eternaltwin/etwin)

Eternal Twin is an open-source project created to preserve and recreate Motion Twin games, a 20-year old indie video game studio which released 25+ Web/Flash-based games.

#### [eMush](https://gitlab.com/eternaltwin/mush/mush)
Mush is a browser-based free-to-play multiplayer game by the French company Motion Twin released in 2013.
The plot of the game, wherein an alien entity (the titular "Mush") takes over some of the 16 people on a spaceship and the players attempt to uncover who it is, has been compared to John Carpenter's The Thing.

I am a [regular](https://gitlab.com/users/cmnemoi/activity) contributor to the project as a backend developer since July 2022.

Stack : **PHP / Symfony, Gitlab**

#### [Web scrapper](https://gitlab.com/eternaltwin/etwin/-/merge_requests/362)

I developped a web scrapper in Rust to collect players' data before sites get offline. I learned :
* Rust language
* How to do use and create unit tests
* Git : fork, commit, create branch...


### [Visions](https://github.com/dylan-profiler/visions)

`Visions` provides a set of tools for defining and using semantic data types. Used by 2 700 repositories like [pandas profiling](https://github.com/pandas-profiling/pandas-profiling), [Compressio](https://github.com/dylan-profiler/compressio) and [Bitrook](https://www.bitrook.com/).

I made a bugfix to make it usable with Pandas 1.3.x through pandas profiling.

### [srcomapi](https://github.com/blha303/srcomapi)

A Python 3 implementation of the speedrun.com REST API used by 19 repositories.

I made a [bugfix](https://github.com/blha303/srcomapi/pull/21) to make the module able to get all the results of a query if they exceed 200.

## [Base MAS Generator (private)](https://github.com/cmnemoi/BaseMASGenerator)

BASE MAS Generator is a graphic application written in Python and Qt which allows you to generate Excel dashboards from INSEE census thematic files.

Stack : [Python 3.6](https://docs.python.org/fr/3.6/), [Openpyxl 3.0.9](https://openpyxl.readthedocs.io/en/stable/), [fbs 1.0.2](https://github.com/mherrmann/fbs-tutorial), [tqdm 4.62.3](https://github.com/tqdm/tqdm), [PyQt5 5.15.2](https://doc.bccnsoft.com/docs/PyQt5/)

 * 360 dashboards generated in 3 minutes instead of an entire week
 * Learned to use PyQt to create GUI-apps
 * Use a lot of Git and Github features (Releases...)
 * First professionnal project

## [Dead Cells Speedashing Discord bot](https://github.com/cmmm976/DC_Speedashing_bot)
A discord bot for the Dead Cells Speedrunning server.

**Stack : Python 3.6+, Docker, OVH Bare Metal Cloud**

**Features :**
 
 * Runs 24/7 in a Cloud-hosted container
 * Posts new verified runs in a dedicated channel by interrogating speedrun.com API
 * Posts a runner PB through the !runner command by interrogating speedrun.com API
 * Posts a random copypasta through the !copypasta command
 * Automatically posts streamers currently playing Dead Cells
 * Posts a category world records through !wr commands
 * Posts funny reactions to Dead Cells speedruns through !casul command

**REX :**
 * Learned to use Docker containers and images
 * Re-used speedrun.com API
 * Re-learned to use Linux commands to configure and use the distant VPS for hosting the bot


## Misc
  
 * [Desktop app which predicts PvP victory rate in Mush (C++/Qt)](https://github.com/cmmm976/KillPredictor)
 * [A Livesplit Autosplitter for Nuclear Blaze](https://github.com/cmmm976/NuclearBlazeAutoSplitter)
 * [PCA charts in R](https://github.com/cmmm976/APCA)
 * [Youtube API call script](https://github.com/cmmm976/ExtractingDataFromMyYTChannel)
 * [PubMed Presence Plugin in Typescript](https://github.com/cmmm976/PubMedPreMidPresence)
 * [Terminal-based Hangman game in Python](https://github.com/cmmm976/zPendu) 

<!---
cmmm976/cmmm976 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
