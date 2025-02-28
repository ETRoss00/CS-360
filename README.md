# CS-360

Briefly summarize the requirements and goals of the app you developed. What user needs was this app designed to address?

The Inventory Story project was designed to help users track, manage, and update their inventory efficiently. The goal was to create an application that enables users to add, edit, delete, and categorize inventory items while maintaining real-time updates to prevent shortages or overstock situations. This app was designed with business owners, warehouse managers, and home organizers in mind, ensuring that inventory management is simple, efficient, and user-friendly.

What screens and features were necessary to support user needs and produce a user-centered UI for the app? How did your UI designs keep users in mind? Why were your designs successful?

To support user needs, several screens and features were necessary, including a Home Dashboard to provide an overview of inventory status. An Add/Edit Inventory Screen to allow users to input item details, including name and quantity. There were also Low Stock Alerts to notify users when stock levels reached 0. The UI was designed with ease of use and accessibility in mind. I tried to create an intuitive layout that would make sure that users could manage their inventory efficiently. My UI designs were successful because they prioritized usability, ensured smooth navigation, and provided visual feedback to guide user interactions. 

How did you approach the process of coding your app? What techniques or strategies did you use? How could those techniques or strategies be applied in the future?

For the coding process, I treid to  follow a structured, modular approach to allow for scalability and maintainability. Some of the techniques and strategies I used include a Model-View-Controller (MVC) Architecture to organize the codebase for better separation of concerns. I developed modular components for reusable functions for CRUD (Create, Read, Update, Delete) operations. I used SQLite for data persistence to store inventory data locally, allowing users to access their inventory even without an internet connection. I tried to implement SharedPreferences to store user settings, such as a preferred inventory view and notification preferences.

How did you test to ensure your code was functional? Why is this process important, and what did it reveal?

To verify functionality, I implemented unit testing for data validation and CRUD functionality. If I were able to complete the project as intended, I would have also conducted some manual testing by running the app on different screen sizes and devices to ensure responsiveness. I would have also performed some edge-case testing and simulated scenarios such as entering invalid data, adding excessive inventory, and handling empty fields to make sure the app responded correctly. Testing is very important because it helps identify and fix UI inconsistencies, data validation issues, and performance bottlenecks before final deployment.

Consider the full app design and development process from initial planning to finalization. Where did you have to innovate to overcome a challenge?

One of the biggest challenges I faced in the Inventory Story project was configuring the UI layout, particularly in designing the data display screen for the inventory list. Specifically, I struggled with getting the item_cell layout to display information the way I envisioned. Initially, I found it difficult to properly arrange text fields, icons, and spacing in a way that was both aesthetically pleasing and functionally effective. The main issues I had were with the text and icons misaligning within each item row and an inconsistent spacing when dynamically populating the list with inventory items. To resolve this, I tried to take a more methodical approach to designing and testing the item_cell layout. I researched best practices for designing list item layouts in Android Studio. I tried to implement a dynamic UI update strategy, making sure that elements resized proportionally when inventory data was updated. I also tred to use RecyclerView with a properly configured ViewHolder pattern, to make sure the item cells were efficiently recycled and displayed correctly.

In what specific component of your mobile app were you particularly successful in demonstrating your knowledge, skills, and experience?

One of the biggest successes of this project was implementing a fully functional, user-friendly inventory management system that aligns with real-world user needs. I was able to create a seamless CRUD functionality that allowed users to manage their inventory with minimal effort. The intuitive UI design made sure that even non-technical users could navigate the app easily. This project strengthened my understanding of user-centered design, structured development approaches, and performance optimization—skills that will undoubtedly be valuable in future development projects.
