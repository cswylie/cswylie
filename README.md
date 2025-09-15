## Hello there 👋

<!--
**cswylie/cswylie** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

Preferred contact: `christianswylie@gmail.com`

[Website](https://christianswylie.com/): `https://christianswylie.com/`

[LinkedIn](https://www.linkedin.com/in/christian-wylie-593249265/): `https://www.linkedin.com/in/christian-wylie`

[Personal Portfolio](https://github.com/cswylie/personal_portfolio): `https://github.com/cswylie/personal_portfolio`

## About Me:
* **Computer Science B.S., University of California, Santa Cruz (September 2021 – March 2025)**
* **ResNet (Residential Networking) Technician (September 2024 - March 2025)**: Provided technical and networking support for on campus residential students, resolving network or OS issues, and configured student-owned devices.
* I've been played trumpet for about 11 years, and I've been playing guitar for about 2 years.
    * I spend a lot of my free time practicing and writing music.
* **AWS Certified Cloud Practitioner** (Until 2028).

## Featured Projects:

### [SkillSwapper](https://github.com/cswylie/SkillSwapper)
This is a full stack web application developed by myself and 5 other UCSC undergraduate students as a project for CSE115a: Introduction to Software Development. It is a web platform that connects people in their communities by exchanging one’s skills and time for another’s without the exchange of monetary currency. There is a relevant README in the project repository, and there are also instructions on how to run and use the web application. I specifically helped develop a lot of the backend, which includes:
* Testing Suite
* Authentifciation Services
  * Including Secure Account Authentification Middleware 
* Firebase Database Management
* Account Services and Endpoints
  * Using TSOA to create REST APIs  
* Creating and maintaining cookies for users.
#### Technologies Used:
ReactJS | JavaScript | TypeScript | HTML/CSS | NodeJS | ExpressJS | Firebase | Jest

### [Portfolio Website](https://github.com/cswylie/website)
This is my portfolio website that has my Resume and a little bit of my photography and artwork. It was made using React and Vite, and was hosted using Netlify. The UI of the website was made using Tailwind CSS and TypeScript.
#### Technologies Used:
ReactJS | JavaScript | TypeScript | HTML | Tailwind CSS | Vite

### [ChordIdentifier](https://github.com/cswylie/ChordIdentifier) 
This is a small full stack web application designed to give the user a breakdown of what chords a list of notes are in. It makes use of the tonaljs library to return the list of chords that the notes are in.
#### Technologies Used:
ReactJS | JavaScript | TypeScript | HTML | NodeJS | ExpressJS | Vite


### [Strum](https://github.com/cswylie/Strum) 
This is an ongoing project designed to develop a small specialized AI chatbot to help with music production. I've opted to calling it **Strum**. I often have to look up a lot of specific information when it comes to recording music in DAWs, so this will streamline the process to make accessing that information a lot easier.
#### How does it work?:
It's run through a Docker container and hosts the pipeline locally. The chatbot makes use of Retrieval-Augmented Generation, or RAG, to search a predefined database of knowledge, mostly on music production, generating a response derived specifically from that data rather than a very well educated guess, like a normal pretrained LLM model. Queries are embedded into a vector, which is then compared against the data set (also turned into vectors), which then will find the highest matching documents relevent to the query. The program will then pass along that context (data) to the Open AI gpt-oss-20b LLM model along with the query, ensuring that the model can answer appropriately. The query can be accessed from the endpoints exposed by Fast API.
#### Technologies Used:
Python | Retrieval-Augmented Generation (RAG) | FastAPI | Docker

