# IOI Gamification Repository

[![Open Shiny App](https://img.shields.io/badge/Shiny-Live%20App-1f77b4?logo=r)](https://adingor.shinyapps.io/ioi-gamification-repository/)
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)
![Topic: Teaching](https://img.shields.io/badge/topic-teaching-blue)

A curated repository of games and gamification resources for teaching **Industrial Organization Engineering (IOI)**.

This project provides a structured database of educational games that can be used in courses related to industrial organization, operations management, project management, supply chains, lean management, and related areas.

The repository also includes a **Shiny web application** that allows users to explore the database using filters such as subject, keywords, language, and other attributes.

The app is deployed and can be freely used here: https://adingor.shinyapps.io/ioi-gamification-repository/

There is also a youtube video introducing the repository here: https://www.youtube.com/watch?v=Bgrrctx4IsA 


## Purpose of the project

Gamification has proven to be an effective tool to enhance student engagement and promote active learning. However, information about existing educational games is often scattered and difficult to locate.

This repository aims to:

- collect and organize gamification resources relevant to **Industrial Organization Engineering**
- facilitate their discovery and use by instructors
- support the integration of **active learning methodologies**
- encourage collaboration and expansion of the repository by the academic community


## Shiny Application

The repository includes a **Shiny application** that allows users to browse and search the database interactively.

Features include:

- search by **keywords**
- filter by **subject**
- filter by **language**
- filter by **registration requirement**
- access to **game descriptions and links**
- embedded **multimedia resources when available**


## GPT Assistant for Gamification

In addition to the repository, a **custom GPT assistant** has been developed using this database and additional resources related to gamification in IOI.

The assistant can help instructors:

- find suitable games for specific topics
- design gamification activities
- explore teaching ideas based on active learning

You can try it here:

https://chatgpt.com/g/g-H7fZGRAt5-aprendizaje-interactivo-en-ing-de-organizacion


## Origin of the Database

The original database of games and its methodology are described in the following article:

https://epsapps.udg.edu/cioblog/index.php/2019/12/13/repositorio-de-juegos-para-el-aula/

This repository builds on that work by:

- structuring the dataset
- improving the metadata
- providing an interactive search interface
- enabling collaborative development through GitHub


## Project Development

This application has been developed by the **Teaching Coordination Committee of ADINGOR**:

https://adingor.net/comision-coordinacion-docente/

The work builds upon a **Bachelor's Thesis developed within the INSISOC research group** at the **University of Valladolid**:

https://www.insisoc.uva.es/


## Repository structure

- **app.R** – Main Shiny application.
- **data_clean/** – Cleaned datasets used by the application.
  - **juegos.csv** – Core dataset containing the catalogue of gamification games.
  - **juegos_asignaturas.csv** – Links games with IOI subjects.
  - **juegos_keywords.csv** – Links games with thematic keywords.
  - **fichas/** – Advanced teaching sheets in PDF format for selected games.
- **README.md** – Documentation of the project.
- **LICENSE** – MIT open-source license.


## Contributing

Contributions are welcome.

The repository can be expanded with:

- new games
- improved metadata
- additional keywords
- teaching materials
- improvements to the Shiny application

You can contribute by:

- opening an **issue**
- submitting a **pull request**


## Contact

For suggestions, corrections, or collaboration proposals:

**José Manuel Galán Ordax**  
https://sites.google.com/site/josemagalan/home
or any other member of the **Teaching Coordination Committee of ADINGOR**: https://adingor.net/comision-coordinacion-docente/

You can also contribute directly via GitHub by submitting pull requests.

---

## License

This project is distributed under the **MIT License**.

See the LICENSE file for details.
