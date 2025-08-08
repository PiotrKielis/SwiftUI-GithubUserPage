GitHubBio is a SwiftUI application that fetches and displays a GitHub user's profile information — including their avatar, username, and bio — using the GitHub REST API.
It’s a lightweight and elegant way to present your GitHub profile in a native iOS interface.


Features:
1.Fetch GitHub user data – Automatically retrieves the profile of a specified GitHub user.
2.Profile picture display – Shows the user's avatar in a clean, circular image view.
3.Username and bio presentation – Displays login and bio text with a simple and modern design.
4.Async image loading – Uses AsyncImage for smooth, asynchronous avatar fetching.
5.Error handling – Gracefully handles invalid URLs, failed responses, and data issues.


How it works:
1.On launch, the app calls the GitHub API to retrieve the specified user's profile data.
2.The JSON response is decoded into a GitHubUser model using JSONDecoder.
3.The UI updates to show the avatar, username, and bio.


Technologies Used
1.SwiftUI for the user interface.
2.AsyncImage for asynchronous image loading.
3.URLSession for networking.
4.Codable for JSON parsing.
5.GitHub REST API for profile data.


Requirements
iOS 16.0+
Xcode 14+
Internet connection to fetch data from the GitHub API.
<img width="345" height="699" alt="Zrzut ekranu 2025-08-8 o 19 51 17" src="https://github.com/user-attachments/assets/e0ef0c0a-a2d2-41d5-80a4-8007bb9d72aa" />

