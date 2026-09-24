# NoCapMail 🕸️ | Dynamic PCAP Analyzer

**NoCapMail** is a lightweight, high-performance FastAPI web application designed to analyze network capture files (`.pcap`, `.cap`, `.pcapng`) for email security risks. Featuring an immersive "spider-web" burgundy aesthetic, it dynamically inspects file properties to calculate security metrics, flag unencrypted streams, and provide step-by-step developer resolution guides.

![Python Version](https://img.shields.io/badge/Python-3.8%252B-blue?style=flat-square)
![FastAPI](https://img.shields.io/badge/FastAPI-0.100%252B-teal?style=flat-square)
![License](https://img.shields.io/badge/License-MIT-red?style=flat-square)

---

## 🕷️ Features

* **Dynamic Packet Intelligence:** Automatically parses file metadata and attributes to calculate custom risk scores, conversation counts, and anomaly metrics.
* **Immersive Theme:** Custom Tailwind CSS configuration featuring a dark burgundy "spider-web" grid aesthetic with smooth interactive transitions and loading overlays.
* **Actionable Remediation Guides:** Breaks down vulnerabilities (such as unencrypted IMAP/SMTP streams or legacy TLS cipher suites) with beginner-friendly drop-down resolution steps.
* **Zero-Database Setup:** Stateless design that processes uploads securely on the fly.

---

## 🛠️ Tech Stack

* **Backend:** FastAPI, Uvicorn, Python-Multipart
* **Frontend:** HTML5, Tailwind CSS (via CDN)
* **Hosting Support:** Render, Railway, or local Uvicorn server

---

## 🚀 Local Installation & Quickstart

Follow these steps to run NoCapMail locally on your machine:

1. **Clone or download the repository:**
   ```bash
   git clone [https://github.com/YOUR-USERNAME/nocapmail.git](https://github.com/YOUR-USERNAME/nocapmail.git)
   cd nocapmail
