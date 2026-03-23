<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Christian Angelo B. Inocencio · CV</title>
  <style>
    
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      background: #ffffff;
      font-family: 'Times New Roman', Georgia, 'Palatino', serif;
      color: #000000;
      line-height: 1.45;
      padding: 40px 20px;
    }

    .cv-paper {
      max-width: 1000px;
      margin: 0 auto;
      background: white;
      padding: 40px 48px;
      box-shadow: none;
      border: none;
    }

    
    h1 {
      font-size: 2rem;
      font-weight: 500;
      letter-spacing: 0.5px;
      text-transform: uppercase;
      margin-bottom: 8px;
      color: #000;
      border-bottom: 2px solid #000;
      padding-bottom: 12px;
      font-family: inherit;
    }

    .subhead {
      font-size: 0.95rem;
      margin-top: 6px;
      margin-bottom: 0px;
      color: #2c2c2c;
      font-style: normal;
    }

    .contact-bar {
      margin: 18px 0 22px 0;
      padding-bottom: 10px;
      border-bottom: 1px solid #ccc;
      font-size: 0.85rem;
      display: flex;
      flex-wrap: wrap;
      justify-content: flex-start;
      gap: 24px;
      color: #1e1e1e;
    }
    .contact-bar span {
      white-space: nowrap;
    }

    .section-title {
      font-size: 1rem;
      font-weight: 600;
      text-transform: uppercase;
      letter-spacing: 0.8px;
      margin: 28px 0 12px 0;
      padding-bottom: 3px;
      border-bottom: 1px solid #000;
      color: #000;
      font-family: inherit;
    }

    .first-section {
      margin-top: 8px;
    }

    .entry {
      margin-bottom: 20px;
      page-break-inside: avoid;
    }
    .entry-header {
      display: flex;
      flex-wrap: wrap;
      justify-content: space-between;
      align-items: baseline;
      margin-bottom: 4px;
    }
    .entry-title {
      font-weight: 700;
      font-size: 0.95rem;
      letter-spacing: 0.2px;
      color: #000;
    }
    .entry-subtitle {
      font-style: italic;
      font-weight: 500;
      font-size: 0.88rem;
      color: #3a3a3a;
      margin-top: 2px;
    }
    .entry-date {
      font-weight: normal;
      font-size: 0.82rem;
      color: #4a4a4a;
      white-space: nowrap;
    }
    .entry-location {
      font-size: 0.78rem;
      color: #5a5a5a;
      margin-top: 2px;
      margin-bottom: 6px;
    }
    .entry-desc {
      margin-top: 6px;
      font-size: 0.86rem;
      line-height: 1.45;
      color: #1e1e1e;
    }
    .entry-desc ul {
      margin-left: 1.5rem;
      margin-top: 4px;
      margin-bottom: 4px;
    }
    .entry-desc li {
      margin-bottom: 4px;
    }
    .entry-desc p {
      margin-bottom: 4px;
    }

    .inline-badge-list {
      margin: 6px 0 4px 0;
      padding-left: 0;
      display: flex;
      flex-wrap: wrap;
      gap: 16px;
      list-style: none;
    }
    .inline-badge-list li {
      font-size: 0.85rem;
    }
    .tech-list {
      display: flex;
      flex-wrap: wrap;
      gap: 8px 20px;
      margin-top: 6px;
      margin-bottom: 6px;
    }
    .tech-item {
      font-size: 0.85rem;
    }
    .skills-grid {
      margin-top: 6px;
    }
    .skills-category {
      margin-bottom: 8px;
    }
    .skills-category strong {
      font-weight: 700;
    }

    @media (max-width: 650px) {
      .cv-paper {
        padding: 20px 24px;
      }
      .contact-bar {
        gap: 12px;
        flex-wrap: wrap;
      }
      .entry-header {
        flex-direction: column;
        gap: 4px;
      }
      .entry-date {
        white-space: normal;
      }
    }

    @media print {
      body {
        padding: 0;
        margin: 0;
      }
      .cv-paper {
        padding: 0.4in;
        max-width: 100%;
      }
      .contact-bar {
        border-bottom: 1px solid #aaa;
      }
    }
  </style>
