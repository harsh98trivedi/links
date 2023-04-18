# [Links](https://github.com/harsh98trivedi/Links)

A Beautiful Jekyll Theme For Links

![Links](https://raw.githubusercontent.com/harsh98trivedi/links/master/assets/images/links.jpg)

### Screenshot
![Screenshot](https://i.imgur.com/9uJrd9k.png)

### Checkout the [Demo Here](https://harsh98trivedi.github.io/links)

<a href="https://youtu.be/2J2_2gsCjtk"><img src="https://i.imgur.com/s7vdI7T.png"/></a>

---

## Installation 

### System Requirements
- [Ruby](https://www.ruby-lang.org/en/)
- [Jekyll](https://jekyllrb.com/) (You can read **What is Jekyll [here](https://github.com/jekyll/jekyll#jekyll)**)
- [NPM](https://npmjs.com/)

### Up and Running
- Fork this [Repository](https://github.com/harsh98trivedi/Links)<br>
- Edit the **_config.yml** in the **config** directory
- Fill the available details accordingly
- Commit the changes

> Links is also [**Netlify**](https://www.netlify.com/) ready. ✅ <br>
You can checkout the netlify version up and running [**here**](https://htlink.netlify.app/).

### Want to set this up **locally**?
- Clone this **Repository** using **Git**<br>
    > Kindly Change [USERNAME] with your own GitHub UserName
``` git
git clone https://github.com/[USERNAME]/Links
```
- Go to the project directory
```bash
cd links
```
- Install **Links** with **npm**
```bash
npm install
```
- Run the **Jekyll** server
```bash
bundle exec jekyll serve --config config/_config.yml
```
- Open the browser and go to **http://localhost:4000**. You should see your **links** site up and running!
---

### Want to set this up on **Docker**?
View repository on [Docker Hub](https://hub.docker.com/r/harsh98trivedi/links)

We have a premade **Docker Compose** file for you to get started, all you need to do is:
- Edit the **_config.yml** in the **config** directory
- Fill in the available details accordingly
- Run the **Docker** container using **Docker Compose**:
```bash
docker compose up -d
```
- Open the browser and go to **http://localhost:4000**. You should see your **links** site up and running!

> Note: Whenever you make changes to the **_config.yml** file, you need to restart the container for the changes to take effect. You can do so by running:
```bash
docker restart links
```
If you wish to build the image yourself, uncomment the **build** line in the **docker-compose.yml** file and comment out the **image** line. Then run the following command:
```bash
docker compose build
```
Then run the container using:
```bash
docker compose up -d
```
---

## Content Credits
- [Cover Image](https://source.unsplash.com/)
- [Font Awesome](https://fontawesome.com/)
- [Poppins Font](https://fonts.google.com/specimen/Poppins)
- [Images.weserv.nl](https://images.weserv.nl/)

---

Special Thanks to [Rohit Motwani](https://github.com/rohittm) for configuring **Nodemon** and making it up and running with his geeky mind, [Hitanshu Sahu](https://www.behance.net/phantomcluster) for improving the design with his awesome UI skills and [Nelson Dane](https://github.com/NelsonDane) for making this compatible with [Docker](https://docker.com/)

### License

The contents of this repository are licensed under the [GNU General Public License v2.0](https://github.com/harsh98trivedi/Links/blob/master/LICENSE)

[![Netlify Status](https://api.netlify.com/api/v1/badges/2a02bd54-cdfc-4a4f-8ab6-59e45edddad8/deploy-status)](https://app.netlify.com/sites/htlink/deploys)
![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)
