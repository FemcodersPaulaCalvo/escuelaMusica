#  🎹 Toquen el DOM 🎶


### _Aprendiendo a hacer ruido_ 📀 Music School
<br>

## 📋 Description

Welcome to the new website project for the _Aprendiendo a hacer ruido_ online music school where technology teams up with your musical creativity. This web has a feature that allows users to learn and practise playing some instruments online. By clicking or pressing keys users can enjoy playing music to their heart's content, and in a real way because the online instruments reproduce the real sounds of the instruments.    
<br>


## 🔁 Flowchart
 ![Flowchart](/assets/images/Diagrama%20de%20flujo.PNG)

<br>

## 📄 Stages and Pages

- Main Page  
![screenshot of main page](/assets/images/1.MAIN.png)
- Go to these pages from here: 


- MARIMBA icon →  Play the  MARIMBA online 
![screenshot of main page](/assets/images/2.PLAY_MARIMBA.png)


- PIANO (or DRUMS) icon →  Play the PIANO (and the DRUMS) --UNDER CONSTRUCTION 🏗️ 🏗
![screenshot pages in process](/assets/images/3.PIANO(DRUMS)_IN-PROGRESS.png)


- MARIMBA button →  Some background info and a tutorial to learn to play the MARIMBA  ![screenshot pages in process](/assets/images/4.MARIMBA_INFO.png)  
<br>
 

## 🛠 Tech Tools

- **HTML 5** 
- **CSS 3** 
- **JavaScript**
- **Git and GitHub**
- **Docker**
- **Figma**
<br>
<br>

## 🐳 Installation

#### _Previous requirements_

Install [Docker](https://docs.docker.com/desktop/)⤵


#### _Execute the project with Docker_

◽ Step 1: Open docker terminal
```docker
docker 
```
 
◽ Step 2: This command builds a Docker image from the Dockerfile of the project.
```docker
docker build -t escuela-musica .
```

◽ Step 3: This command runs a container from that newly created image.
```docker
docker run -d -p 8080:80 escuela-musica
```
<br>

## 👩‍💻 Authors

- [Mary Kenny](https://github.com/marykenny123)
- [Paula Calvo García](https://github.com/PCalvoGarcia)
- [Paola Andrea Pinilla Landazábal](https://github.com/PaolaAPL17)
- [Lara Pla Moreno](https://github.com/Lizar22)


## APPEND: 18TH JULY - DOCKER EXERCISE, NEW DOCKERFILE "Dockerfile2" ADDED -- RUN WITH COMMAND docker build -f Dockerfile2 -t docker-exercise/add-new-dockerfile2 .