</head>
<body>
<div class="cv-paper">
  
  <h1>CHRISTIAN ANGELO B. INOCENCIO</h1>
  
  <div class="contact-bar">
    <span>📧 Cbaldonado54@gmail.com</span>
    <span>📞 (64) 993-126-9550</span>
    <span>📍 San Jose Del Monte, Bulacan</span>
    <span>🔗 HTTP://GitHub.com/Geloox</span>
  </div>

  <div class="section-title first-section">Education</div>
  <div class="entry">
    <div class="entry-header">
      <div class="entry-title">Bestlink College of the Philippines</div>
      <div class="entry-date">2022 – 2026</div>
    </div>
    <div class="entry-subtitle">Bachelor of Science in Computer Engineering · San Jose Del Monte, Bulacan</div>
    <div class="entry-desc">
      Expected graduation: 2026. Focus on embedded systems, robotics, and full-stack development.
    </div>
  </div>

  <div class="section-title">Academic Projects</div>
  
  <div class="entry">
    <div class="entry-header">
      <div class="entry-title">Autonomous Parcel Sorter with Li-DAR Navigation and Cobotic Arm</div>
      <div class="entry-date">2025 – Present</div>
    </div>
    <div class="entry-subtitle">Hardware Analyst Capstone Project</div>
    <div class="entry-desc">
      <ul>
        <li>Architected the hardware for an autonomous mobile sorting robot, integrating Li-DAR for navigation, computer vision for parcel recognition, and a multi-axis cobotic arm for manipulation.</li>
        <li>Designed and deployed a full-stack monitoring dashboard using Flask and SQLite, providing a web interface for real-time system tracking, data logging, and manual override control.</li>
        <li><strong>Technologies:</strong> Python, C++, Raspberry Pi 4, Arduino, LiDAR, OpenCV, Flask, SQLite.</li>
      </ul>
    </div>
  </div>

  <div class="entry">
    <div class="entry-header">
      <div class="entry-title">Automated Parcel Sorting Conveyor</div>
      <div class="entry-date">2024 – 2025</div>
    </div>
    <div class="entry-subtitle">Hardware Analyst Capstone Project</div>
    <div class="entry-desc">
      <ul>
        <li>Managed the complete software deployment on a Raspberry Pi, including OS configuration, library management, and scripting for all hardware component functions.</li>
        <li>Implemented OCR using Open-CV and PyTesseract to read parcel addresses under variable lighting conditions.</li>
        <li>Engineered a full-stack web application using Flask to serve as a real-time monitoring dashboard for the conveyor's operational status and sorting history.</li>
        <li><strong>Technologies:</strong> Python, OpenCV, PyTesseract, Raspberry Pi, Flask, SQL.</li>
      </ul>
    </div>
  </div>

  <div class="entry">
    <div class="entry-header">
      <div class="entry-title">Automated Conveyor Color-Based Segregation</div>
      <div class="entry-date">2023 – 2024</div>
    </div>
    <div class="entry-subtitle">Hardware Analyst Capstone Project</div>
    <div class="entry-desc">
      <ul>
        <li>Programmed an industrial device for companies with color implantation to products, creating C++ algorithms to translate analog data from Color Sensor into distinct, pre-programmed commands.</li>
        <li>Engineered a multi-output Servo Motors that segregates different colors and transmits the data into 7-segment display for counteraction.</li>
        <li><strong>Technologies:</strong> C++, Arduino Mega, Color Sensor, MG995 Servo Motor.</li>
      </ul>
    </div>
  </div>

  <div class="section-title">Certifications</div>
  <div class="entry-desc" style="margin-bottom: 8px;">
    <ul style="margin-left: 1.2rem;">
      <li><strong>Formulating Competitive Marketing Strategies in the Digital Age</strong> — June 28, 2025</li>
      <li><strong>Moving Towards Quantum Computer Engineering in the Philippines</strong> — June 24, 2025</li>
      <li><strong>The Future of Development: Will Vibe Coding Replace Traditional Programming?</strong> — June 7, 2025</li>
      <li><strong>From Ground to Cloud: Building Seamless Connectivity</strong> — May 31, 2025</li>
      <li><strong>With Great Data Comes Great Responsibility: Training AI for a Better World</strong> — March 15, 2025</li>
      <li><strong>Training Solution Collaborative Robotics</strong> — June 27, 2024</li>
    </ul>
  </div>

  <div class="section-title">Technologies & Tools</div>
  <div class="tech-list">
    <span class="tech-item"><strong>Languages:</strong> Python, C++, JavaScript, SQL, HTML, CSS</span><br>
    <span class="tech-item"><strong>Frameworks & DB:</strong> Flask, SQLite</span><br>
    <span class="tech-item"><strong>Hardware & IDEs:</strong> AutoCAD, Blender, Arduino IDE, Proteus 8, MPLAB IDE</span><br>
    <span class="tech-item"><strong>Platforms & Microcontrollers:</strong> Raspberry Pi, Arduino, Microcontrollers, Sensors, Actuators, IoT Based Integration</span>
  </div>

  <div class="section-title">Skills & Competencies</div>
  <div class="skills-grid">
    <div class="skills-category"><strong>Software Development</strong> · Embedded Systems Programming · Front End Web Development</div>
    <div class="skills-category"><strong>Hardware Integration & Control</strong> · Prototyping & Circuit Design · Technical Documentation & Research Writing</div>
    <div class="skills-category"><strong>Team Leadership & Presentation</strong> · Problem Solving · System Architecture Design</div>
    <div class="skills-category"><strong>AI & Automation Exploration</strong> · Version Control (Git/GitHub) · Academic Research & Defense</div>
  </div>

  <div class="section-title">Interests & Professional Focus</div>
  <div class="entry-desc">
    Robotics and autonomous systems · Industrial automation · Embedded AI · Full-stack IoT dashboards · Collaborative robotics (Cobotics) · Computer vision applications · Open-source hardware/software integration.
  </div>

  <div style="margin-top: 28px; border-top: 1px solid #ddd; padding-top: 12px; font-size: 0.75rem; color: #4a4a4a;">
    <em>Full CV and project portfolio available at github.com/Geloox</em>
  </div>
</div>
</body>
</html>
