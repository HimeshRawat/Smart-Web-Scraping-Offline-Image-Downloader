# Smart-Web-Scraping-Offline-Image-Downloader
This project demonstrates an efficient web scraping workflow using Python. The scraper works in two phases:

1 . Offline Page Collection → Scrapes all available pages from the target website (in this case, 50 pages) and stores them in an HTMLs folder. This avoids the need to repeatedly hit the live website.

2 . Image Extraction → Extracts and downloads images from the saved HTML files into an Images folder. Users can also select specific page ranges (e.g., pages 1–5 or 10–20) for image downloads.

This approach ensures faster execution, reduced server load, and flexible data handling.

🎯 Key Features

📂 Save website pages offline for reuse.

🖼️ Download all images from saved pages.

🔢 Selective range-based image downloads (e.g., Page 1–5, 10–20).

⚡ Reduces redundant scraping requests to the live website.

🛠️ Modular code for easy customization and future extension.

🛠️ Technologies Used

• Python

• BeautifulSoup (bs4)

• Requests

• OS & File Handling
