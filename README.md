# GitHub Repo Analyzer

![GitHub Repo Analyzer UI](https://via.placeholder.com/1000x500.png?text=GitHub+Repo+Analyzer)

A modern, highly interactive, and premium portfolio-level web application that utilizes the GitHub API to analyze repositories and user profiles. Featuring a visually striking dark glassmorphism design, robust data visualization, and a 3D interface, it's designed to impress.

## ✨ Features

*   **Deep Repository Analysis:** Instant access to stats including Stars, Forks, Open Issues, Contributors count, Primary Language, Size, License, and Visibility.
*   **User Profile Search:** Fetch all public repositories of any GitHub user and easily select one for deep analysis.
*   **Intelligent Search:** Paste a GitHub URL, a `username/repo` string, or just a `username`. The app handles the parsing and API routing automatically.
*   **Premium UI/UX:**
    *   Sleek Dark Mode with neon gradients and soft shadows.
    *   Glassmorphism components (frosted glass effects).
    *   Dynamic background particles and mesh gradients.
    *   3D tilt-hover effects on data cards (powered by Vanilla Tilt).
    *   Number counting animations and smooth UI transitions.
*   **Recent Searches:** Remembers your past queries locally to save you time.
*   **Fully Responsive:** Impeccable experience across Desktop, Tablet, and Mobile.
*   **Robust Error Handling:** Custom error cards instead of native browser popups for rate-limits, missing repos, or invalid inputs.

## 📂 Folder Structure

```text
github-repo-analyzer/
│
├── index.html      # Main HTML structure
├── style.css       # Core styling, animations, and design tokens
├── script.js       # App logic, API fetching, and DOM manipulation
└── README.md       # This documentation file
```

## 🛠️ Technologies Used

*   **HTML5:** Semantic architecture.
*   **CSS3:** Custom properties, Flexbox/Grid, Animations, Backdrop-filters.
*   **Vanilla JavaScript (ES6+):** Async/Await, DOM Manipulation, Fetch API.
*   **GitHub REST API:** Data provider.
*   **FontAwesome:** High-quality scalable vector icons.
*   **Google Fonts:** Modern typography (`Inter` and `Outfit`).
*   **Vanilla-Tilt.js:** 3D hover effects.

## 🚀 How to Run Locally

Since this is a client-side application using vanilla web technologies, running it is incredibly simple.

### Prerequisites
You only need a modern web browser (Chrome, Firefox, Safari, Edge) and optionally a code editor like VS Code.

### Steps
1.  **Clone the Repository:**
    ```bash
    git clone https://github.com/your-username/github-repo-analyzer.git
    cd github-repo-analyzer
    ```
    *(If you downloaded the ZIP, simply extract it and open the folder).*

2.  **Open the Application:**
    *   **Method 1:** Double-click the `index.html` file to open it directly in your default browser.
    *   **Method 2:** If you are using VS Code, install the "Live Server" extension, right-click on `index.html`, and select "Open with Live Server" for hot-reloading as you edit.

3.  **Usage:**
    *   Enter a username (e.g., `torvalds`) to see their repositories.
    *   Enter a repository name (e.g., `facebook/react`) to analyze it instantly.
    *   Click the "Copy Link" or "Open in GitHub" buttons inside the result card to interact with the repository.

## 🤝 How to Contribute

Contributions, issues, and feature requests are highly welcome! This project is great for open-source initiatives like GSSoC.

1.  **Fork the Project**
2.  **Create your Feature Branch:** `git checkout -b feature/AmazingFeature`
3.  **Commit your Changes:** `git commit -m 'Add some AmazingFeature'`
4.  **Push to the Branch:** `git push origin feature/AmazingFeature`
5.  **Open a Pull Request**

### Contribution Ideas:
*   Add light-mode toggle.
*   Implement language-specific color coding for the primary repository language.
*   Add charts (e.g., Chart.js) to show repository language breakdowns.
*   Integrate GitHub Authentication to bypass rate limits.

## 📜 License

Distributed under the MIT License. See `LICENSE` for more information.

---
*Built for GSSoC & Beyond*
