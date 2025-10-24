<!Doctype html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width,initial-scale=1">
  <title>Autobiography — First Year IT Student</title>
  <meta name="description" content="Autobiography page for a first-year Industrial Technology student.">
  <style>
    :root{
      --bg:#ffeef8; --card:#ffffff; --muted:#a78a9c; --accent:#f472b6;
      --radius:14px;
      font-family: Inter, system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial;
    }
    *{box-sizing:border-box}
    body{margin:0;background:linear-gradient(180deg,var(--bg) 0%, #fff5f9 100%);color:#4b224a}
    .container{max-width:900px;margin:36px auto;padding:28px}

    header{display:flex;gap:20px;align-items:center}
    .avatar{width:120px;height:120px;border-radius:18px;background:linear-gradient(135deg,#fcd6e8,#ffeef8);display:flex;align-items:center;justify-content:center;font-weight:700;color:var(--accent);font-size:28px}
    h1{margin:0;font-size:28px}
    p.lead{margin:6px 0 0;color:var(--muted)}

    .card{background:var(--card);border-radius:var(--radius);padding:20px;margin-top:22px;box-shadow:0 10px 30px rgba(15,23,42,0.06)}
    .grid{display:grid;grid-template-columns:1fr 320px;gap:18px}
    @media (max-width:880px){.grid{grid-template-columns:1fr}}

    section h2{margin:0 0 10px;font-size:18px;color:var(--accent)}
    .meta{color:var(--muted);font-size:14px}

    ul.skills{list-style:none;padding:0;margin:0;display:flex;flex-wrap:wrap;gap:8px}
    ul.skills li{background:#ffe4f1;padding:8px 12px;border-radius:999px;font-size:13px}

    .progress{background:#fce7f3;border-radius:999px;height:10px;overflow:hidden}
    .progress > i{display:block;height:100%;background:linear-gradient(90deg,var(--accent),#fbcfe8)}

    footer{margin-top:18px;color:var(--muted);font-size:13px}

    .contact dt{font-weight:600}
    .goal-list{margin:0;padding-left:1.1rem}

    .top-right{margin-left:auto}
    .btn{border:0;background:#f472b6;color:white;padding:8px 12px;border-radius:8px;cursor:pointer}
  </style>
</head>
<body>
  <div class="container">
    <header>
      <div class="avatar">MT</div>
      <div>
        <h1>Ma.Cristina Tangpos — First Year IT Student</h1>
        <p class="lead">Industrial Technology, Class of 2029 &middot; Passionate about basic coding, web apps, and learning new technologies.</p>
      </div>
      <div class="top-right">
        <button class="btn" onclick="toggleTheme()">Toggle Theme</button>
      </div>
    </header>

    <div class="grid">
      <main>
        <article class="card">
          <section>
            <h2>About Me</h2>
            <p class="meta">Hello! I am a first-year Information Technology student currently studying at Lapu-Lapu City College. I love building small web projects and exploring how software interacts with people and devices. I enjoy learning by doing basic coding, learning new typing techniques, and contributing to group projects.</p>
          </section>

          <section style="margin-top:16px">
            <h2>Education</h2>
            <p class="meta"><strong>BS in Information Technology</strong> &mdash; Lapu-Lapu City College &middot; First Year (2025 - present)</p>
            <ul style="margin-top:8px">
              <li>Relevant courses: Introduction to Programming, Computer Systems, Web Development</li>
            </ul>
          </section>

          <section style="margin-top:16px">
            <h2>Skills</h2>
            <ul class="skills">
              <li>BASIC CODING</li>
              <li>HTML</li>
              <li>CSS</li>
              <li>BASIC JAVA</li>
            </ul>

            <div style="margin-top:12px">
              <div class="meta">Web Development</div>
              <div class="progress" aria-hidden="true" style="margin-top:6px"><i style="width:70%"></i></div>
            </div>
          </section>

          <section style="margin-top:16px">
            <h2>Projects & Experience</h2>
            <p class="meta">Mini portfolio highlights:</p>
            <ul>
              <li><strong>Personal Portfolio Website</strong> &mdash; Created a 3d stickman using html code.</li>
              <li><strong>To-Do App (Group Project)</strong> &mdash; Basic coding and ppt.</li>
            </ul>
          </section>

          <section style="margin-top:16px">
            <h2>Hobbies & Interests</h2>
            <p class="meta">When I’m not coding, I enjoy sketch art, playing the guitar, and exploring new things around me and feeding my curiosity.</p>
          </section>

          <section style="margin-top:16px">
            <h2>Goals</h2>
            <ol class="goal-list">
              <li>Learn a modern frontend framework (React or Vue) within the year.</li>
              <li>Master coding.</li>
              <li>Improved typing skills.</li>
            </ol>
          </section>
        </article>
      </main>

      <aside>
        <div class="card">
          <section>
            <
