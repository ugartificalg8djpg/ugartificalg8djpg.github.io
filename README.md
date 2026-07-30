<!DOCTYPE html>
<html lang="en-GB">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Ugonna Ezenekwe — Cybersecurity &amp; GRC Analyst</title>
<meta name="description" content="CV of Ugonna Ezenekwe, an entry level cybersecurity and GRC analyst in London. Security audits, incident analysis, NIST CSF, PCI DSS, GDPR.">
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Fraunces:opsz,wght@9..144,500;9..144,600&family=IBM+Plex+Sans:wght@400;500;600&family=IBM+Plex+Mono:wght@400;500&display=swap" rel="stylesheet">
<style>
  :root{
    --paper:#F7F8F6;
    --card:#FFFFFF;
    --ink:#131B26;
    --slate:#5A6B7E;
    --line:#DDE3E0;
    --pass:#0F6B54;
    --pass-soft:#E4F0EB;
    --amber:#8A5A12;
    --amber-soft:#F6EDDC;
  }
  *{margin:0;padding:0;box-sizing:border-box}
  html{scroll-behavior:smooth}
  body{
    background:var(--paper);
    color:var(--ink);
    font-family:'IBM Plex Sans',system-ui,sans-serif;
    font-size:16.5px;
    line-height:1.6;
    -webkit-font-smoothing:antialiased;
  }
  .wrap{max-width:860px;margin:0 auto;padding:0 24px}

  /* ---------- header ---------- */
  header{padding:72px 0 40px;border-bottom:2px solid var(--ink)}
  .eyebrow{
    font-family:'IBM Plex Mono',monospace;
    font-size:12.5px;letter-spacing:.14em;text-transform:uppercase;
    color:var(--pass);margin-bottom:18px;
  }
  h1{
    font-family:'Fraunces',serif;font-weight:600;
    font-size:clamp(38px,7vw,58px);line-height:1.04;
    letter-spacing:-0.015em;margin-bottom:16px;
  }
  .tagline{max-width:56ch;color:var(--slate);font-size:17.5px}
  .contact{margin-top:28px;display:flex;flex-wrap:wrap;gap:10px}
  .contact a{
    font-family:'IBM Plex Mono',monospace;font-size:13px;
    text-decoration:none;color:var(--ink);
    border:1px solid var(--ink);border-radius:999px;
    padding:8px 16px;transition:background .15s,color .15s;
  }
  .contact a:hover,.contact a:focus-visible{background:var(--ink);color:var(--paper)}
  .contact a:focus-visible{outline:2px solid var(--pass);outline-offset:2px}

  /* ---------- sections ---------- */
  section{padding:48px 0;border-bottom:1px solid var(--line)}
  section:last-of-type{border-bottom:none}
  .sec-head{
    display:flex;align-items:baseline;gap:14px;margin-bottom:28px;
  }
  .sec-head h2{
    font-family:'Fraunces',serif;font-weight:600;font-size:26px;letter-spacing:-0.01em;
  }
  .sec-head .ref{
    font-family:'IBM Plex Mono',monospace;font-size:12px;color:var(--slate);
    letter-spacing:.1em;
  }

  /* ---------- summary ---------- */
  .summary p{max-width:68ch;margin-bottom:14px;font-size:16px}
  .summary p:last-child{margin-bottom:0;font-weight:500}

  /* ---------- skills ---------- */
  .skill-row{display:grid;grid-template-columns:170px 1fr;gap:8px 20px;padding:12px 0;border-top:1px dashed var(--line)}
  .skill-row:first-of-type{border-top:none}
  .skill-row dt{
    font-family:'IBM Plex Mono',monospace;font-size:12.5px;
    text-transform:uppercase;letter-spacing:.08em;color:var(--slate);padding-top:3px;
  }
  .skill-row dd{font-size:15.5px}

  /* ---------- register entries (experience + projects) ---------- */
  .entry{
    background:var(--card);border:1px solid var(--line);border-radius:10px;
    padding:24px 26px;margin-bottom:18px;
  }
  .entry-top{display:flex;flex-wrap:wrap;align-items:baseline;gap:8px 14px;margin-bottom:6px}
  .entry-id{
    font-family:'IBM Plex Mono',monospace;font-size:11.5px;
    color:var(--slate);letter-spacing:.1em;
  }
  .entry h3{font-size:18.5px;font-weight:600;letter-spacing:-0.005em}
  .entry .meta{font-size:14px;color:var(--slate)}
  .tags{display:flex;flex-wrap:wrap;gap:6px;margin:10px 0 14px}
  .tag{
    font-family:'IBM Plex Mono',monospace;font-size:11.5px;
    padding:3px 10px;border-radius:4px;
    background:var(--pass-soft);color:var(--pass);
  }
  .tag.warm{background:var(--amber-soft);color:var(--amber)}
  .entry ul{list-style:none}
  .entry li{
    position:relative;padding-left:22px;margin-bottom:10px;font-size:15.5px;
  }
  .entry li::before{
    content:"▸";position:absolute;left:2px;color:var(--pass);font-size:13px;top:2px;
  }
  .entry li:last-child{margin-bottom:0}

  /* ---------- certs ---------- */
  .cert{display:flex;justify-content:space-between;gap:16px;padding:14px 0;border-top:1px dashed var(--line);flex-wrap:wrap}
  .cert:first-of-type{border-top:none}
  .cert .name{font-weight:500}
  .cert .status{
    font-family:'IBM Plex Mono',monospace;font-size:12px;white-space:nowrap;
    align-self:center;padding:3px 10px;border-radius:4px;
  }
  .status.done{background:var(--pass-soft);color:var(--pass)}
  .status.progress{background:var(--amber-soft);color:var(--amber)}

  footer{padding:40px 0 64px;color:var(--slate);font-size:13.5px}
  footer .stamp{font-family:'IBM Plex Mono',monospace;font-size:12px;letter-spacing:.08em}

  /* motion */
  @media (prefers-reduced-motion:no-preference){
    header,section{animation:rise .55s ease both}
    section:nth-of-type(1){animation-delay:.06s}
    section:nth-of-type(2){animation-delay:.12s}
    section:nth-of-type(3){animation-delay:.18s}
    section:nth-of-type(4){animation-delay:.24s}
    section:nth-of-type(5){animation-delay:.3s}
    @keyframes rise{from{opacity:0;transform:translateY(10px)}to{opacity:1;transform:none}}
  }
  @media (max-width:600px){
    header{padding:52px 0 32px}
    .skill-row{grid-template-columns:1fr}
    .entry{padding:20px 18px}
  }
