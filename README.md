# Software Engineer

## Work Experience

### [LinkedIn Profile](https://www.linkedin.com/in/chris-sato/)
### **Scientist @ Capacitor Sciences Inc (_Sept 2019 - March 2024_)**
- Developed a Laboratory Information Management System (LIMS). Built with Django and Postgres to enter, store, and display experiment data.

## Portfolio Projects

### Fullstack Game Information Guide

A modern fullstack web application providing game information to [Dragon Quest Monsters - Terry's Wonderland](https://dragon-quest.org/wiki/Dragon_Quest_Monsters:_Terry%27s_Wonderland_RETRO).

#### Technologies Used

- **Backend:** [FastAPI](https://fastapi.tiangolo.com/) for an asynchronous API, using a [SQLite](https://www.sqlite.org/index.html) database.
- **Frontend:** [ReactJS](https://react.dev/) and [Radix UI](https://www.radix-ui.com/) for responsive web design.
- **MVP:** [Streamlit](https://streamlit.io/) for prototyping and easy deployment.

#### FastAPI Backend

Designed and implemented a RESTful API to handle game data. Built with FastAPI, SQLModel/SQLAlchemy, and SQLite. 

[🔗 GitHub Repo - DQMonstersDB-API](https://github.com/cmsato09/DQMonstersDB-API)

[☁️ Live API on Google Cloud Run](https://dqmonstersdb-api-743047725852.us-central1.run.app/)

<img src="assets\img\fastapi-screenshot-1.JPG" style="width: 100%;">
<img src="assets\img\fastapi-screenshot-2.JPG" style="width: 100%;">

#### ReactJS Frontend

Developed a responsive frontend with ReactJS and Radix UI to display game information details from above API.
Focused on user-friendly navigation and clear data presentation. Followed Streamlit prototype as a guide when developing. 

[🔗 GitHub Repo - DQMonstersDB-React](https://github.com/cmsato09/DQMonstersDB-React)

[☁️ Live Demo on Vercel](https://dqmonsters-db.vercel.app/)

<img src="assets\img\react-screenshot-1.JPG" style="width: 100%;">
<img src="assets\img\react-screenshot-2.JPG" style="width: 100%;">

#### Streamlit MVP

Initial prototype that laid the foundation for the ReactJS app. 

[🔗 GitHub Repo - DQMonstersDB-streamlit](https://github.com/cmsato09/DQMonstersDB-streamlit)

[☁️ MVP Demo on Streamlit Cloud](https://dqmonstersdb.streamlit.app/)

<img src="assets\img\streamlit-screenshot-1.JPG" style="width: 100%;">
<img src="assets\img\streamlit-screenshot-2.JPG" style="width: 100%;">

## Open Source Contribution

### [pybites-carbon](https://github.com/PyBites-Open-Source/pybites-carbon)
pybites-carbon is a CLI tool that interfaces with [carbon](https://carbon.now.sh/) for generating code images, using [Playwright](https://playwright.dev/) for browser automation.

My contributions include:
- Migrating the project from Selenium to Playwright, improving performance. 
- Integrating the uv package manager and updating the GitHub Actions to use it.
- Updating the README to reflect the changes. 
