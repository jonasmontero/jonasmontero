<div align="center">

# Jonas Montero
### Software Engineer · Systems, Backend & Developer Tooling

<p align="center">
  <a href="https://github.com/jonasmontero">
    <img src="https://img.shields.io/badge/Focus-Systems_Programming_&_Developer_Tooling-0284C7?style=flat-square" alt="Focus">
  </a>
  <a href="https://github.com/jonasmontero">
    <img src="https://img.shields.io/badge/Stack-Rust_•_C++_•_Go_•_TypeScript_•_Wasm-0F172A?style=flat-square" alt="Stack">
  </a>
  <a href="https://github.com/jonasmontero">
    <img src="https://img.shields.io/badge/Protocol-Model_Context_Protocol_(MCP)-10B981?style=flat-square" alt="MCP">
  </a>
</p>

<p align="center">
  Building developer tooling, color-science runtimes, and backend services with Rust, C++, Go, and WebAssembly.
</p>

---

</div>

## About & Engineering Focus

- **Systems Programming:** Writing deterministic, memory-safe software in **Rust**, **C++**, and **Go**.
- **Perceptual UI & WebAssembly:** Implementing color-science models (OKLCH, APCA contrast math, CVD simulation matrices) compiled to **WebAssembly** with **TypeScript** tooling.
- **AI Protocols & Developer Tooling:** Architecting native **Model Context Protocol (MCP)** JSON-RPC 2.0 servers for IDE agents to inspect codebase ASTs and design tokens.
- **Infrastructure & Provisioning:** Automated server provisioning suites and container orchestration workflows for Ubuntu 24.04 LTS.

---

## Featured Engineering Projects

<table>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/jonasmontero/rustbook-ds">rustbook</a></h3>
      <p><b>Component isolation and documentation engine in Rust & WebAssembly.</b></p>
      <ul>
        <li>Native Axum HTTP server with <code>&lt; 5ms</code> startup time.</li>
        <li>Client-side color calculations via WebAssembly.</li>
        <li>Autodocs specification mode, live knobs, and built-in Model Context Protocol (MCP) server.</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/Rust-DEA584?style=flat-square&logo=rust&logoColor=white" alt="Rust" />
        <img src="https://img.shields.io/badge/WebAssembly-654FF0?style=flat-square&logo=webassembly&logoColor=white" alt="Wasm" />
        <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
      </p>
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/jonasmontero/colorust">colorust</a></h3>
      <p><b>Color-science engine implementing OKLCH, APCA contrast math, and CVD simulation.</b></p>
      <ul>
        <li>OKLCH, Oklab, and sRGB bidirectional conversion pipelines.</li>
        <li>Real-time APCA (Advanced Perceptual Contrast Algorithm) & WCAG 2.1 auditing.</li>
        <li>11-step perceptual tonal palette generator and spectral CVD simulation matrices.</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/Rust-DEA584?style=flat-square&logo=rust&logoColor=white" alt="Rust" />
        <img src="https://img.shields.io/badge/Color_Science-0284C7?style=flat-square" alt="Color Science" />
        <img src="https://img.shields.io/badge/APCA_/_WCAG-10B981?style=flat-square" alt="Accessibility" />
      </p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/jonasmontero/vps-bootstrap">vps-bootstrap</a></h3>
      <p><b>Automated server provisioning suite for Ubuntu 24.04 LTS.</b></p>
      <ul>
        <li>Automated security baseline: SSH key hardening, UFW firewall, Fail2ban, and auto-updates.</li>
        <li>Containerized orchestration with Docker, Caddy reverse proxy, and automated TLS certificates.</li>
        <li>Idempotent POSIX shell scripts with verification test harness.</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnu-bash&logoColor=white" alt="Bash" />
        <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker" />
        <img src="https://img.shields.io/badge/Security-Hardening-DC2626?style=flat-square" alt="Security" />
      </p>
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/jonasmontero/qr-code-generator">qr-code-generator</a></h3>
      <p><b>QR Code generator in C++17 implementing ISO/IEC 18004 standards.</b></p>
      <ul>
        <li>Bit-level Reed-Solomon error correction (levels L, M, Q, H) and matrix masking.</li>
        <li>Vector SVG generation without dynamic heap allocations.</li>
        <li>Engineered for deterministic batch generation in backend pipelines.</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/C++-00599C?style=flat-square&logo=c%2B%2B&logoColor=white" alt="C++" />
        <img src="https://img.shields.io/badge/Algorithms-8B5CF6?style=flat-square" alt="Algorithms" />
        <img src="https://img.shields.io/badge/Vector_SVG-F97316?style=flat-square" alt="SVG" />
      </p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/jonasmontero/lead-phone-validator">lead-phone-validator</a></h3>
      <p><b>Phone number and lead validation microservice in Go.</b></p>
      <ul>
        <li>Concurrent E.164 parsing, carrier detection, and syntax normalization.</li>
        <li>Low memory footprint designed for batch ingest pipelines and horizontal scaling.</li>
        <li>Deterministic error handling and RESTful API endpoints.</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white" alt="Go" />
        <img src="https://img.shields.io/badge/Concurrency-0284C7?style=flat-square" alt="Concurrency" />
        <img src="https://img.shields.io/badge/Microservice-64748B?style=flat-square" alt="Microservice" />
      </p>
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/jonasmontero/PRD-MCP-Server">PRD-MCP-Server</a></h3>
      <p><b>Model Context Protocol (MCP) server for codebase-aware PRD generation.</b></p>
      <ul>
        <li>Bridges IDEs and AI agents directly to repository architectural state.</li>
        <li>Extracts structural dependencies, schemas, and ASTs deterministically.</li>
        <li>Generates Product Requirement Documents aligned with active source code.</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/MCP-Protocol-10B981?style=flat-square" alt="MCP" />
        <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
        <img src="https://img.shields.io/badge/AI_Tooling-6366F1?style=flat-square" alt="AI Tooling" />
      </p>
    </td>
  </tr>
  <tr>
    <td colspan="2" valign="top">
      <h3><a href="https://github.com/jonasmontero/ivoyager">ivoyager</a></h3>
      <p><b>Offline-first multi-currency financial suite and geospatial radar mapping.</b></p>
      <ul>
        <li>Local-first IndexedDB caching architecture with optimistic sync pipelines.</li>
        <li>Multi-currency exchange calculations with localized tax engines.</li>
        <li>Interactive geospatial radar with hardware acceleration and offline support.</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
        <img src="https://img.shields.io/badge/Offline--First-059669?style=flat-square" alt="Offline First" />
        <img src="https://img.shields.io/badge/Geospatial-0284C7?style=flat-square" alt="Geospatial" />
        <img src="https://img.shields.io/badge/PWA-5A0FC8?style=flat-square" alt="PWA" />
      </p>
    </td>
  </tr>
