# 🔍 GitHub Finder

A responsive web application that allows users to search for GitHub profiles and explore publicly available GitHub information such as profile details, repositories, followers, and following.

The application integrates with the **GitHub REST API** to retrieve user data dynamically and display it through a clean, interactive interface.

## 🚀 Live Demo

🔗 **Live Application:**
https://github-finder-rouge-five.vercel.app/

## 📌 Overview

**GitHub Finder** is a frontend application designed to make it easier to explore GitHub users and their public activity.

Users can enter a GitHub username and retrieve information directly from the GitHub API. The application dynamically updates the interface based on the API response.

This project demonstrates practical frontend development concepts including API integration, asynchronous programming, dynamic rendering, user input handling, and responsive UI development.

## ✨ Features

* 🔎 Search GitHub users by username
* 👤 Display GitHub profile information
* 🖼️ Display user profile avatar
* 📝 Display profile name and bio
* 📁 Browse public repositories
* 👥 Display followers and following information
* ⚡ Fetch data dynamically using the GitHub REST API
* ❌ Handle invalid usernames
* ⚠️ Handle API request failures
* 📱 Responsive user interface
* 🎨 Modern and clean design
* 🔄 Dynamic UI updates based on API results

## 🛠️ Technologies Used

| Technology                       | Purpose                                    |
| -------------------------------- | ------------------------------------------ |
| **JavaScript**                   | Application logic and API interaction      |
| **HTML**                         | Application structure                      |
| **CSS**                          | Styling and responsive layouts             |
| **Tailwind CSS**                 | Utility-based UI styling                   |
| **GitHub REST API**              | Retrieving GitHub user and repository data |
| **Fetch API / Async JavaScript** | Making API requests                        |
| **JSON**                         | Processing API responses                   |
| **Vercel**                       | Application deployment                     |

## 🧠 Key Concepts Demonstrated

### API Integration

The application communicates with the GitHub REST API to retrieve publicly available GitHub user information.

```text
User enters username
        │
        ▼
GitHub Finder
        │
        ▼
GitHub REST API
        │
        ▼
JSON Response
        │
        ▼
Process API Data
        │
        ▼
Update User Interface
```

### Asynchronous Programming

The application handles API requests asynchronously and processes the returned data before displaying it to the user.

### Dynamic Rendering

Profile and repository information is generated dynamically based on the selected GitHub account.

### Error Handling

The application handles situations such as:

* Invalid GitHub usernames
* Failed API requests
* Empty search submissions
* Missing or unavailable profile information

## 📂 Project Structure

```text
GitHub-Finder/
│
├── public/
│   └── ...
│
├── src/
│   └── ...
│
├── .gitignore
├── .prettierrc.json
├── package.json
├── package-lock.json
├── tailwind.config.js
└── README.md
```

## ⚙️ Getting Started

### Prerequisites

Make sure you have the following installed:

* **Node.js**
* **npm**
* A modern web browser

You can verify Node.js and npm with:

```bash
node --version
npm --version
```

## 📥 Installation

Clone the repository:

```bash
git clone https://github.com/mpatel1802/GitHub-Finder.git
```

Navigate to the project directory:

```bash
cd GitHub-Finder
```

Install the project dependencies:

```bash
npm install
```

## ▶️ Running the Application

Start the development server using the project's configured npm script:

```bash
npm start
```

Then open the local development URL provided by the application.

## 💡 How to Use

1. Open the GitHub Finder application.
2. Enter a GitHub username in the search field.
3. Submit the search.
4. The application sends a request to the GitHub REST API.
5. The returned profile information is displayed.
6. Explore the user's public repositories and GitHub statistics.

For example, searching for:

```text
octocat
```

will retrieve publicly available GitHub information associated with that account.

## 🔗 GitHub API

This project uses the **GitHub REST API** to retrieve public GitHub information.

The application demonstrates how a frontend application can consume an external REST API and transform JSON responses into an interactive user interface.

## 🎯 Project Goals

The main goals of this project were to:

1. Learn how to integrate a real-world REST API into a frontend application.
2. Practice asynchronous JavaScript programming.
3. Work with JSON API responses.
4. Build a dynamic search interface.
5. Implement error handling for API requests.
6. Create a responsive and user-friendly interface.
7. Deploy a frontend application using Vercel.

## 📚 What I Learned

Through this project, I strengthened my understanding of:

* REST APIs
* API requests and responses
* Asynchronous JavaScript
* Fetching external data
* JSON data processing
* DOM/UI updates
* User input handling
* Error handling
* Responsive web design
* Tailwind CSS
* Frontend application architecture
* Git and GitHub
* Web application deployment

## 🔮 Future Improvements

Potential improvements for future versions include:

* [ ] Add repository pagination
* [ ] Display repository stars and forks
* [ ] Display repository languages
* [ ] Add repository search and filtering
* [ ] Add GitHub contribution activity
* [ ] Add search history
* [ ] Add dark mode
* [ ] Add loading animations
* [ ] Add detailed repository pages
* [ ] Improve accessibility
* [ ] Add automated tests

## ⚠️ API Considerations

The application relies on GitHub's public API. API requests may be subject to GitHub's rate limits.

The application only displays publicly available GitHub information.

## 👨‍💻 Author

**Mann Patel**

GitHub: [@mpatel1802](https://github.com/mpatel1802)

## 🤝 Contributing

Contributions are welcome.

To contribute:

1. Fork the repository.
2. Create a new branch.
3. Make your changes.
4. Commit your changes.
5. Push the branch.
6. Open a pull request.

## 📄 License

This project is available for educational and portfolio purposes.
