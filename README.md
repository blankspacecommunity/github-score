# GitHub User Scoring

This project aims to calculate a score for a GitHub user based on their public repository metrics such as stars, commits, pull requests (PRs), and issues. The score provides an overall assessment of the user's activity and contributions on GitHub.

## Table of Contents

- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)
- [Customization](#customization)
- [License](#license)

## Introduction

GitHub User Scoring is a JavaScript application that utilizes the GitHub public API to gather data for the specified user. It fetches information about the user's public repositories and calculates a score based on different metrics.

The scoring mechanism in this project considers two categories: "Development" (stars and commits) and "Contribution" (PRs and issues). Each category is assigned a weight, and the final score is calculated by combining the scores of both categories.

Additionally, based on the final score, the project categorizes users into different types, such as "Newbie," "Intermediate," or "Experienced," providing insights into the user's level of engagement and activity on GitHub.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/github-user-scoring.git
   ```

2. Navigate to the project directory:

   ```bash
   cd github-user-scoring
   ```

3. Install the dependencies:

   ```bash
   npm install
   ```

## Usage

1. Open the `index.js` file in a text editor.

2. Modify the `calculateGitHubScore` function by providing the GitHub username of the user you want to calculate the score for:

   ```javascript
   calculateGitHubScore("username");
   ```

3. Save the changes to `index.js`.

4. Run the application:

   ```bash
   node index.js
   ```

   The application will fetch the necessary data from the GitHub API and display the results in the console, including the total stars, commits, PRs, issues, category scores, final score, category label, and user type.

## Customization

You can customize the scoring logic by adjusting the weights assigned to each category or by modifying the user type thresholds in the code. Additionally, feel free to extend the functionality by adding more metrics or implementing additional features based on your requirements.

## License

This project is licensed under the [MIT License](LICENSE).

---
