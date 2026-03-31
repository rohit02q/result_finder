🎯 Result Finder Pro

A fast, mobile-first web tool to fetch, filter, and rank student results using an API.

Built with pure HTML, CSS, and JavaScript — no frameworks, no backend.

---

🚀 Features

- 🔍 Search results using Roll Code + Roll Range
- ⚡ Fast fetching with parallel requests + batching
- 📊 Filter results by Min / Max Marks
- 🏆 Auto-sorted results (High → Low)
- 📱 Fully mobile optimized UI
- 📈 Live progress bar + status tracking
- 💾 Export results as CSV file
- 🎨 Clean modern light theme UI

---

🛠️ How It Works

1. User inputs:
   
   - Roll Code
   - Start Range
   - End Range
   - Min Marks
   - Max Marks

2. The app:
   
   - Generates roll numbers ("2600000 + index")
   - Calls API for each roll number
   - Filters valid results
   - Sorts by marks (descending)
   - Displays in table

---

🌐 API Used

https://my-results.onrender.com/result?roll_code=XXXX&rollno=YYYYYYY

- "roll_code" → User input
- "rollno" → Generated roll number

---

📦 Project Structure

📁 result-finder-pro
 ├── index.html   # Complete app (UI + Logic)
 └── README.md

---

⚡ Performance Strategy

- Uses batch processing (10 requests at a time) to avoid API overload
- Uses Promise.all() for parallel execution
- Displays real-time progress

---

📸 UI Preview

«Clean, minimal, mobile-first interface with:»

- Input form
- Progress bar
- Result table
- Download button

---

💻 How to Use

1. Clone repo:

git clone https://github.com/your-username/result-finder-pro.git

2. Open:

index.html

3. Enter inputs and click:

Check Results

---

📥 Export Data

Click Download CSV to export results.

---

⚠️ Disclaimer

- This tool depends on a public API.
- Avoid sending too many requests at once.
- Intended for educational use only.

---

🚀 Future Improvements

- 🔎 Search by name
- 🥇 Topper highlighting
- 🌍 Online hosting + shareable links
- 🔐 Backend caching for ultra-fast results

---

👨‍💻 Author

Rohit

- Class 11 Student 🚀
- Passionate about Web Dev & Problem Solving

---

⭐ Support

If you like this project:

- ⭐ Star the repo
- 📢 Share with friends
- 💡 Suggest improvements

---

📜 License

MIT License
