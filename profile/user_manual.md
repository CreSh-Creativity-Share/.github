# User Manual

### Authorization
Cresh allows users who are not logged in to view content, but some actions will not be available.

To log into the system, press the login icon in the upper right corner. 

<img width="96" alt="image" src="https://github.com/CreSh-Creativity-Share/.github/assets/18706771/82341d58-39d8-4117-9542-b8e042f06269">

A login window will appear, requiring an email and password. If you don't have an account, you can press Sign Up, while if you forget your password, you can press "Reset password."

Naturally, there is also a logout button. You can find it in the upper right corner, after pressing on the user profile.

<img width="175" alt="image" src="https://github.com/CreSh-Creativity-Share/.github/assets/18706771/23b12425-3953-45dc-9e5c-7a8f665f2eac">

### Wall

Wall view is the main view of the application. On it, you can find the latest and greatest ideas that have come into the system. There are 3 views prepared for the user:
 - Top - the best ideas from different time frames,
 - For You - a personalized view of posts selected for you,
 - Followed - ideas followed by you, your stash of ideas.

#### Short Post View

The displayed ideas include basic information and a brief description. If you want to see a detailed view that includes additional information, such as AI analysis press the title of the idea, or if it is displayed "See more".

If you like any of the ideas, you can save them in the Followed tab by pressing the bell.

You can also interact with the idea. The heart button gives the idea a like, while the comment button allows you to see the main comments and write your own.

If, on the other hand, you are interested in the author of the idea, you can press on his name or photo to go
to his or her profile.

### Detail Post View

The detailed view has all the functionality of the [Short Post View](#short-post-view). It does, however, include [AI analysis](#ai-analysis) by friendly artificial intelligence and allows you to review all comments.

### AI Analysis

We decided to support your creativity with artificial intelligence. Each idea is analyzed by AI, which uses IAP methodology to describe the project. We implemented metrics and asked ChatGPT to rate the idea on a scale of 1-5. You can find the results in the detailed view of the post. We have divided the 32 metrics into 5 categories that describe the idea in simple terms.

| Metric shortcut  | Metric full name  |
|---|---|
| TVG  | Technical Viability Group  |
| MVG  | Market Viability Group  |
| PVG  | Product Viability Group  |
| MSG  | Market Strategy Group  |
| RFVG  | Risk and Financial Viability Group  |

An idea's score is a percentage of the total points scored by the idea. To analyze the component metrics in detail, go to the detailed view by pressing the "See more" button. The components are the basic metrics calculated by ChatGPT, which, when grouped and averaged, give the value of the basic metrics.

#### Not visible analysis.
The analysis usually takes a few minutes to complete, which means it will not be immediately visible. We will send you a notification when it is generated.

### Search

Cresh is prepared to manage a large number of ideas. To find our way through the vastness of human creativity, we have implemented search functionality. You can find it by clicking the magnifying glass button in the footer of the page.

<img width="78" alt="image" src="https://github.com/CreSh-Creativity-Share/.github/assets/18706771/268da2d8-e1b6-45fd-9342-9d34a06cc41f">

Searching can be done under 2 parameters:
 * tags,
 * title.

To search by tags, just type the "#" symbol, a list of the most popular tags will then appear, which will filter as you type the letters. Next to it, it is possible to type words to reduce the scope of the search.

Search built this way allows you to follow specific hashtags.

### User Profile

Each user's profile picture and name takes you to the user's profile. You can find yours by clicking on your photo in the upper right corner and selecting "Profile" in the menu.

<img width="176" alt="image" src="https://github.com/CreSh-Creativity-Share/.github/assets/18706771/2e579536-473c-4a34-b53c-bc915664dde1">

Your user profile has several additional functionalities:
 * by pressing on the photo you can change it,
 * you have a "New Post" button,
 * you have the possibility to change your data through the "Edit profile" button.

Below are the three tabs that will be displayed for each user:
 * Posts - posts added by the user,
 * Likes - posts that got likes from the user,
 * Saved - posts that the user follows.

### Notification

At Cresh, we wanted to make it easier for users to follow the development of ideas, so we introduced notification. Any action that takes place in your or a follower's post will be sent to you in the form of a notification. You can access it by pressing the bell button in the footer of the page.

<img width="58" alt="image" src="https://github.com/CreSh-Creativity-Share/.github/assets/18706771/ba6f5c1a-dc4a-4d20-8000-a4dc280b47f0">

A counter on the bell indicates the number of unread notifications.

Notifications have a read marker and are displayed chronologically from the youngest. If you press a notification, you will be taken to the notification source.
