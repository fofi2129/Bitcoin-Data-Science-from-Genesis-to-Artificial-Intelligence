
Here's everything you need — download the file above first, then follow these steps exactly.

Step 1 — Download the website file
Click the file above to download index.html. Save it somewhere you'll remember, for example:
~/Desktop/bitcoin-ds/index.html

Step 2 — Open a terminal
macOS: Press Cmd + Space, type Terminal, hit Enter
Windows: Press Win + R, type cmd, hit Enter (or open PowerShell)
Linux: Ctrl + Alt + T

Step 3 — Navigate to the folder
# macOS / Linux
cd ~/Desktop/bitcoin-ds
# Windows
cd %USERPROFILE%\Desktop\bitcoin-ds

Step 4 — Check if Python is installed
python3 --version
# Should show: Python 3.x.x
# Windows may need:
python --version
If Python isn't installed, download it free from python.org/downloads — any version 3.8+ works.

Step 5 — Start the local server
# macOS / Linux
python3 -m http.server 8080
# Windows
python -m http.server 8080
You'll see:
Serving HTTP on 0.0.0.0 port 8080 (http://0.0.0.0:8080/) ...

Step 6 — Open the website
Open any browser and go to:
http://localhost:8080
The website loads with the live Bitcoin ticker, full module navigation, sidebar, all 27 modules, and the live dashboard pulling real BTC price and blockchain stats from free APIs.

Step 7 — Stop the server
When you're done, go back to the terminal and press:
Ctrl + C

That's it. Three things to know once it's running:
Sidebar — click any module (M0 through M26) to open its full topic tree, sub-topics, code preview, and deliverable description.
Live Dashboard — the top nav has a Live Dashboard page showing real BTC price, block height, hash rate, difficulty, and halving countdown fetched from blockchain.info and CoinGecko — both free, no API key needed.
No internet needed for the website itself — only the live metrics on the dashboard require a connection. All navigation, content, and code previews work fully offline.
<img width="829" height="911" alt="image" src="https://github.com/user-attachments/assets/07c55ec9-b2b0-4689-bfb7-e329fdb727cb" />

