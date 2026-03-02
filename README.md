# 🛡️ PhishGuard — Real-Time URL Phishing Detector

A real-time URL phishing detection web app based on the research paper:
**"Machine Learning-Based Phishing URL Detection Using Lexical and Structural Features"**
by Kanduri Phaneendra et al., RGMCET, Andhra Pradesh.

---

## 🚀 Live Demo

Just open `index.html` in any browser — no server needed!

---

## 📁 Project Structure

```
phishguard/
├── index.html        # Main app (all-in-one HTML + CSS + JS)
└── README.md         # Documentation
```

---

## ⚙️ How to Deploy

### Option 1 — Netlify (Recommended, Free)
1. Go to [netlify.com](https://netlify.com)
2. Drag and drop this folder → Live in 30 seconds!

### Option 2 — GitHub Pages (Free)
1. Push this folder to a GitHub repo
2. Go to Settings → Pages → Select main branch
3. Your site is live at `https://yourusername.github.io/repo-name`

### Option 3 — Vercel (Free)
1. Go to [vercel.com](https://vercel.com)
2. Import GitHub repo → Auto deploy!

---

## 🧠 Features Extracted (Based on Research Paper)

| Feature | Description |
|---|---|
| url_length | Total characters in URL |
| has_ip_address | IP used instead of domain |
| dot_count | Number of dots in URL |
| https_flag | Presence of HTTPS |
| url_entropy | Randomness of characters |
| token_count | Number of URL tokens |
| subdomain_count | Number of subdomains |
| query_params | Number of query parameters |
| tld | Top-level domain |
| path_length | Length of URL path |
| has_hyphen | Hyphen in domain name |
| digit_count | Total numeric characters |
| susp_extension | Suspicious file extensions |
| domain_length | Length of domain name |
| pct_numeric | Percentage of numeric chars |
| susp_keywords | Suspicious keywords present |

---

## 📊 Model Performance (From Research Paper)

| Metric | Value |
|---|---|
| Accuracy | 99.9% |
| Precision | 0.99 |
| Recall | 0.99 |
| F1-Score | 0.99 |
| Dataset Size | 100,000+ URLs |
| Classifier | Random Forest |

---

## 👨‍💻 Author

**Kanduri Phaneendra**
B.Tech CSE (Cyber Security) — RGMCET, Nandyal
GitHub: [Phaneendra2005](https://github.com/Phaneendra2005)

---

## 📄 License

This project is for educational and research purposes.
