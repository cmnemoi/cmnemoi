# Hi !

* 👋 I’m **Charles-Meldhine Madi Mnemoi**. I am a **Data Scientist apprentice** by day and a **Backend developper** for [eMush](https://emush.eternaltwin.org) by night.
* 🛠️ Skills 
    * Proficient in **Data Analysis (Pandas, Matplotlib, Plotly)** and **Machine Learning (Scikit-learn, PyCaret)** with **Python**
    * Familiar in **Web Scrapping (requests, BeautifulSoup)** with **Python**, **DevOps (Docker, GitLab CI, GitHub Actions)** and **testing (pytest)** 
    * Some experience in **Backend web development (APIs with Flask)**, prototyping web apps with **Streamlit** and cloud with **AWS** and **GCP**
* 📫 Reach me by [mail](mailto:charlesmeldhine.madimnemoi@gmail.com) or [Linkedin](https://www.linkedin.com/in/madi-mnemoi-charles-meldhine-data-scientist-python-machine-learning)

Below are the projects I am the most proud of. (there are many more in [my repositories](https://github.com/cmnemoi?tab=repositories&q=&type=&language=&sort=))

# Data Science Projects

## [OWR Predictor](https://github.com/cmmm976/OWREstimator)
[![Open in Streamlit](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://bit.ly/TASPredictor)

This is a personal project in which I created a web application to predict the best possible time for a game speedrun.

Stack : **Python (pandas, sklearn, matplotlib, seaborn, beautiful soup, flask, streamlit)**

* Created a web app that estimates the best possible time of a speedrun (MAE ~ 388 seconds).
* Extracted 3800+ game runs from Speedrun.com using its API and Python.
* Scrapped 2000+ game runs from TASvideos using Beautiful Soup and Python.
* Engineering features from the time of the world records, number of runners and released year for each game put on Python, Libre Office Calc/Excel and Streamlit.
* Optimized linear, lasso, ridge, random forest, gradient boost regressor using GridSearchCV to find the best model.
* Built the web app using Streamlit.

# Data Analysis projects

## [Lyrics Explorer](https://github.com/cmmm976/LyricsExplorator)

[![Open in Streamlit](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://bit.ly/LyricsExplorer)

A web app allowing you to compare French Hip-Hop lyrics.

Stack : **Python (Streamlit, Pandas, Plotly, Matplotlib, LyricsGenius, SQLAlchemy), MySQL, AWS RDS**

* 21723 songs collected through LyricsGenius API
* MySQL database hosted on a AWS RDS DB instance
* Nice looking charts automatically generated from data and user entries
* Web app with Streamlit

## [SpeeDons Twitch Chat Analysis](https://github.com/cmnemoi/SpeeDonsChatAnalysis)

Analysis of SpeeDons 2022 Twitch chat.
 
[Twitter thread with insights (archive)](https://github.com/cmnemoi/cmnemoi/files/9331785/ThreadReader_0_cmnemoi_1518210494095671296.pdf) (reached ~50 retweets)

# Other

## Open source contributions

### [Eternaltwin](https://gitlab.com/eternaltwin)

Eternaltwin is an open-source project created to preserve and recreate Motion Twin games, a 20-year old indie video game studio which released 25+ Web/Flash-based games.

I help as an eMush contributor and with DevOps contributions : [Docker](https://gitlab.com/eternaltwin/kadokadeo/kadokadeo/-/merge_requests/2) and [CI pipeline](https://gitlab.com/eternaltwin/dinocard/dinocard/-/merge_requests/4) setups for other games.

#### [eMush](https://github.com/cmnemoi/eMush/)

Stack : **PHP 8 (Symfony 6.2, PHPUnit), PostgreSQL, GitLab, Docker, GitLab CI**

eMush is an open-source remake of Mush: the greatest space-opera epic of Humanity, directly on your browser! 
I am a [regular](https://github.com/cmnemoi/eMush/commits?author=cmnemoi) contributor to the project as a backend developer / lead since July 2022.

Missions :
- feature development, bugfixes and testing
- enhancement of CI pipelines
- participation in discussions on project direction and features to be developed
- writing monthly news and patchnotes
- animating alpha tests

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

<!---
cmmm976/cmmm976 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
