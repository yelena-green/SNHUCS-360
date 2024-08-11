# CardGrove

## Overview
CardGrove is an Android application developed to help users manage and organize their physical greeting card collections. The app allows users to keep track of various types of cards, such as birthday cards, thank-you notes, and more, while providing a user-friendly interface to manage their inventory effectively. The app also features SMS notifications to alert users when their card inventory is running low, ensuring they never run out of essential cards.

## Requirements and Goals
The primary goal of CardGrove is to address the needs of individuals who want to efficiently manage their greeting card collections. The app was designed to help users keep track of their cards, monitor inventory levels, and receive alerts when supplies are low. This was achieved by providing a simple yet effective user interface that allows users to add, delete, and update card information easily.

## User-Centered UI Design
To meet user needs and ensure a user-centered experience, CardGrove includes several key screens and features:

* Login Screen: Allows users to securely access their card inventory.
* Card Inventory Screen: Displays all cards in a grid format, showing card type, name, and quantity. This screen also includes options to add new cards, increase or decrease quantities, and delete cards.
* Add Card Screen: Provides an intuitive interface for users to add new cards to their inventory, including fields for card name, type, and quantity.
* SMS Permission Screen: Allows users to grant or revoke permissions for SMS notifications, ensuring they stay informed when inventory levels are low.
* The UI was designed with simplicity and ease of use in mind. By focusing on intuitive layouts, clear labels, and minimal clicks to perform tasks, the app keeps the user experience smooth and efficient. The successful design was validated through user testing, which confirmed that users could navigate the app and manage their cards without confusion.

## Coding Approach and Strategies
The development of CardGrove was approached methodically, starting with a clear understanding of the app’s requirements and user needs. The following strategies were employed:

### Modular Design
The app was built using a modular approach, with each feature and functionality encapsulated in separate components (e.g., fragments, adapters). This made the codebase more manageable and easier to maintain.
Use of SQLite: SQLite was used for persistent data storage, allowing users to manage their card inventory across sessions. The database was designed to be robust and scalable, ensuring smooth performance even as the user’s card collection grows.
User Feedback Integration: Continuous user feedback was integrated during the development process to ensure that the app met user expectations and provided a seamless experience.
These strategies are not only effective for this project but can be applied to future projects to ensure clean, maintainable, and scalable code.

### Testing and Validation
Testing was a critical part of the development process. The app was tested rigorously using the Android Emulator and physical devices to ensure all features worked as intended. Both unit tests and manual testing were performed to validate functionality. This process was essential in identifying and resolving issues, such as crashes or unexpected behaviors, before the final release.
Testing revealed the importance of edge cases, such as handling zero inventory gracefully and ensuring that SMS notifications are sent only under the correct conditions. By catching these issues early, the app’s reliability was significantly improved.

### Overcoming Challenges
The design and development process required innovation, particularly when implementing the SMS notification feature. Ensuring that users were properly informed when their inventory was low without overwhelming them with notifications was a challenge that was overcome through careful design and testing.
Additionally, integrating a smooth user experience with persistent data storage required thoughtful planning and execution. The decision to use SQLite and the careful handling of user data helped to create a reliable and responsive app.

## Demonstrated Knowledge and Skills
The Card Inventory feature of the app is where I particularly demonstrated my knowledge and skills. By developing a dynamic, database-driven grid that allowed for real-time updates, inventory management, and user notifications, I showcased my ability to build a complex, interactive feature that directly meets user needs.

Overall, CardGrove represents a comprehensive and polished application that not only meets the initial project requirements but also provides a robust and enjoyable user experience. The knowledge and skills gained during this project will be invaluable in future development endeavors.
