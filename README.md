# Hi 👋, I'm Saurav Kumar

### A passionate frontend developer from Jharkhand

---

## 📊 Profile Stats

<div align="center">

**📦 Repositories**  
<img src="https://img.shields.io/badge/Total_Repos-loading-blue?style=flat-square" alt="Repo Count" id="repoCount"/>

![GitHub followers](https://img.shields.io/github/followers/sauravkushwaha2244?style=flat-square)
![GitHub User's stars](https://img.shields.io/github/stars/sauravkushwaha2244?style=flat-square)

</div>

---

## 💼 About Me

- 🎯 **Frontend Developer** specializing in modern web technologies
- 🌱 **Currently Learning:** DOM, JavaScript Frameworks, Advanced CSS
- 💻 **Tech Stack:** HTML5, CSS3, JavaScript, C++
- 📍 **Location:** Jharkhand, India

---

## 🛠️ Languages & Tools

<div align="center">

![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34C26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

</div>

---

## 🌐 Connect With Me

<div align="center">

[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/sauravkushwaha2244)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/your-profile)
[![Twitter](https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/your-handle)

</div>

---

## 📈 GitHub Activity

[![GitHub Streak](https://github-readme-streak-stats.herokuapp.com?user=sauravkushwaha2244&theme=dark)](https://github.com/sauravkushwaha2244)

---

## 🚀 Recent Work

Your featured projects will appear here. Add descriptions as you build more repositories.

---

<div align="center">

### Made with ❤️ by Saurav Kumar

![Visitors](https://visitor-badge.laobi.icu/badge?page_id=sauravkushwaha2244.sauravkushwaha2244)

</div>

---

<script type="module">
// This script runs when GitHub renders the README
// It fetches your repository count dynamically

async function updateRepoCount() {
  try {
    const response = await fetch('https://api.github.com/users/sauravkushwaha2244');
    const data = await response.json();
    const repoCount = data.public_repos;
    
    // Update the badge with actual count
    const badge = document.getElementById('repoCount');
    if (badge) {
      badge.src = `https://img.shields.io/badge/Total_Repos-${repoCount}-blue?style=flat-square`;
    }
  } catch (error) {
    console.log('Could not fetch repo count');
  }
}

// Run when DOM is ready
if (document.readyState === 'loading') {
  document.addEventListener('DOMContentLoaded', updateRepoCount);
} else {
  updateRepoCount();
}
</script>
