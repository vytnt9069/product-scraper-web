git clone https://github.com/tai-khoan-cua-ban/product-scraper-web.git
cd product-scraper-web
product-scraper-web/
│
├── backend/
│   └── index.js         <-- server Node.js
│   └── package.json     <-- thông tin npm
│
├── frontend/
│   └── index.html       <-- giao diện
│
├── README.md
{
  "name": "scraper-backend",
  "version": "1.0.0",
  "main": "index.js",
  "scripts": {
    "start": "node index.js"
  },
  "dependencies": {
    "cors": "^2.8.5",
    "express": "^4.18.2",
    "puppeteer": "^21.3.8"
  }
}
git add .
git commit -m "init frontend and backend"
git push origin main