</style>
</head>
<body>

<header>
  <div class="wrap">
    <p class="eyebrow">Security register · London, UK</p>
    <h1>Ugonna Ezenekwe</h1>
    <p class="tagline">Aspiring cybersecurity and GRC analyst with a BSc in Sociology with Criminology.</p>
    <nav class="contact" aria-label="Contact links">
      <a href="mailto:ezenekweugowork04@outlook.com">email</a>
      <a href="https://github.com/ugartificalg8djpg" rel="noopener">github</a>
    </nav>
  </div>
</header>

<section aria-labelledby="about-h">
  <div class="wrap">
    <div class="sec-head"><h2 id="about-h">Summary</h2><span class="ref">REF 00</span></div>
    <div class="summary">
      <p>I've built a portfolio of hands-on projects mirroring real analyst work: internal security audits assessed against NIST CSF, PCI DSS and GDPR with risk registers and remediation roadmaps, incident investigations using tcpdump and Wireshark tracing attack chains across DNS and HTTP traffic, and a home lab running an Ubuntu virtual machine with SIEM tooling for log monitoring and alert triage.</p>
      <p>My background adds strong communication, something many entry level candidates lack. Through my research internship at Reimagining Criminal Justice C.I.C. I drafted correspondence for senior stakeholders, and my criminology degree trained me to analyse risk and evidence, skills that matter in GRC, where translating findings for non technical audiences is half the job.</p>
      <p>I'm seeking entry level roles in GRC, compliance analysis, security operations or internal audit. My inbox is open.</p>
    </div>
  </div>
</section>

