<!-- Header -->
<div align="center">
  <img src="header-background.jpg" width="100%" height="200px">
  <h1>Hi, I'm [Iman]!</h1>
  <h3>Full-Stack Developer with knowledge of React, TypeScript, and Node</h3>
  <img src="react-logo.svg" width="50px" height="50px">
  <img src="typescript-logo.svg" width="50px" height="50px">
  <img src="node-logo.svg" width="50px" height="50px">
</div>

<!-- Chart -->
<div align="center">
  <canvas id="myChart"></canvas>
</div>

<!-- Footer -->
<div align="center">
  <img src="footer-background.jpg" width="100%" height="200px">
  <p>Thanks for visiting my profile! Connect with me on <a href="https://www.linkedin.com/in/[Your LinkedIn Profile]">LinkedIn</a>.</p>
</div>

<!-- JavaScript -->
<script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
<script>
  var ctx = document.getElementById('myChart').getContext('2d');
  var myChart = new Chart(ctx, {
    type: 'bar',
    data: {
      labels: ['React', 'TypeScript', 'Node'],
      datasets: [{
        label: 'Skill Level',
        data: [90, 80, 70],
        backgroundColor: [
          'rgba(255, 99, 132, 0.2)',
          'rgba(54, 162, 235, 0.2)',
          'rgba(255, 206, 86, 0.2)'
        ],
        borderColor: [
          'rgba(255, 99, 132, 1)',
          'rgba(54, 162, 235, 1)',
          'rgba(255, 206, 86, 1)'
        ],
        borderWidth: 1
      }]
    },
    options: {
      scales: {
        y: {
          beginAtZero: true
        }
      }
    }
  });
</script>
