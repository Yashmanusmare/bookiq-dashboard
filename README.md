# BookIQ - AI-Powered Book Insight Assistant

BookIQ is a futuristic dashboard designed to analyze library data using a simulated RAG (Retrieval-Augmented Generation) pipeline. It provides real-time insights, automated scraping simulations, and AI-driven literature analysis.

## 📸 Screenshots
![Dashboard](screenshot1.png)
![AI Assistant](screenshot2.png)
![Web Scraper](screenshot3.png)

## 🚀 Setup & Running Instructions
1. Clone the repository: `git clone https://github.com/Yashmanusmare/bookiq-dashboard.git`
2. Navigate to the project folder.
3. Open `index.html` in any modern web browser.
4. (Optional) For the best experience, use the VS Code "Live Server" extension.

## 🤖 API Documentation
- **Core Model:** Claude-3-5-Sonnet (Simulated via Anthropic API architecture).
- **Interface:** RESTful API Simulation handling JSON payloads.
- **RAG Logic:** The system retrieves context from a local `BOOKS` data object, injects it into the prompt context, and generates a response with citations.

## ❓ Sample Questions & Answers (Testing)
**Q: Analyze the themes of Dune.**
**A:** "Dune focuses on political power, ecology, and the messiah complex. [Source: Sci-Fi Archive #2026]"

**Q: Who is the protagonist of The Great Gatsby?**
**A:** "The story is narrated by Nick Carraway, focusing on the mysterious Jay Gatsby. [Source: Classic Literature DB]"

## 🛠️ Testing Samples
To verify functionality, please test the following inputs in the "Ask AI" tab:
1. "Recommend a sci-fi book."
2. "Summarize Dune."
3. "Run Scraper" (in the Scraper tab) to test the data extraction UI logic.

## ⚙️ Technical Stack
- **HTML5/CSS3:** Custom Grid/Flexbox architecture.
- **JavaScript (ES6+):** Async/Await for API simulations.
- **Icons:** Lucide-React methodology.
