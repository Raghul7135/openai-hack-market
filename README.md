# 🛍️ OpenAI Hack Market  
### *An Intelligent Product-Customer Recommendation & Feedback System for Retail*

[![Python](https://img.shields.io/badge/Python-3.9%2B-blue?logo=python)](https://python.org)
[![Flask](https://img.shields.io/badge/Flask-3.0+-black?logo=flask)](https://flask.palletsprojects.com)
[![LightFM](https://img.shields.io/badge/LightFM-1.17-lightblue)](https://github.com/lyst/lightfm)
![License](https://img.shields.io/badge/License-MIT-green)

> 💡 A **hybrid recommendation engine** that bridges *customer needs* (fabric, brand, budget) with *business insights* (trending queries, conversion stats, feedback loops) — designed for clothing/retail domains.

---

## 🌟 Features

### 🔍 For Customers
- ✅ **Natural requirement input**: *"soft cotton shirts, budget ₹800–1200"*
- ✅ **Multi-criteria filtering**: Fabric, brand, price range, quality
- ✅ **Personalized recommendations** using hybrid LightFM (collaborative + content-based)
- ✅ **Feedback loop**: Rate products → improves future suggestions

### 📊 For Business Owners
- ✅ **Live dashboard**: Top fabrics, brands, avg. rating, conversion rate
- ✅ **Requirement insights**: Real-time view of customer queries (e.g., *"85% asked for cotton last week"*)
- ✅ **Product performance**: Views → wishlist → purchase funnel analysis
- ✅ **Cold-start ready**: Uses popularity + metadata for new users/items

### ⚙️ Tech Highlights
- Hybrid LightFM model (WARP loss) — optimal for implicit feedback (`view`, `wishlist`, `purchase`)
- Flask backend + responsive HTML/CSS/JS frontend (no frameworks)
- SQLite (dev) → scalable to PostgreSQL/Snowflake
- CORS-enabled for local frontend-backend integration

---

## 🚀 Quick Start

### 1. Clone & Setup
```bash
git clone https://github.com/Raghul7135/openai-hack-market.git
cd openai-hack-market
python -m venv .venv
.\.venv\Scripts\Activate.ps1    # Windows
# source .venv/bin/activate      # Linux/macOS
