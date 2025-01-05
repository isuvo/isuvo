<h1 align="center">Hi 👋, I'm Shuvo</h1>
<h3 align="center">I am a full stack developer and an AI ML Researcher</h3> 
  
# Image Management

docker build -t resumeapp:v1.0 . # Builds an image from a Dockerfile in current directory, tag it with resumeapp:v1.0
docker images # Lists all available images
docker pull resumeapp:v1.0 # Pulls the resumeapp:v1.0 image from a registry
docker push your-dockerhub-username/resumeapp:v1.0 # Pushes the resumeapp:v1.0 image to your Docker Hub (replace your-dockerhub-username)
docker rmi resumeapp:v1.0 # Removes the resumeapp:v1.0 image
docker image prune # Removes unused images

# Container Management

docker run -d --name resumeapp-container -p 8080:80 resumeapp:v1.0 # Creates and starts a container in detached mode, names it resumeapp-container, maps port 8080 to port 80 inside the container, based on resumeapp:v1.0 image
docker start resumeapp-container # Starts the existing resumeapp-container
docker stop resumeapp-container # Stops the running resumeapp-container
docker restart resumeapp-container # Restarts the resumeapp-container
docker pause resumeapp-container # Pauses the running resumeapp-container
docker unpause resumeapp-container # Unpauses the paused resumeapp-container
docker rm resumeapp-container # Removes the stopped resumeapp-container
docker ps # Lists all running containers
docker ps -a # Lists all containers
docker container prune # Removes stopped containers

# Container Interaction

docker exec -it resumeapp-container /bin/bash # Executes /bin/bash inside a running container in interactive mode
docker logs resumeapp-container # Fetches the logs of the resumeapp-container
docker cp resumeapp-container:/app/data.txt ./data.txt # Copies data.txt from the container to the current directory
docker port resumeapp-container # Lists port mappings for the resumeapp-container

# Docker System Information

docker info # Displays system-wide information
docker version # Displays Docker version

# Docker Network
# Assuming a default bridge network, commands remain generic
docker network ls # List Docker networks
docker network create my-network # Create a Docker network named my-network
docker network connect my-network resumeapp-container # Connect a container to my-network
docker network disconnect my-network resumeapp-container # Disconnect a container from my-network
docker network rm my-network # Remove a Docker network named my-network

# Docker Volume
# Assuming a named volume called resumeapp-data
docker volume ls # List Docker volumes
docker volume create resumeapp-data # Create a Docker volume named resumeapp-data
docker volume rm resumeapp-data # Remove a Docker volume named resumeapp-data

# Docker Compose
# Assuming you have a docker-compose.yml file defined for your app
docker compose up # Builds, creates and starts containers defined in docker-compose.yml
docker compose down # Stops and removes containers and networks defined in docker-compose.yml
docker compose ps # Lists containers created by docker-compose
docker compose build # Builds or rebuilds service images in docker-compose.yml
docker compose logs # View output from containers started by docker-compose

# Docker login
docker login # Log in to a Docker registry
docker logout # Log out from a Docker registry
enthusiast</h3>

<p align="left"> <img src="https://komarev.com/ghpvc/?username=isuvo&label=Profile%20views&color=0e75b6&style=flat" alt="isuvo" /> </p>

<p align="left"> <a href="https://github.com/ryo-ma/github-profile-trophy"><img src="https://github-profile-trophy.vercel.app/?username=isuvo" alt="isuvo" /></a> </p>

<p align="left"> <a href="https://twitter.com/suvobgd" target="blank"><img src="https://img.shields.io/twitter/follow/suvobgd?logo=twitter&style=for-the-badge" alt="suvobgd" /></a> </p>

- 🔭 I’m currently working on **Blockchain technology and Pyhton**

- 🌱 I’m currently learning **Bert: Transformer models to do supervised learning and improve performance**

- 👯 Happy to collaborate on **AI automatic code analysis and refactoring**

- 🤝 Appreciate help with **ML and Deep Learning**

