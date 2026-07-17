<p align="center">
  <img src="assets/jellyfish.svg" alt="Jellymint AI Animation" width="220" height="286" />
</p>

<h1 align="center">🍃 Jellymint AI</h1>

<p align="center">
  <strong>Self-Hosted Local LLM Platform · Powered by Raspberry Pi 5 · Privacy-First AI</strong>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Raspberry_Pi_5-C51A4A?style=for-the-badge&logo=raspberrypi&logoColor=white" alt="Raspberry Pi" />
  <img src="https://img.shields.io/badge/Runtime-Ollama-0969DA?style=for-the-badge&logo=ollama&logoColor=white" alt="Ollama" />
  <img src="https://img.shields.io/badge/Backend-Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white" alt="Node.js" />
  <img src="https://img.shields.io/badge/Database-Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black" alt="Firebase" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/License-MIT-blue?style=flat-square" alt="License" />
  <img src="https://img.shields.io/badge/Version-2.0-4ECCA3?style=flat-square" alt="Version" />
  <img src="https://img.shields.io/badge/Models-DeepSeek_%7C_Qwen-purple?style=flat-square" alt="Models" />
  <img src="https://img.shields.io/badge/Search-SearXNG-orange?style=flat-square" alt="SearXNG" />
</p>

---

<p align="center">
  <img src="assets/banner.png" alt="Jellymint AI Banner" width="100%" style="border-radius: 12px;" />
</p>

---

## 🌟 Overview

**Jellymint AI** is a production-grade, self-hosted AI assistant platform that leverages local hardware to provide a high-performance, private alternative to cloud-based LLM services. Combining local inference with a real-time web search metasearch engine and a real-time sync layer, Jellymint delivers a premium, low-latency AI experience with complete data sovereignty.

Designed to be hosted on edge hardware like the **Raspberry Pi 5** and GPU-accelerated node clusters, Jellymint handles advanced AI workflows—such as multi-model consensus, autonomous agentic loops, real-time document analysis, and smart traffic load balancing—entirely within your private network.

---

## ✨ Key Features

* 🔒 **100% Data Privacy**  
  All LLM inference and web search aggregation run locally on your own network. Zero conversation history or query metadata is sent to third-party AI companies.
  
* ⚡ **Decentralized Multi-Server Load Balancer**  
  Features an active failover system that distributes traffic between a primary GPU-accelerated machine (for heavy tasks) and an edge node (like the Raspberry Pi 5) acting as a sentinel backup, achieving high availability.
  
* 🤖 **Autonomous Agentic Loops**  
  An execution sandbox that allows the local model to perform multi-step reasoning, plan tasks in a thought loop, and execute local tools (like filesystem operations, web search, or web scraping) to fulfill complex user goals.
  
* 🔀 **Merged LLM Consensus Mode**  
  Query multiple models in parallel (e.g. Qwen for reasoning and DeepSeek for coding) and dynamically synthesize their outputs into a single, high-quality, optimal response.
  
* 🌐 **RAG-lite Web Search Augmentation**  
  Integrates a privacy-respecting local metasearch engine (SearXNG) to dynamically crawl, filter, and inject up-to-date internet snippets as context to answer time-sensitive queries.
  
* 📊 **Enterprise Admin Dashboard**  
  Real-time control panel with live hardware sparklines (CPU, RAM, Temp, Fan RPM), detailed user access metrics, dynamic maintenance controls, and customizable token usage parameters.
  
* 📁 **Smart Document Parsers**  
  Upload and analyze documents (PDF, DOCX, TXT) processed locally on the edge, supporting tier-based constraints and token usage controls.
  
* ⏱️ **Token Economy Engine**  
  A rolling usage-quota manager with Free, Pro, and Advanced tiers, offering users transparent, real-time statistics of their daily resource allowances.
  
* 🎨 **Premium Glassmorphic Interface**  
  A dark-themed, highly responsive user interface with custom animations, live theme toggles, markdown rendering, and syntax-highlighted code blocks.

---

## 🏗️ Conceptual Infrastructure

Jellymint operates on a secure hybrid architecture that decouples UI rendering from inference execution:

1. **Client Layer**: A modern Single Page Application (SPA) designed with vanilla performance optimizations, hosted on a global CDN edge.
2. **Gateway Router**: A Node.js backend running on local hardware that acts as a secure reverse proxy, handling authentication, token limits, and traffic routing.
3. **Inference Nodes**: Local runtimes (Ollama) hosting specialized models. An intelligent coordinator balances workloads based on active hardware load and availability.
4. **Metasearch Engine**: A containerized, local search engine that aggregates search results across multiple indexes while stripping tracking telemetry.
5. **Real-time Sync**: A lightweight cloud sync layer managing profile configurations, tiered system settings, and session metadata.

---

## 🧪 Tech Stack

* **Frontend**: Vanilla JavaScript, CSS custom variables, Vite (Build Tool)
* **Backend**: Node.js, Express.js
* **AI Runtime**: Ollama (Local Model Engine)
* **Models**: DeepSeek Coder, Qwen 2.5, Nomic Embed
* **Search Integration**: Containerized SearXNG
* **Database & Identity**: Firebase (Authentication & Firestore)
* **Target Hardware**: Raspberry Pi 5 (8GB) & GPU-accelerated workstation nodes

---

## 🗺️ Future Roadmap

- [x] Multi-node load balancing & high-availability failover cluster
- [x] Merged LLM synthesis mode
- [x] Agentic AI execution loop & tool sandbox
- [x] Locally hosted metasearch integration
- [x] Tiered token economy and daily allowances
- [x] Audio streaming & real-time TTS engines
- [ ] Mobile-native application
- [ ] High-density local Vector Database (Qdrant/Chroma) integration
- [ ] Extended custom plugin system for advanced system tools

---

## 📄 License

This project is licensed under the MIT License.

---

<p align="center">
  <img src="assets/logo.png" alt="Jellymint" width="48" />
  <br/>
  <strong>Built by MintFire</strong>
  <br/>
  <sub>Running AI, locally. Privately. Beautifully.</sub>
</p>
