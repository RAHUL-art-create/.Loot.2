
---

# Loot

**Loot** is a user-friendly web application designed to offer a wide range of exciting deals and reward opportunities. Users can explore different products, upload their own items, shop for deals, and earn rewards through an interactive and seamless interface.

## Key Features

### 1. **Explore Products**
   - View a variety of products with detailed descriptions and preview videos.
   - Browse through a modern grid layout to easily find products of interest.

### 2. **Loot Deals**
   - Discover exclusive "Loot Deals" with significant discounts.
   - View deals in a card layout, including offer percentages and links to claim.

### 3. **Shop**
   - Upload your own product videos along with descriptions and links.
   - Firebase storage integration ensures secure and fast uploads.
   - Easily showcase your product to the entire Loot community.

### 4. **Rewards**
   - Earn rewards such as loyalty points, badges, and mystery boxes.
   - Claim daily bonuses, level-up rewards, and prizes for completing challenges.
   - Engaging reward cards with an intuitive interface.

### 5. **User Authentication**
   - Users can sign up, log in, and manage their accounts securely using Firebase Authentication.
   - Account information is stored and updated in real-time, offering seamless user experience.

### 6. **Responsive Design**
   - Optimized for mobile, tablet, and desktop with a flexible, responsive layout.
   - Sidebar navigation and modern grid display allow easy interaction on any device.

### 7. **Data Persistence**
   - Firebase integration ensures that data is securely stored and retrieved.
   - Users can upload product information and video files, which are saved in the cloud and retrievable at any time.

## How to Use

### Explore Products
   - Navigate to the **Explore** section to view all products available.
   - Product details such as name, description, and a preview video are provided.
   - Click the "Buy Now" button to be redirected to the product purchase page.

### Loot Deals
   - Access the **Loot** section to browse exclusive deals with discount offers.
   - Claim any deal directly by clicking the "Claim Offer" button on the deal card.

### Shop (Product Upload)
   - Go to the **Shop** section and fill in the product name, description, and product link.
   - Upload a video showcasing the product.
   - Click "Upload Product" to add your item to the explore page for other users to discover.

### Rewards
   - Head to the **Rewards** section to see your achievements.
   - Claim your rewards such as loyalty points, badges, and more by clicking the "Claim Reward" button.

### Account Management
   - Sign in using Firebase authentication and access your **Account** section.
   - View and manage your product uploads, rewards, and other personal items.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/Loot.git
   ```

2. Open the `Loot Preview.html` file in your preferred browser.

3. Configure Firebase:
   - Go to the Firebase console and create a new project.
   - Set up authentication, database, and storage.
   - Replace the Firebase configuration in the HTML with your own Firebase project credentials.

## Technologies Used

- **Frontend**:
  - HTML5, CSS3, JavaScript
  - **FontAwesome** for icons
  - **Google Fonts** for Poppins typography

- **Backend**:
  - Firebase for Authentication, Realtime Database, and Storage.

## Firebase Setup

To set up Firebase in your own project:

1. Create a Firebase project at [Firebase Console](https://console.firebase.google.com/).
2. Set up authentication with **Email and Password**.
3. Configure **Firebase Realtime Database** for product uploads.
4. Configure **Firebase Storage** for storing uploaded videos.
5. Replace the Firebase configuration in the `Loot Preview.html` file with your own Firebase configuration:

```javascript
const firebaseConfig = {
    apiKey: "your-api-key",
    authDomain: "your-auth-domain",
    projectId: "your-project-id",
    storageBucket: "your-storage-bucket",
    messagingSenderId: "your-messaging-sender-id",
    appId: "your-app-id",
    measurementId: "your-measurement-id"
};
firebase.initializeApp(firebaseConfig);
```

## Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

This README provides detailed instructions for using and configuring your app, as well as a comprehensive feature breakdown. You can adjust specific project URLs and Firebase configurations as necessary.
