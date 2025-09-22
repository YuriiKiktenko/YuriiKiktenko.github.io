---
title: "Yurii Kiktenko — Data Engineer"
layout: page
---

<style>
:root {
  --bg:#0d1117; --fg:#e6edf3; --muted:#9daabc; --card:#161b22; --border:#30363d; --accent:#58a6ff;
}
.page-content { max-width: 960px; }
.hero { margin: 2.2rem 0 1.2rem; }
.hero h1 { margin: 0 0 .4rem 0; }
.sub { color: var(--muted); font-size: 1.05rem; }
.actions { margin: 1rem 0 1.8rem; display:flex; gap:.6rem; flex-wrap:wrap; }
.btn { padding:.55rem .9rem; border:1px solid var(--border); border-radius:10px; text-decoration:none; color:var(--fg); display:inline-block; }
.btn:hover { border-color:var(--accent); }
.badges { display:flex; flex-wrap:wrap; gap:.4rem; margin:.6rem 0 1.6rem; }
.badges span { border:1px solid var(--border); border-radius:999px; padding:.25rem .6rem; font-size:.9rem; color:var(--muted); }
.grid { display:grid; gap:14px; grid-template-columns: repeat(auto-fit, minmax(260px, 1fr)); }
.card { display:block; background:var(--card); border:1px solid var(--border); border-radius:14px; padding:16px; text-decoration:none; color:var(--fg); }
.card:hover { border-color:var(--accent); transform: translateY(-2px); transition: .12s ease; }
.card h3 { margin:.1rem 0 .4rem 0; }
.card p { margin:.2rem 0 .6rem 0; color:var(--muted); }
.card .meta { font-size:.9rem; color:var(--muted); }
.footer-note { margin-top: 26px; color: var(--muted); font-size: .95rem; }
</style>

<div class="hero">
  <h1>Hi, I'm Yurii — Data Engineer</h1>
  <p class="sub">I build reliable data pipelines with <strong>Spark (PySpark)</strong>, <strong>Airflow</strong>, <strong>Kafka</strong>, and <strong>GCP</strong>.</p>
  <div class="actions">
    <a class="btn" href="https://github.com/YuriiKiktenko">GitHub</a>
    <a class="btn" href="https://www.linkedin.com/" target="_blank" rel="noopener">LinkedIn</a>
    <a class="btn" href="mailto:you@email.com">Email</a>
  </div>
  <div class="badges">
    <span>Python</span><span>PySpark</span><span>Airflow</span><span>Kafka</span><span>GCP</span><span>Docker</span>
  </div>
</div>

## Portfolio

<div class="grid">

  <a class="card" href="https://github.com/YuriiKiktenko/de-batch-etl">
    <h3>Batch ETL (PySpark) → Parquet</h3>
    <p>CSV ➜ transformations ➜ per-product aggregates ➜ Parquet output.</p>
    <div class="meta">Stack: PySpark 3.5 • Python 3.11 • pandas • pyarrow</div>
  </a>

  <!-- Duplicate this block for future projects
  <a class="card" href="https://github.com/YuriiKiktenko/<repo>">
    <h3>Streaming: Kafka → Spark Structured Streaming</h3>
    <p>Event ingestion, windowed aggregations, Data Lake zones (raw/processed).</p>
    <div class="meta">Stack: Kafka • Spark • GCS/S3</div>
  </a>
  -->

</div>

<div class="footer-note">
  Next up: Airflow DAG (daily), Kafka → Spark Streaming → Data Lake.  
  This site is built with GitHub Pages (Jekyll Minima).
</div>