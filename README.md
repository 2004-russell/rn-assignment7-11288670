# rn-assignment7-11288670


This project is a React Native application designed to provide a seamless shopping experience for users. It includes features such as product listings, detailed product views, a shopping cart, blog access, and information about store locations. The application utilizes React Navigation to create a user-friendly navigation experience through different screens.

Design Choices
React Native and React Navigation:

React Native: Chosen for its capability to build cross-platform mobile applications with a single codebase.
React Navigation: Selected for its comprehensive and flexible navigation solutions, including stack and drawer navigations.
Navigation Structure:

Stack Navigator: Used for navigation between different screens in a stack manner. This is useful for maintaining navigation history and allowing users to go back to the previous screens.
Drawer Navigator: Provides a side menu for easy access to different sections of the app, enhancing the user experience by organizing navigation in a clear and accessible manner.
Component Organization:

The application is divided into several screens, each representing different sections of the app (e.g., Home, Cart, Blog, Locations, Jewelry, Clothing, Electronics).
Each screen is encapsulated in its own component, making the code modular and easier to maintain.
Implementation Details
App Structure:

The main app component (App) initializes the navigation container and sets up the stack navigator.
The drawer navigator is nested within the stack navigator to allow the main screens to be accessible via a side drawer.
Screens:

HomeScreen: The default landing page of the application.
ProductDetailScreen: Displays detailed information about a selected product.
CartScreen: Shows the items added to the cart by the user.
BlogScreen: Provides access to blog articles.
LocationsScreen: Displays store locations.
JewelryScreen, ClothingScreen, ElectronicScreen: Display respective categories of products.
Data Storage:

The current implementation does not specify any data storage methods. Depending on the application's requirements, data storage can be implemented using:
Local Storage: For simple key-value storage, React Native's AsyncStorage can be used.
State Management: For managing application state, libraries like Redux or Context API can be utilized.

SCREENSHOTS.
![WhatsApp Image 2024-07-12 at 21 58 33_cad7460b](https://github.com/user-attachments/assets/aeb17277-e191-4c46-952a-0857cb616297)
![WhatsApp Image 2024-07-12 at 21 58 32_feb0242e](https://github.com/user-attachments/assets/b48352e7-153e-4379-bb5d-a5ddb5e76761)
![WhatsApp Image 2024-07-12 at 21 50 58_3ac1c66b](https://github.com/user-attachments/assets/98e59518-f24b-4845-b291-4fdc635d1aa3)
![WhatsApp Image 2024-07-12 at 22 10 28_4c11b818](https://github.com/user-attachments/assets/600394fa-fbac-419b-a1ee-f363d92409f7)



