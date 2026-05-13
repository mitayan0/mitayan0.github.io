---
layout: page
title: Projects
permalink: /projects/
---

<section class="projects-intro">
  <p>
    A small index of things I have built, studied, worked on, and kept thinking
    about after closing the laptop.
  </p>
</section>

<section class="projects-section" aria-labelledby="selected-projects">
  <div class="section-heading compact-heading">
    <p class="eyebrow">Work</p>
    <h2 id="selected-projects">Selected projects</h2>
  </div>

  <div class="project-list">
    <article class="project-item">
      <div>
        <p class="project-kicker">PostgreSQL table migration</p>
        <h3><a href="https://github.com/mitayan0/pg-migrate">PG-Migrate</a></h3>
      </div>
      <p>
        A cross-platform PostgreSQL migration tool built with Rust, Tauri, and React. PG-Migrate moves tables, schemas, and records between databases with an emphasis on speed and reliability.
      </p>
      <p>
        It uses optimized multi-row batching and keyset pagination to keep large migrations consistent and fast. The tool preserves JSON/JSONB payloads, synchronizes serial sequences, and orders tables by foreign-key dependencies so migrations complete safely.
      </p>
      <p class="project-meta">Rust / Tauri / React / TypeScript / PostgreSQL</p>
    </article>

    <article class="project-item">
      <div>
        <p class="project-kicker">SQL for APIs and data</p>
        <h3><a href="https://github.com/mitayan0/sidol">Sidol</a></h3>
      </div>
      <p>
        A universal SQL layer for APIs and databases. Sidol executes SELECT queries through DuckDB and converts INSERT/UPDATE/DELETE operations into connector-driven write actions.
      </p>
      <p>
        Includes built-in connectors for ServiceNow, CSV, and SQLite, and can be extended by implementing a BaseConnector for new sources. Ideal for working with heterogeneous data from one familiar interface.
      </p>
      <p class="project-meta">Python / DuckDB / sqlglot / Data connectors</p>
    </article>
  </div>
</section>