- 👨‍💻 All of my projects are available at [https://github.com/isuvo](https://github.com/isuvo)

- 📝 I occasionally write articles on [https://suvobgd.wordpress.com/](https://suvobgd.wordpress.com/)

- 💬 you can ask me about **.NET, Azure DevOps, MSSQL Server, JS frameworks, OWASP, Migration, System architecture and design**

- 📫 Reach me **isuvo@outlook.com**

- 📄 Know about my experiences [https://isuvo.github.io/resume/](https://isuvo.github.io/resume/)

- ⚡ Fun fact **why so serious!**

### Blogs posts
<!-- BLOG-POST-LIST:START -->
<!-- BLOG-POST-LIST:END -->

<h3 align="left">Connect with me:</h3>
<p align="left">
<a href="https://twitter.com/suvobgd" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/twitter.svg" alt="suvobgd" height="30" width="40" /></a>
<a href="https://linkedin.com/in/isuvo" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="isuvo" height="30" width="40" /></a>
<a href="https://medium.com/@isuvo" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/medium.svg" alt="@isuvo" height="30" width="40" /></a>

</p>

<h3 align="left">Languages and Tools:</h3>
<p align="left"> <a href="https://angular.io" target="_blank" rel="noreferrer"> <img src="https://angular.io/assets/images/logos/angular/angular.svg" alt="angular" width="40" height="40"/> </a> <a href="https://angular.io" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/angularjs/angularjs-original-wordmark.svg" alt="angularjs" width="40" height="40"/> </a> <a href="https://aws.amazon.com" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/amazonwebservices/amazonwebservices-original-wordmark.svg" alt="aws" width="40" height="40"/> </a> <a href="https://azure.microsoft.com/en-in/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/microsoft_azure/microsoft_azure-icon.svg" alt="azure" width="40" height="40"/> </a> <a href="https://getbootstrap.com" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/bootstrap/bootstrap-plain-wordmark.svg" alt="bootstrap" width="40" height="40"/> </a> <a href="https://www.chartjs.org" target="_blank" rel="noreferrer"> <img src="https://www.chartjs.org/media/logo-title.svg" alt="chartjs" width="40" height="40"/> </a> <a href="https://www.w3schools.com/cs/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/csharp/csharp-original.svg" alt="csharp" width="40" height="40"/> </a> <a href="https://www.w3schools.com/css/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" alt="css3" width="40" height="40"/> </a> <a href="https://d3js.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/d3js/d3js-original.svg" alt="d3js" width="40" height="40"/> </a> <a href="https://www.docker.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original-wordmark.svg" alt="docker" width="40" height="40"/> </a> <a href="https://dotnet.microsoft.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/dot-net/dot-net-original-wordmark.svg" alt="dotnet" width="40" height="40"/> </a> <a href="https://git-scm.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="git" width="40" height="40"/> </a> <a href="https://www.java.com" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg" alt="java" width="40" height="40"/> </a> <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="javascript" width="40" height="40"/> </a> <a href="https://www.linux.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/linux/linux-original.svg" alt="linux" width="40" height="40"/> </a> <a href="https://www.mongodb.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mongodb/mongodb-original-wordmark.svg" alt="mongodb" width="40" height="40"/> </a> <a href="https://www.microsoft.com/en-us/sql-server" target="_blank" rel="noreferrer"> <img src="https://www.svgrepo.com/show/303229/microsoft-sql-server-logo.svg" alt="mssql" width="40" height="40"/> </a> <a href="https://www.mysql.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg" alt="mysql" width="40" height="40"/> </a> <a href="https://pandas.pydata.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/2ae2a900d2f041da66e950e4d48052658d850630/icons/pandas/pandas-original.svg" alt="pandas" width="40" height="40"/> </a> <a href="https://www.postgresql.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/postgresql/postgresql-original-wordmark.svg" alt="postgresql" width="40" height="40"/> </a> <a href="https://postman.com" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/getpostman/getpostman-icon.svg" alt="postman" width="40" height="40"/> </a> <a href="https://www.python.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/> </a> <a href="https://www.rabbitmq.com" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/rabbitmq/rabbitmq-icon.svg" alt="rabbitMQ" width="40" height="40"/> </a> <a href="https://reactjs.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original-wordmark.svg" alt="react" width="40" height="40"/> </a> <a href="https://scikit-learn.org/" target="_blank" rel="noreferrer"> <img src="https://upload.wikimedia.org/wikipedia/commons/0/05/Scikit_learn_logo_small.svg" alt="scikit_learn" width="40" height="40"/> </a> <a href="https://seaborn.pydata.org/" target="_blank" rel="noreferrer"> <img src="https://seaborn.pydata.org/_images/logo-mark-lightbg.svg" alt="seaborn" width="40" height="40"/> </a> <a href="https://www.selenium.dev" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/detain/svg-logos/780f25886640cef088af994181646db2f6b1a3f8/svg/selenium-logo.svg" alt="selenium" width="40" height="40"/> </a> <a href="https://www.sqlite.org/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/sqlite/sqlite-icon.svg" alt="sqlite" width="40" height="40"/> </a> <a href="https://www.typescriptlang.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/typescript/typescript-original.svg" alt="typescript" width="40" height="40"/> </a> <a href="https://vuejs.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/vuejs/vuejs-original-wordmark.svg" alt="vuejs" width="40" height="40"/> </a> <a href="https://zapier.com" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/zapier/zapier-icon.svg" alt="zapier" width="40" height="40"/> </a> </p>

<p><img align="left" src="https://github-readme-stats.vercel.app/api/top-langs?username=isuvo&show_icons=true&locale=en&layout=compact" alt="isuvo" /></p>

<p>&nbsp;<img align="center" src="https://github-readme-stats.vercel.app/api?username=isuvo&show_icons=true&locale=en" alt="isuvo" /></p>

<p><img align="center" src="https://github-readme-streak-stats.herokuapp.com/?user=isuvo&" alt="isuvo" /></p>
