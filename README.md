# Untire React assignment

## News Searching and Saving Application

### Summary
Create a web application using TypeScript, React, and Next.js. The application should allow users to search for news articles using a keyword, view the results in a list, and save selected articles for later viewing. The application should consist of two pages:

- **Search Page**: A page where users can enter a keyword to search for news articles. The search results should be displayed in a list format.
- **Saved Articles Page**: A page where users can view all the news articles they have saved.

You can implement the backend functionality using Next.js API routes.

### Project Setup:
1. Create a new Next.js project with TypeScript enabled.

### News API:
- Use the News API for fetching news articles.
- Get a free API key by signing up on their website.
- The endpoint for fetching news is:
  ```
  http://newsapi.org/v2/everything?apiKey=YOUR_API_KEY&q=USER_SEARCH_INPUT
  ```

### Pages:
#### Search Page:
- Provide an input field for users to type in a keyword.
- Display the search results in a scrollable list.
- Each article in the list should have a button to "Save" the article.

#### Saved Articles Page:
- Display a list of articles the user has saved.
- Allow users to remove articles from the saved list.

### Backend:
- Create API routes to fetch news articles securely without exposing the API key on the frontend.

### Project Assumptions
- Aim to spend no more than **3-4 hours** on this assignment, even if that means the result is incomplete or non-functional.
- Git should be used for version control. Maintain a clear commit history.
- Submit the project via a GitHub repository or as a zip folder.

### Bonus Suggestions
- Implement basic testing using Jest.
- Use ESLint to ensure TypeScript code quality.
- Add a loading indicator while fetching news articles.

### Notes
The intent is to review your efforts together, discussing your process, solution direction, architectural choices, and code implementation.
