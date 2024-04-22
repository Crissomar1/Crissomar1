
<h3>Hi there 👋 I am Cristian Morales
<script>
    // Your JavaScript code here
    function cutImageToCenter(imageUrl, width, height) {
        const canvas = document.createElement('canvas');
        const context = canvas.getContext('2d');
        const image = new Image();

        image.onload = function() {
            const x = (image.width - width) / 2;
            const y = (image.height - height) / 2;

            canvas.width = width;
            canvas.height = height;

            context.drawImage(image, x, y, width, height, 0, 0, width, height);

            const dataUrl = canvas.toDataURL();
            const imgElement = document.createElement('img');
            imgElement.src = dataUrl;

            document.body.appendChild(imgElement);
        };

        image.src = imageUrl;
    }
    cutImageToCenter('https://i.giphy.com/U2RlmYS95I3IvrBDzo.webp', 50, 50);
</script>
<img src="https://i.giphy.com/U2RlmYS95I3IvrBDzo.webp" sharp="center,50,50">
use this code to center the image

</h3>

I'm a final year Computer Engineering student at the University of Guadalajara, specializing in Artificial Intelligence. I'm passionate about coding, problem-solving, and learning new technologies.

## 📚 Education
- **Computer Engineering**, University of Guadalajara (UdeG), Expected graduation: 2024
- **Academic Exchange Program**, Autonomous University of Nuevo León (UANL), 2023

## 💼 Work Experience
- **Bilingual Agent**, BELIVEO (XFINITY), Mexico

## 🔭 Projects
I've worked on various projects using different programming languages like C++, Python, HTML, GDScript, TypeScript, and JavaScript. My repositories include a C compiler, a data mining project, and web developments with NextJS and Astro.

## 🌱 I'm currently learning
I'm currently focusing on Artificial Intelligence, including machine learning, neural networks, and data analysis.

## 📈 GitHub Stats
[![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=Crissomar1)](https://github.com/anuraghazra/github-readme-stats)

## 📫 How to reach me
[Insert Contact Information Here]

## 🔗 Links
[Insert Relevant Links Here]

Python is my preferred language and I'm always excited to learn more and work on new projects. Feel free to reach out to me if you have any opportunities or collaborations!
<!--
**Crissomar1/Crissomar1** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...


this is te greatest GitHub profile of all time it needs to be seen by everyone and include all the information about me and my projects
-->


