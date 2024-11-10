# Hey there, this is Tharunika L
### Learning and Growing

<div align="center">
  <h1 id="dynamic-text">Hey there</h1>
  <h3>Learning and Growing</h3>
</div>

<!-- Add the script that handles the dynamic text change -->
<script>
  let phrases = [
    { text: 'Vanakam', font: 'font-family: "Bamini", sans-serif;' }, // Tamil Font
    { text: 'नमस्ते', font: 'font-family: "Mangal", sans-serif;' },  // Hindi Font
    { text: 'こんにちは', font: 'font-family: "Noto Sans JP", sans-serif;' },  // Japanese Font
    { text: 'Hey there', font: 'font-family: "Arial", sans-serif;' }  // Default Font (English)
  ];

  let currentIndex = 0;
  const dynamicTextElement = document.getElementById("dynamic-text");

  function changeText() {
    dynamicTextElement.style = phrases[currentIndex].font;
    dynamicTextElement.innerText = phrases[currentIndex].text;

    currentIndex = (currentIndex + 1) % phrases.length;
  }

  // Run the changeText function every 3 seconds (3000 milliseconds)
  setInterval(changeText, 3000);
</script>

## Connect with me:
- 🔭 I’m currently working on **Genetic Algorithms**
- 🌱 I’m currently learning **RAG Models**
- 💬 Ask me about **Deep Learning**
- 📫 How to reach me: **tharunika.l14@gmail.com**
- ⚡ Fun fact: **I've read over 150+ books**

### Languages and Tools:
- AWS
- C
- Figma
- Flask
- Git
- Java
- JavaScript
- Linux
- MATLAB
- MongoDB
- MySQL
- Node.js
- OpenCV
- Pandas
- Python
- PyTorch
- React
- React Native
- Scikit-learn
- Seaborn
- TensorFlow
- Zapier

<p align="center"><img src="https://github-readme-stats.vercel.app/api/top-langs?username=tharunikal&show_icons=true&locale=en&layout=compact" alt="tharunikal" /></p>

<p align="center"><img src="https://github-readme-streak-stats.herokuapp.com/?user=tharunikal&" alt="tharunikal" /></p>