<section aria-labelledby="skills-h">
  <div class="wrap">
    <div class="sec-head"><h2 id="skills-h">Key Skills</h2><span class="ref">REF 01</span></div>
    <dl>
      <div class="skill-row"><dt>Cyber &amp; GRC</dt><dd>Gap analysis, governance documentation, control assessment, risk assessment, compliance frameworks (PCI DSS, GDPR, SOC, NIST), SIEM tools, event monitoring</dd></div>
      <div class="skill-row"><dt>Software</dt><dd>Excel, SPSS, Microsoft Office</dd></div>
      <div class="skill-row"><dt>Project support</dt><dd>Project secretariat, milestone tracking, coordinating inputs, progress reporting, action management</dd></div>
      <div class="skill-row"><dt>Communication</dt><dd>Clear written and verbal communication with senior managers and external stakeholders, drafting correspondence and briefings, producing on brand professional documents</dd></div>
    </dl>
  </div>
</section>

<section aria-labelledby="exp-h">
  <div class="wrap">
    <div class="sec-head"><h2 id="exp-h">Work Experience</h2><span class="ref">REF 02</span></div>

    <article class="entry">
      <div class="entry-top">
        <span class="entry-id">ENTRY 001</span>
        <h3>Cybersecurity Home Lab</h3>
        <span class="meta">Self employed · ongoing</span>
      </div>
      <div class="tags"><span class="tag">Ubuntu</span><span class="tag">SIEM</span><span class="tag">SOC processes</span></div>
      <ul>
        <li>Deployed and configured an Ubuntu based virtual machine to simulate an enterprise network environment, establishing a controlled sandbox for hands-on security testing and analysis</li>
        <li>Conducted simulated security monitoring exercises within the lab, developing practical exposure to incident identification, event correlation and security operations centre (SOC) processes</li>
      </ul>
    </article>

    <article class="entry">
      <div class="entry-top">
        <span class="entry-id">ENTRY 002</span>
        <h3>Justice Research and Communications Intern</h3>
        <span class="meta">Reimagining Criminal Justice C.I.C. · Jan 2025 – Apr 2025</span>
      </div>
      <div class="tags"><span class="tag warm">Stakeholder management</span><span class="tag warm">Research</span></div>
      <ul>
        <li>Managed and maintained a structured stakeholder database of over 50 national and international organisations, keeping contact records accurate and accessible so senior staff could retrieve up-to-date information quickly</li>
        <li>Drafted professional outreach correspondence to external partner organisations on behalf of senior staff, communicating clearly for a range of audiences</li>
        <li>Produced concise written summaries of complex documents for senior decision makers, distilling dense material into clear, actionable outputs</li>
        <li>Coordinated research inputs across multiple workstreams simultaneously, prioritising effectively in a small, fast moving team</li>
      </ul>
    </article>
  </div>
</section>

