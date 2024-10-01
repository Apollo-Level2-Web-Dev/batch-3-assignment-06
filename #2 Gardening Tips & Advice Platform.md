# #2 Gardening Tips & Advice Platform

### **1\. Project Overview**

The **Gardening Tips & Advice Platform** is a comprehensive full-stack web application designed for gardening enthusiasts and professionals to share, discover, and engage with gardening knowledge. It will provide users with insightful tips, plant care advice, seasonal guides, and techniques to enhance their gardening experiences. Additionally, users can share their gardening knowledge, interact with others, and explore premium content through a seamless payment integration.

The platform aims to foster a vibrant community where users can post gardening advice, upvote content, comment, follow other users, and share their experiences. Key features include a **rich text editor** for content creation, **user authentication**, **premium content access via payments**, and **social interaction tools**. It will blend informative gardening content with an interactive community-focused experience.

  

* * *

### **2\. Core Project Objectives**

1. **Develop a full-stack web application** using Next.js, Typescript, MongoDB, Express,, Node.js.
2. **Implement JWT-based user authentication**, ensuring secure login, registration, and profile management.
3. **Create a responsive user interface** that works across devices—mobile, and desktop.
4. **Develop social features**, including upvoting posts, commenting, following other users, and displaying the most popular content. \[break down the most popular content section\]
5. **Build a rich text editor** to allow users to create, edit, and share gardening tips and guides, supporting multimedia content (images, videos, etc.).
6. **Payment Integration**: Integrate payment gateways like **AAMARPAY or Stripe** to access premium gardening contents.
7. **Advanced Search and Filter:** Implement search and filtering features that allow users to find relevant gardening content based on category, popularity, and other parameters.
8. **Develop an admin dashboard** for managing users, posts, payments, and community moderation.

  

* * *

### 3\. Functional Requirements

#### User Authentication:

*   Users must be able to register with an email and password and some other relevant user details.
*   Secure user login and logout with JWT-based authentication.
*   Password recovery and change password option.

**_Note:_** _Do not enforce any additional password complexity (i.e., no uppercase, lowercase, or special character requirements)._

#### User Profile Management:

*   Users can update their personal information, including profile pictures.
*   My Profile section displaying my posts and followers/following.
*   Consider designing it similar to the profile page on Facebook or in the style of X (Twitter).
*   Users can follow/unfollow others.
*   Users can verify their profile once their post has received at least 1 upvotes. Profile verification requires users to pay a certain amount using **AAMARPAY or Stripe**. Verified users will be able to unlock premium contents.
*   Verified users will receive a badge that will be displayed alongside their profile image.

#### Posts Creation & Sharing:

*   Rich Text Editor or Markdown support for creating and editing gardening tips and guides. (i.e., quill, draft.js, slate, froala-editor etc)
*   Ability to attach images to posts, allowing for visual representation of gardening experiences.
*   Posts can be categorized under topics such as Vegetables, Flowers, Landscaping, etc.
*   A modal for post creation, offering a distraction-free user experience.
*   Users can edit or delete their posts.
*   Additionally, posts can be tagged as **Premium**, which will only be accessible to verified users.

#### Upvote & Downvote System:

*   Users can upvote or downvote posts to help others discover the best content.
*   Sorting functionality to display posts with the highest upvotes at the top.

#### Commenting System:

*   Users can comment on posts with options to edit or delete their own comments.
*   Replying on others comment is optional

#### Payment Integration:

*   Integration with Aamarpay/Stripe to allow users to make payments for premium features like exclusive content access.

#### News Feed:

*   A dynamic news feed displaying the latest gardening tips and guides.
*   Infinite scroll to load more content dynamically.
*   Searching and filtering functionality.
*   When searching or filtering, the content should appear sorted by upvote count.

#### Following System:

*   Users can follow other gardeners and view their gardening content.

#### Micro Animations:

*   Smooth transitions, hover effects, and loading animations to enhance the user experience.

#### **Favourite Posts:**

*   Users can click a "favourite" button on posts, which saves them in a "Favourites" section in their profile.

* * *

### 4\. User Interface Design

#### Required Pages:

*   **Login/Registration Page:** Forms for user sign-up and login with secure authentication.
*   **User Dashboard:** A personalized dashboard displaying user-specific content, and followed users and followers.
*   **Admin Dashboard:** A control panel for administrators to manage content, users, and payment history, with graphs for monthly payments, posts, and user activity
*   **Profile Page:** A section for users and admins to view and edit their profiles, including a display of their posts, followers, and followed users.
*   **News-feed:** A page listing all gardening posts, with filtering options by category and other relevant properties.
*   **About Us Page:** Information about the team or organization behind the project, outlining the mission and vision.
*   **Contact Us Page:** A contact form or details for user inquiries and support.
*   **Image gallery Section:** Add an image gallery section to showcase recent gardening images.

####   

* * *

### 5\. Bonus Requirements

**Gardening Quotes:**

*   A feature that displays inspiring gardening quotes on the homepage, motivating users and adding a positive touch to the platform.

**PDF Generation:**

*   Users can generate PDFs of gardening tips/guides or other users' content for offline use.

**Content Sharing:**

*   Enable users to share gardening tips and guides by copying a link. Each post will have a share button, and when the user clicks this button, the specific post URL will be copied to the clipboard

**Unique Feature/Section:**

*   Add a simple, unique feature relevant to your project and mention it in the [README.md](http://readme.md/) file.

  

* * *

###
