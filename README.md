#  Komlavi Practice App

A simple Node.js project built by **Komlavi Gidi (@amenvi18-tech)** to simulate the **Clipboard Health** coding challenge.  
This app fetches fake healthcare provider data from a public API, processes it, and summarizes users by city.

---

## Features
- Fetches provider data from a REST API (`jsonplaceholder.typicode.com`)
- Prints provider names, emails, and cities
- Summarizes how many providers live in each city
- Uses **async/await**, **ES modules**, and **node-fetch**
- Fully compatible with **Node.js v18+**

---

## Tech Stack
- **Node.js**
- **JavaScript (ES Modules)**
- **node-fetch**
- **Git / GitHub**

---

##  Installation & Setup

###  Clone the repository
```bash
git clone https://github.com/amenvi18-tech/komlavi.git
cd komlavi




2️⃣ Install dependencies
npm install

3️⃣ Run the app
npm start

 Example Output
 Fetching provider data...
✅ Fetched 10 users.

 Summary by City:
Gwenborough - 2 users
McKenziehaven - 3 users
Wisokyburgh - 1 user

Project Structure
komlavi/
│
├── src/
│   ├── fetchProviders.js       # Main script - fetch & display data
│   └── utils/
│       └── summarize.js        # Helper for summarizing by city
│
├── package.json                # Project metadata and dependencies
├── .gitignore                  # Ignores node_modules and logs
└── README.md                   # Project documentation

Author

Komlavi Gidi
 GitHub: @amenvi18-tech

 Email: arogidi@gmail.com

 License

This project is licensed under the MIT License.
You’re free to use and modify it for your own learning and practice.


---

##  How to Add It
In your **Command Prompt**:

```cmd
cd C:\Users\amen\Desktop\apps\clipboard-health-practice
echo.> README.md
notepad README.md


Paste the content above, save, and close Notepad.

Then commit and push:

git add README.md
git commit -m "Add professional README"
