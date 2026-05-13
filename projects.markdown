---
layout: page
title: Projects
permalink: /projects/
---

<section class="projects-section full-width-projects">
  <div class="project-list">
    <article class="project-card">
      <header>
        <p class="project-kicker">PostgreSQL table migration</p>
        <h3><a href="https://github.com/mitayan0/pg-migrate">PG-Migrate</a></h3>
      </header>
      <div class="project-copy">
        <p class="project-overview">A cross-platform PostgreSQL migration tool built with Rust, Tauri, and React. PG-Migrate moves tables, schemas, and records between databases with a focus on speed, safety, and repeatability.</p>
        <ul class="project-highlights">
          <li>Optimized batch writing and keyset pagination for fast, consistent migration of large datasets.</li>
          <li>Schema remapping, foreign-key-aware table ordering, and sequence synchronization for safe cross-database cloning.</li>
          <li>Non-destructive migration options with conflict-safe behavior and optional target truncation.</li>
        </ul>
      </div>
      <footer>
        <p class="project-meta">Rust / Tauri / React / TypeScript / PostgreSQL</p>
      </footer>
    </article>

    <article class="project-card">
      <header>
        <p class="project-kicker">SQL for APIs and data</p>
        <h3><a href="https://github.com/mitayan0/sidol">Sidol</a></h3>
      </header>
      <div class="project-copy">
        <p class="project-overview">A universal SQL interface that lets you query APIs and databases through familiar SQL syntax. Sidol executes reads via DuckDB and routes write operations to connector-backed APIs.</p>
        <ul class="project-highlights">
          <li>Plain SQL access to heterogeneous data sources including ServiceNow, CSV, and SQLite.</li>
          <li>Query parsing with sqlglot, connector-based write routing, and extensibility through a BaseConnector interface.</li>
          <li>Designed for fast exploration, data engineering experiments, and API-backed workflows from one unified layer.</li>
        </ul>
      </div>
      <footer>
        <p class="project-meta">Python / DuckDB / sqlglot / Data connectors</p>
      </footer>
    </article>
  </div>
</section>