</table>

---

## Technical Skills

| Domain | Technologies & Tooling |
| :--- | :--- |
| **Systems & Low-Level** | Rust, C++, Go, WebAssembly (Wasm), POSIX Shell, Tokio, Axum |
| **Frontend & Developer Tooling** | TypeScript, Angular, React, Next.js, Web Components, SCSS, OKLCH Design Tokens |
| **AI Systems & Protocols** | Model Context Protocol (MCP), Agent Tooling, JSON-RPC 2.0 Server Architectures |
| **Infrastructure & DevOps** | Linux (Ubuntu 24.04 LTS), Docker, Caddy, Tailscale, UFW, Fail2ban, GitHub Actions, CI/CD |
| **Quality & Standards** | APCA & WCAG 2.1 (AA/AAA), TDD, Static Analysis, Deterministic Memory Management |

---

## GitHub Metrics & Ecosystem Overview

<div align="center">

| Public Repositories | Core Languages | AI & Protocols | Infrastructure |
| :---: | :---: | :---: | :---: |
| **8 Public Repos** | **Rust • C++ • Go • TypeScript** | **Model Context Protocol (MCP)** | **Ubuntu 24.04 LTS • Docker** |

<br>

<p align="center">
  <img src="https://img.shields.io/badge/Primary_Stack-Rust_•_C++_•_Go_•_TypeScript_•_Wasm-0284C7?style=flat-square&labelColor=0F172A" alt="Primary Stack" />
  <img src="https://img.shields.io/badge/Architecture-Type--Safe_•_Deterministic_•_Accessible-10B981?style=flat-square&labelColor=0F172A" alt="Architecture" />
  <img src="https://img.shields.io/badge/CI_/_CD-GitHub_Actions_•_Automated_Testing-8B5CF6?style=flat-square&logo=githubactions&logoColor=white&labelColor=0F172A" alt="CI/CD" />
</p>

</div>

---

## Connect

<div align="center">
  <a href="https://github.com/jonasmontero">
    <img src="https://img.shields.io/badge/GitHub-jonasmontero-181717?style=flat-square&logo=github&logoColor=white" alt="GitHub" />
  </a>
  <a href="https://linkedin.com/in/jonasmontero">
    <img src="https://img.shields.io/badge/LinkedIn-jonasmontero-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="mailto:jonasmontero@users.noreply.github.com">
    <img src="https://img.shields.io/badge/Email-Get_in_Touch-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email" />
  </a>
</div>
