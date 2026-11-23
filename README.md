<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>RIHAB - Penetration Tester & Defensive Security Practitioner</title>
  <style>
    :root {
      --bg-color: #0d1117;
      --card-bg: #161b22;
      --border-color: #30363d;
      --accent-green: #22f700;
      --text-primary: #e6edf3;
      --text-secondary: #8b949e;
      --link-color: #58a6ff;
    }

    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    body {
      font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
      background-color: var(--bg-color);
      color: var(--text-primary);
      line-height: 1.6;
      padding: 40px 20px;
    }

    .container {
      max-width: 900px;
      margin: 0 auto;
    }

    h2 {
      font-size: 1.5rem;
      font-weight: 600;
      margin-bottom: 16px;
      color: var(--text-primary);
    }

    p {
      margin-bottom: 18px;
      color: var(--text-secondary);
      font-size: 1rem;
    }

    a {
      color: var(--link-color);
      text-decoration: none;
    }

    a:hover {
      text-decoration: underline;
    }

    .name-highlight {
      background-color: var(--card-bg);
      border: 1px solid var(--border-color);
      padding: 2px 8px;
      border-radius: 6px;
      font-family: ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
      font-weight: 700;
      color: var(--text-primary);
    }

    .social-links {
      margin-bottom: 20px;
    }

    details {
      background-color: var(--card-bg);
      border: 1px solid var(--border-color);
      border-radius: 8px;
      padding: 14px 18px;
      margin-bottom: 24px;
    }

    summary {
      cursor: pointer;
      font-weight: 600;
      color: var(--text-primary);
      outline: none;
    }

    .about-details {
      margin-top: 12px;
      color: var(--text-secondary);
      font-size: 0.95rem;
    }

    .about-details p {
      margin-bottom: 8px;
    }

    .about-details p:last-child {
      margin-bottom: 0;
    }

    hr {
      border: 0;
      border-top: 1px solid var(--border-color);
      margin: 32px 0;
    }

    .skills-box {
      border: 2px solid var(--accent-green);
      background-color: var(--card-bg);
      border-radius: 10px;
      padding: 22px;
      margin-bottom: 20px;
    }

    .badge-group {
      display: flex;
      flex-wrap: wrap;
      justify-content: flex-start;
      align-items: center;
      gap: 10px;
    }

    .badge-group img {
      height: 28px;
      border-radius: 4px;
    }

    table {
      width: 100%;
      border-collapse: collapse;
      background-color: var(--card-bg);
      border: 1px solid var(--border-color);
      border-radius: 8px;
      overflow: hidden;
    }

    th, td {
      padding: 14px 16px;
      text-align: left;
      border-bottom: 1px solid var(--border-color);
    }

    th {
      background-color: #1f242c;
      font-weight: 600;
      color: var(--text-primary);
    }

    tr:last-child td {
      border-bottom: none;
    }

    tr:hover td {
      background-color: #1c2128;
    }
  </style>
</head>
<body>
  <div class="container">

    <section id="intro">
      <h2>Hi there 👋</h2>
      <p>
        I'm <a href="https://www.linkedin.com/in/rihabazhuvalappil/" target="_blank" rel="noopener noreferrer"><span class="name-highlight">RIHAB</span></a>,
        Penetration Tester &amp; Defensive Security Practitioner. Experienced across VAPT, Active Directory, incident response, threat hunting, and SIEM/log analysis. Sharing security research, detection notes, and practical remediation insights.
      </p>

      <div class="social-links">
        <a href="https://www.linkedin.com/in/rihabazhuvalappil/" target="_blank" rel="noopener noreferrer">
          <img src="https://img.shields.io/badge/-LinkedIn-0072b1?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
        </a>
      </div>

      <details>
        <summary>More about me</summary>
        <div class="about-details">
          <p><strong>Name:</strong> RIHAB</p>
          <p><strong>From:</strong> Kerala, India &nbsp;|&nbsp; Bug Hunter | Security Researcher | Freelance Penetration Tester</p>
          <p>Hands-on experience in vulnerability assessment, penetration testing, social engineering, and defensive security fundamentals.</p>
          <p>Continuously expanding my skills across web &amp; network security, incident response, and detection/mitigation.</p>
          <p>Actively learning and exploring advanced exploitation, network defense, and practical security research.</p>
        </div>
      </details>
    </section>

    <hr />

    <section id="knowledge_skills">
      <h2>Knowledge &amp; Skills</h2>
      <div class="skills-box">
        <div class="badge-group">
          <img src="https://img.shields.io/badge/Burp_Suite-FF6633?style=for-the-badge&logo=burp-suite&logoColor=white&labelColor=000000" alt="Burp Suite" />
          <img src="https://img.shields.io/badge/Metasploit-008C8C?style=for-the-badge&logo=metasploit&logoColor=white&labelColor=000000" alt="Metasploit" />
          <img src="https://img.shields.io/badge/Wireshark-009639?style=for-the-badge&logo=wireshark&logoColor=white&labelColor=000000" alt="Wireshark" />
          <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black&labelColor=000000" alt="Linux" />
          <img src="https://img.shields.io/badge/Kali_Linux-557C94?style=for-the-badge&logo=kali-linux&logoColor=white&labelColor=000000" alt="Kali Linux" />
          <img src="https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white&labelColor=000000" alt="VS Code" />
          <img src="https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=openjdk&logoColor=white&labelColor=000000" alt="Java" />
        </div>
      </div>
    </section>

    <hr />

    <section id="Certifications">
      <h2>Certifications</h2>
      <div class="badge-group">
        <img src="https://img.shields.io/badge/CompTIA_Security%2B-SY0--701-E11D48?style=for-the-badge&logo=comptia&logoColor=white&labelColor=0A0A0A" alt="CompTIA Security+ SY0-701" />
        <img src="https://img.shields.io/badge/OCSP-Certified-DC2626?style=for-the-badge&logo=kali-linux&logoColor=white&labelColor=0A0A0A" alt="OCSP Certified" />
        <img src="https://img.shields.io/badge/CPT-Penetration_Tester-B91C1C?style=for-the-badge&logo=hackthebox&logoColor=white&labelColor=0A0A0A" alt="CPT Certified Penetration Tester" />
      </div>
    </section>

    <hr />

    <section id="Projects">
      <h2>Projects</h2>
      <table>
        <thead>
          <tr>
            <th>Project</th>
            <th>Description</th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <td><strong><a href="https://github.com/" target="_blank" rel="noopener noreferrer">Project 1</a></strong></td>
            <td>Short Description</td>
          </tr>
          <tr>
            <td><strong><a href="https://github.com/" target="_blank" rel="noopener noreferrer">Project 2</a></strong></td>
            <td>Short Description</td>
          </tr>
          <tr>
            <td><strong><a href="https://github.com/" target="_blank" rel="noopener noreferrer">Project 3</a></strong></td>
            <td>Short Description</td>
          </tr>
        </tbody>
      </table>
    </section>

  </div>
</body>
</html>
