<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>PBA Presentation - Root Cause and Solution</title>
  <link rel="stylesheet" href="styles.css" />
  <style>
    body {
      font-family: 'Times New Roman', serif;
      margin: 0;
      background: #f4f4f4;
    }

    header {
      background: #2e7d32;
      color: white;
      padding: 10px;
      text-align: center;
      position: sticky;
      top: 0;
    }

    header h1 {
      margin: 0;
    }

    .menu-toggle {
      background: white; 
      color: #0066ff;
      border: 2px solid black;
      padding: 5px 10px;
      margin: 5px;
      cursor: pointer;
      font-weight: bold;
      border-radius: 5px;
    }

    .home-button {
      background: white; 
      color: #0066ff;
      border: 2px solid black;
      padding: 5px 10px;
      margin: 5px;
      cursor: pointer;
      font-weight: bold;
      border-radius: 5px;
    }

    .container {
      display: flex;
    }

    /* Sidebar */
    .sidebar {
      width: 250px;
      background: #79fc6d;
      padding: 15px;
      border: 2px solid black;
    }

    .sidebar h2 {
      margin-top: 0;
    }
    
    img {
  border-radius: 100%;
    }

    .topic-button {
      display: block;
      width: 100%;
      margin: 8px 0;
      padding: 8px;
      background: #2e7d32;
      color: white;
      border: none;
      border-radius: 4px;
      cursor: pointer;
      text-align: left;
    }

    /* Main content */
    .main-content {
      flex: 1;
      padding: 20px;
    }

    /* White rectangular box for headers + subtopics */
    .topic-box {
      background: white;
      border: 2px solid #ccc;
      border-radius: 10px;
      padding: 15px;
      margin-bottom: 20px;
      border: 2px solid black;
    }

    .topic-box h2, .topic-box h3 {
      margin: 0 0 10px 0;
    }

    .content {
      margin-top: 10px;
    }

    /* Navigation buttons */
    .nav-buttons {
      margin-top: 10px;
    }

    .nav-button {
      background: #2e7d32;
      color: white;
      border: none;
      padding: 6px 12px;
      margin: 0 5px;
      cursor: pointer;
      border-radius: 5px;
    }

    footer {
      text-align: center;
      padding: 15px;
      background: #2e7d32;
      color: white;
      margin-top: 20px;
    }
  </style>
</head>
<body>
   <header>
      <button id="menuToggle" class="menu-toggle" onclick="toggleSidebar()">☰ Menu</button>
      <button class="home-button" onclick="showHome()">Home</button>
    <h1>Root Cause Analysis - Group 6</h1>
  </header>

  <div class="container">
    <!-- Sidebar -->
    <aside class="sidebar" id="sidebar">
      <h2>Select a Topic</h2>
      <ul>
   <li><button class="topic-button" onclick="showTopic('MP')">1. Main Problem</button></li>
  <li><button class="topic-button" onclick="showTopic('RC')">2. Root Cause</button></li>
      </ul>
    </aside>



    <!-- Main Content -->
    <main class="main-content">
      <!-- Home -->
      <div id="homeContent" class="topic-box" style="display: block;">
        <h2>Introduction to our Homepage</h2>
        <p>Welcome! This is the Homepage Content that includes the main problem or the root cause of the problem. Dive into each subtopic by clicking the menu button after the logo and choosing the following topics where we discuss the problem identified. Since this is the Homepage content, we will only share the problems regarding to root cause analysis or (RCA)</p>
        <p><strong>Group 6 Project</strong></p>
            <!-- Example of a navigation menu to be included in all HTML files -->
<nav>
    <a href="index.html" class="nav-link">Home</a> 
    <a href="solution.html" class="nav-link">Solution</a> 
    <a href="about.html" class="nav-link">About</a> 
</nav>
      </div>

<!-- Main Problem -->
<div id="MPContent" style="display:none;">
  <div class="topic-box">
    <h1>Main Problem;</h1>
  </div>
  <div class="topic-box" id="MP1" style="display:none;">
    <h3>
      Problem; Many businesses don't use the DOST green packaging solutions due to its
      price, inconsistent quality, and lack of awareness.
    </h3>
  </div>
</div>
<!-- End -->

<!-- RCA -->
<div id="RCAContent" style="display:none;">
  <div class="topic-box">
    <h2>Root Cause Analysis -- 5 Whys</h2>
  </div>
  <div class="topic-box" id="RCA1" style="display:none;">
  </div>
</div>
<!-- End -->

<!-- RC -->
<div id="RCContent" style="display:none;">
  <div class="topic-box">
    <h1>Root Cause;</h1>
  </div>

  <div class="topic-box" id="RC1" style="display:none;">
          <h3>Root Cause: Lack of support, funding, and promotion for affordable, and inconsistent quality.</h3>
          <div class="nav-buttons">
          </div>
        </div>
          </div>
        </div>
      </div>
