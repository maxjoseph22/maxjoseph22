## 👋 Hi there, I'm Max! 👋

I'm a Software Engineer living in London with a unique combination of technical skills and established financial experience. I recently completed an intensive Full Stack Development Bootcamp at Makers, where I developed my knowledge in JavaScript, Python, React.js, Node.js, MongoDB, PostgreSQL, HTML, and CSS. 

I'm currently building a web-application for a popular content-creator on Instagram with over 7 million followers. For 12 years they have been taking photos and videos of all the different dogs in New York city and have uploaded nearly 10,000 posts garnering millions of likes. This considerable amount of data was being severely under-leveraged by Instagram's lack of native search and sorting capabilities. If a user wanted to find a dog with a specific name or of a certain breed, they were limited to having to scroll through every post until they got lucky (or got bored and gave up!). There were a number of questions that both the content-creator and their followers wanted to know the answers to: which were the most popular breeds and names? Which breeds had never been featured? Which dogs had the most likes? The list went on. All of these were unanswerable without an organised database and bespoke application, and so work began.

The captions of each post contained information about one, or sometimes multiple, dog/s - their name, age, breed, location, sex and personality. The problem was that data could not be extracted using the traditional techniques of string/array/dictionary manipulation that I was familiar with. This was due to the unpredictable and unique structure of each paragraph of text. To get around this, I leveraged the use of OpenAI's API and created a bespoke prompt, through much trial and error, which created a JSON object from a CSV file containing all of the post data. I then built custom repositories using Python to input the JSON objects one by one into my SQL database, which I connected using the Pyscopg SQL database adapter. 

Once I'd populated my database with nearly 10,000 dogs it was time to have some fun. I connected a Flask web-app framework and started building! I wanted users to be able to search for dogs easily, each result would show a preview of the Instagram post and redirect you there if you clicked through. I created leaderboards of breeds, names and likes popularity as well as highlighting which breeds were the rarest or never seen before. I also used the location data to create and embed a wordlwide map of all of the dog using Google Maps. 

My most recent updates included incorporating Auth0, a cloud-based authentication and authorisation platform which I synced with a local table of users in my database. Users are able to securely log in to the site and add dogs to their favourites list, which is saved in the database. The features I'm working on next are:
- Request forms for users to request certain breeds to be featured
- Creating a fantasy football style game where users can create a team of dogs, each dog priced based using equations that factor in their various attributes (breed, number of likes and comments, rarity etc.)



<!--
**maxjoseph22/maxjoseph22** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

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

## 🔧 Technical Skills 🔧

Front-End Development
- React.js
- HTML
- CSS

Back-End Development
- JavaScript
- Node.js
- Express.js
- Python
- SQL (PostgreSQL, MySQL)
- NoSQL (MongoDB)
- Flask
  
Testing and QA Tools
- Pytest
- Jest
- Vitest
  
Tools and Practices
- Git
- GitHub
- Docker
- Command Line
- VS Code
- Agile
- Test-Driven Development (TDD)
- Pair Programming

## 🔭 Projects 🔭

### 🐦 Plucker 🐦: (Group Project)
Tech Stack: Python, Flask, React, PostgreSQL

- Created a bird identification app with Flask (asynchronous capabilities using Hypercorn and asyncio).
- Integrated humorous functionality by generating random recipes for newly logged bird sightings.

### ⚔ ThySpace ⚔: (Group Project)
Tech Stack: MongoDB, Express.js, React, Node.js

- Built a medieval-themed social platform replicating Facebook with features like alliances, posts, comments, and likes.

## 📫 Let's connect 📫
[LinkedIn](https://www.linkedin.com/in/max-joseph-a29666225/)

[GitHub](https://github.com/maxjoseph22)
