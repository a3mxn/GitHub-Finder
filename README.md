# GitHub Finder

A web application built using **React**, **TailwindCSS**, and the **GitHub API** that allows users to search for GitHub profiles and view user details such as repositories, followers, and following count.

## Live Demo
[Click Here](https://git-hub-finder-five-lovat.vercel.app/)

## Features

- Search GitHub users by their username
- Display profile details (avatar, bio, location, etc.)
- View a list of repositories with details (name, stars, forks)
- Responsive design using TailwindCSS
- Fast API requests to GitHub using Personal Access Token

## Tech Stack

- **React**: JavaScript library for building user interfaces
- **TailwindCSS**: Utility-first CSS framework for responsive design
- **GitHub API**: To fetch GitHub user data
- **Axios**: For making HTTP requests to the GitHub API

## Installation

1. Clone the repository:
   ```bash
   https://github.com/a3mxn/GitHub-Finder.git
   cd GitHub-Finder
2. Install Dependencies
   ```bash
   npm run build
3. Setup Environment variables
   ```sample .env
   REACT_APP_GITHUB_URL=https://api.github.com/
   REACT_APP_GITHUB_TOKEN=your-github-token-here
4. start
   ```bash
   npm start