<!-- End -->

<!-- SAR -->
<div id="SARContent" style="display:none;">
  <div class="topic-box">
  </div>
  <div class="topic-box" id="SAR1" style="display:none;">
     <div class="nav-buttons">
    </div>
  </div>
</div>
<!-- End -->
<!-- If you copy my code, you are *****, you snitch😎😎😎-->
<!-- If you copy my code, you are *****, you snitch😎😎😎-->
<!-- If you copy my code, you are *****, you snitch😎😎😎-->
<!-- If you copy my code, you are *****, you snitch😎😎😎-->
<!-- If you copy my code, you are *****, you snitch😎😎😎-->
<!-- If you copy my code, you are *****, you snitch😎😎😎-->
<!-- If you copy my code, you are *****, you snitch😎😎😎-->
<!-- If you copy my code, you are *****, you snitch😎😎😎-->
<!-- If you copy my code, you are *****, you snitch😎😎😎-->
<!-- If you copy my code, you are *****, you snitch😎😎😎-->
<!-- If you copy my code, you are *****, you snitch😎😎😎-->
<!-- If you copy my code, you are *****, you snitch😎😎😎-->
<!-- If you copy my code, you are *****, you snitch😎😎😎-->
      <!-- Listed Problems --> <!--Don't mind this code -->
      <div id="listedProblemsContent" style="display:none;">
        <div class="topic-box">
          <h2>Listed Problems - Main Issue (ICT, AFA, FCS, IA)</h2>
          <table>
            <tr>
              <th><strong>ICT</strong></th>
              <th><strong>AFA</strong></th>
              <th><strong>FCS</strong></th>
              <th><strong>IA</strong></th>
            </tr>
            
            <tr>
              <td>Unequal access to technology and stable internet in rural/remote schools.</td>
              <td>High cost and scarcity of green packaging materials.</td>
              <td>Inadequate hygiene and safety practices in spas/salons.</td>
              <td>Shortage of modern tools and safety equipment.</td>
            </tr>
            
            <tr>
              <td>Insufficient teacher training in effective ICT use, limiting equal learning.</td>
              <td>Low awareness and preference for cheap plastics over sustainable options.</td>
              <td>Weak regulations and enforcement, increasing health risks.</td>
              <td>Poor-quality materials and lack of skilled workers, causing unsafe structures.</td>
            </tr>
          </table>
          
          <h3><strong>Our group chooses AFA, DOST Green Packaging Solution - High cost, Poor-quality and Low Awareness</strong></h3>
        </div>
      </div>
    </main>
  </div>

  <footer>
    <p>&copy; 2025 -- Experience Guide 8 -- Group 6</p>
  </footer>

  <script>
    let currentTopic = null;
    let currentSubTopic = 1;
    let sidebarVisible = false;

    function toggleSidebar() {
      const sidebar = document.getElementById('sidebar');
      sidebarVisible = !sidebarVisible;
      sidebar.style.display = sidebarVisible ? 'block' : 'none';
    }

    function showHome() {
      const topics = ['MPContent', 'RCAContent', 'RCContent', 'SARContent', 'listedProblemsContent'];
      topics.forEach(topic => {
        document.getElementById(topic).style.display = 'none';
      });
      document.getElementById('homeContent').style.display = 'block';
      resetSubTopics();
      currentTopic = 1;
      currentSubTopic = 1;
      if (sidebarVisible) toggleSidebar();
    }

    function showTopic(topicId) {
      const topics = ['homeContent', 'MPContent', 'RCAContent', 'RCContent', 'SARContent', 'listedProblemsContent'];
      topics.forEach(t => {
        document.getElementById(t).style.display = 'none';
      });
      document.getElementById(topicId + 'Content').style.display = 'block';
      currentTopic = topicId;
      if (topicId !== 'MPContent') {
        currentSubTopic = null;
        showSubTopic(topicId, 1);
      }
      if (sidebarVisible) toggleSidebar();
    }

    function showSubTopic(topicId, subNumber) {
      for (let i = 1; i <= 3; i++) {
        const subDiv = document.getElementById(topicId + i);
        if (subDiv) subDiv.style.display = 'none';
      }
      const target = document.getElementById(topicId + subNumber);
      if (target) target.style.display = 'block';
      currentSubTopic = subNumber;
    }

    function resetSubTopics() {
      const topics = ['MP', 'RCA', 'RC', 'SAR', 'listedProblems'];
      topics.forEach(topic => {
        for (let i = 1; i <= 3; i++) {
          const subDiv = document.getElementById(topic + i);
          if (subDiv) subDiv.style.display = 'none';
        }
      });
    }

    showHome();
    document.getElementById('sidebar').style.display = 'none';
  </script>
</body>
</html>
