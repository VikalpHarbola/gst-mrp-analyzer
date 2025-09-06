# GST MRP Analyzer

A lightweight web-based tool to analyze the impact of GST (Goods & Services Tax) rate changes on **MRP (Maximum Retail Price)** in India.  
Built for the **Sep 2025 GST notification update**, this calculator helps businesses and consumers quickly compare **current vs proposed GST rates** and see how prices are affected.

---

## 🔗 Live Demo
👉 [GST MRP Analyzer](https://vikalpharbola.github.io/gst-mrp-analyzer/)

---

## ✨ Features
- 🔍 Search or select product categories  
- 📊 Compare **current GST rate vs new GST rate (Sep 2025 update)**  
- 💰 Calculate **Base Price, GST Portion, Proposed Price, and Difference**  
- ⬆️/⬇️ Visual indicators for price increase or decrease  
- 📄 Referenced from [PIB GST Notification, Sep 2025](https://static.pib.gov.in/WriteReadData/specificdocs/documents/2025/sep/doc202594628401.pdf)  

---

## 🖼️ Preview
![Preview Screenshot](assets/preview.png)

---

## 📂 Project Structure
gst-mrp-analyzer/
│
├── index.html # Main app (UI + logic)
├── rates.js # GST rates dataset
├── css/
│ └── style.css # Styling (optional, for cleaner separation)
├── assets/
│ ├── favicon.ico
│ ├── logo.png
│ └── preview.png
├── data/
│ └── rates-2025.json # Optional JSON dataset for future updates
├── docs/
│ └── gst-notification-2025.pdf # Reference notification
├── README.md # Project documentation
└── LICENSE # Open-source license (MIT)