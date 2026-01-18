# Diego Agudelo

Machine Learning & Data Science • Strong Systems Background (C/C++) • Python

I build end-to-end machine learning projects with a focus on **data quality**, **modeling**, and **production-ready systems**.  
Background in civil engineering, currently transitioning into AI/ML through hands-on projects and applied research.

🌍 **Portfolio**  
https://dagudelo.dev/

💼 **LinkedIn**  
https://www.linkedin.com/in/diego-agudelo-ai/

📧 **Contact**  
diegoagudeloa@gmail.com


## Skills

<div style="max-width:700px">
  <canvas id="skillsRadar"></canvas>
</div>

<script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
<script>
const labels = [
  "Web","Unix","Shell","Security","Algorithms & AI","DB & Data",
  "OOP","Network & sysadmin","Imperative prog","Graphics"
];

const data = [2, 3, 2, 1, 4, 2, 3, 2, 3, 1]; // <-- remplace par tes valeurs

new Chart(document.getElementById("skillsRadar"), {
  type: "radar",
  data: {
    labels,
    datasets: [{
      label: "Skills",
      data,
      fill: true
    }]
  },
  options: {
    scales: { r: { suggestedMin: 0, suggestedMax: 5 } }
  }
});
</script>