<section aria-labelledby="proj-h">
  <div class="wrap">
    <div class="sec-head"><h2 id="proj-h">Projects</h2><span class="ref">REF 03</span></div>

    <article class="entry">
      <div class="entry-top">
        <span class="entry-id">ENTRY 003</span>
        <h3>NIST CSF Incident Report Analysis</h3>
        <span class="meta">Independent · Jul 2026</span>
      </div>
      <div class="tags"><span class="tag">NIST CSF</span><span class="tag">DoS / ICMP flood</span><span class="tag">IDS/IPS</span></div>
      <ul>
        <li>Applied the five NIST Cybersecurity Framework functions to analyse a denial of service incident, identifying an ICMP flood attack that exploited an unconfigured firewall and mapping the root cause, affected systems and business impact</li>
        <li>Produced a structured incident report covering protection, detection, response and recovery, recommending controls including firewall rate limiting, source IP verification, network monitoring and an IDS/IPS system</li>
      </ul>
    </article>

    <article class="entry">
      <div class="entry-top">
        <span class="entry-id">ENTRY 004</span>
        <h3>OS Hardening Report</h3>
        <span class="meta">Independent · Jul 2026</span>
      </div>
      <div class="tags"><span class="tag">tcpdump</span><span class="tag">DNS / HTTP</span><span class="tag">Brute force</span></div>
      <ul>
        <li>Investigated a simulated website compromise by capturing and analysing network traffic with tcpdump in a sandboxed virtual machine, tracing the full attack chain across DNS and HTTP logs to identify a malicious redirect to a spoofed domain</li>
        <li>Produced a formal security incident report documenting a brute force attack against an administrative account, recommending remediation controls including a strong password policy, multi factor authentication and login attempt limits</li>
      </ul>
    </article>

    <article class="entry">
      <div class="entry-top">
        <span class="entry-id">ENTRY 005</span>
        <h3>Incident Handler's Journal</h3>
        <span class="meta">Independent · Jul 2026</span>
      </div>
      <div class="tags"><span class="tag">NIST IR lifecycle</span><span class="tag">Documentation</span></div>
      <ul>
        <li>Maintained an incident handler's journal documenting security incidents across multiple scenarios, applying the NIST incident response lifecycle and structured analysis of the who, what, when, where and why of each event</li>
        <li>Recorded investigation notes on real world style incidents including ransomware, phishing and data breaches, capturing tools used, actions taken and lessons learned to support post incident review</li>
      </ul>
    </article>

    <article class="entry">
      <div class="entry-top">
        <span class="entry-id">ENTRY 006</span>
        <h3>Wireshark Network Traffic Analysis</h3>
        <span class="meta">Independent · Jul 2026</span>
      </div>
      <div class="tags"><span class="tag">Wireshark</span><span class="tag">SYN flood</span><span class="tag">TCP</span></div>
      <ul>
        <li>Analysed captured network traffic in Wireshark to investigate a website outage, identifying a SYN flood denial of service attack by tracing a high volume of half open TCP connections from a single source IP</li>
        <li>Documented the incident in a structured report explaining the abuse of the TCP three way handshake, its business impact, and prevention measures including SYN cookies, rate limiting and firewall rules</li>
      </ul>
    </article>

    <article class="entry">
      <div class="entry-top">
        <span class="entry-id">ENTRY 007</span>
        <h3>Security Audit Project — Botium Toys</h3>
        <span class="meta">Independent · May 2026</span>
      </div>
      <div class="tags"><span class="tag">PCI DSS</span><span class="tag">GDPR</span><span class="tag">SOC</span><span class="tag">Risk register</span></div>
      <ul>
        <li>Conducted a controls and compliance gap assessment, evaluating existing security controls against PCI DSS, GDPR and SOC requirements and identifying critical gaps including absent least privilege access, unencrypted customer data and no formal disaster recovery plan</li>
        <li>Produced a risk register and governance documentation capturing asset inventory, threat likelihood and impact ratings across administrative, technical and physical control categories</li>
      </ul>
    </article>

    <article class="entry">
      <div class="entry-top">
        <span class="entry-id">ENTRY 008</span>
        <h3>Meridian Health Partners Security Audit</h3>
        <span class="meta">Independent · May – Jun 2026</span>
      </div>
      <div class="tags"><span class="tag">NIST CSF</span><span class="tag">Internal audit</span></div>
      <ul>
        <li>Performed an end to end internal audit for a fictional mid size company (practice project, AI assisted) covering asset inventory, threat likelihood, control gap identification and risk register development</li>
        <li>Produced a written audit report and remediation roadmap presenting prioritised findings to technical and non technical audiences, aligned to recognised compliance frameworks including NIST CSF</li>
      </ul>
    </article>
  </div>
</section>

<section aria-labelledby="cert-h">
  <div class="wrap">
    <div class="sec-head"><h2 id="cert-h">Certifications &amp; Professional Development</h2><span class="ref">REF 04</span></div>
    <div class="cert"><span class="name">Google Cybersecurity Professional Certificate · Coursera</span><span class="status progress">IN PROGRESS · 2026</span></div>
    <div class="cert"><span class="name">Foundations of Cybersecurity · Coursera</span><span class="status done">COMPLETED · MAY 2026</span></div>
    <div class="cert"><span class="name">Play it Safe: Managing Security Risk · Coursera</span><span class="status done">COMPLETED · JUN 2026</span></div>
    <div class="cert"><span class="name">Connect and Protect: Networks and Network Security · Coursera</span><span class="status done">COMPLETED · JUL 2026</span></div>
  </div>
</section>

<section aria-labelledby="edu-h">
  <div class="wrap">
    <div class="sec-head"><h2 id="edu-h">Education</h2><span class="ref">REF 05</span></div>
    <div class="cert"><span class="name">BSc Sociology with Criminology · Middlesex University</span><span class="status done">COMPLETED</span></div>
  </div>
</section>

<footer>
  <div class="wrap">
    <p class="stamp">REGISTER MAINTAINED BY UGONNA EZENEKWE · LONDON</p>
    <p>Open to entry level roles in GRC, compliance analysis, security operations and internal audit.</p>
  </div>
</footer>

</body>
</html># ugartificalg8djpg.github.io
