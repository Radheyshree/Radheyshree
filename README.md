

<!--
**Radheyshree/Radheyshree** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

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

# 👋 Hi there, I'm Radheyshree Agrawal.

## Final year B.Tech in CSE undergrad | Passionate about problem-solving and building solutions 🚀

## 🛠 Skills
- Programming Languages: Python, C, C++, Java
- Familiar With: Python Development, Full Stack Development
- Tools: Git
<!--- Databases: [e.g., MySQL, MongoDB]-->


## 🌱 I'm currently learning
- Artificial Intelligence and Machine Learning
- Generative AI

## 📫 How to reach me
- LinkedIn: [radheyshree](https://www.linkedin.com/in/radheyshree-agrawal-7a4430236/)
- Email: radheyshree01@gmail.com

<button id="profile-view-count" onclick="getProfileViewCount()">
  <img src="https://camo.githubusercontent.com/edb5baa255fa08dd99bd1753a5c723231d53422cee6a6f61e06a02e2ba24ecb7/68747470733a2f2f6b6f6d617265762e636f6d2f67687076632f3f757365726e616d653d75746b617273686f6e676974687562266c6162656c3d50726f66696c65253230766965777326636f6c6f723d306537356236267374796c653d666c6174" alt="Profile views">
  <span id="view-count"></span>
</button>

<script>
  const apiUrl = 'https://api.github.com/users/Radheyshree';
  const token = process.env.TOKEN_github;
  const headers = {
    'Authorization': `Bearer ${token}`,
    'Content-Type': 'application/json'
  };

  function getProfileViewCount() {
    fetch(apiUrl, { headers })
     .then(response => response.json())
     .then(data => {
        const viewCount = data.view_count;
        document.getElementById('view-count').textContent = `: ${viewCount}`;
      });
  }
</script>
<!---
## 📊 GitHub Stats
![Your GitHub stats](https://github-readme-stats.vercel.app/api?username=yourusername&show_icons=true&theme=radical)

## 🏆 GitHub Trophies
![](https://github-profile-trophy.vercel.app/?username=yourusername&theme=radical&no-frame=false&no-bg=true&margin-w=4)


---
⭐️ From [yourusername](https://github.com/yourusername)-->
