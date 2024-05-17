# Movie Ticket Booking System

Welcome to our Movie Ticket Booking System, a beginner-friendly project aimed at those diving into Java full stack development. This system provides a platform for customers to easily book movie tickets online, offering a seamless experience from movie selection to seat reservation.

## About
Our software system simplifies the process of booking movie tickets by providing an intuitive interface for users to browse and select movies, choose their preferred seats, and complete their bookings.

## Technologies Used
To build this project, we utilized a combination of modern technologies to ensure efficiency, scalability, and user-friendliness:
- **SpringBoot**: Providing a robust framework for building and deploying Java-based applications.
- **Java**: The primary programming language for backend development.
- **Git**: Version control system for collaborative development.
- **HTML, CSS, Bootstrap**: Crafting the visual elements and ensuring a responsive design.

## Features
Our Movie Ticket Booking System comes equipped with the following features to enhance the user experience:
- **Browse Active Movies**: Users can view all currently active movies available for booking.
- **Seat Selection**: Customers have the freedom to choose their preferred seats based on availability.
- **Validation**: The system is thoroughly validated to ensure smooth functioning and eliminate errors.

## Preview
Explore a glimpse of our system through these preview images:

![Preview 1](https://user-images.githubusercontent.com/112768196/205480789-a5ff4ac0-6090-49be-b00f-d280084b7e20.png)
![Preview 2](https://user-images.githubusercontent.com/112768196/205480811-b27b0670-ed1d-4623-a5ba-250189b6498e.png)

## Database
For demonstration purposes, we've integrated an H2 database (local database) with the application, ensuring accessibility for all users. However, if you prefer using a different database, simply make the relevant changes in the `application.properties` file.

## Sample Data
To facilitate smooth usage and testing, we've included sample data within the system:
- **Active Movies**: Four movies are currently activated in four theaters, each with four shows scheduled for the current day. The program is auto-scheduled for convenience.
- **Show Status**: Show status is dynamically updated based on the current time. Shows that have ended are marked as completed, while those in progress cannot be booked.
- **Validation**: Rest assured, all data is validated to maintain system integrity and user satisfaction.

## Setup Instructions

1. **Clone the repository:**
    ```sh
    git clone https://github.com/yourusername/Movie-Ticket-Booking-System.git
    ```

2. **Navigate to the project directory:**
    ```sh
    cd Movie-Ticket-Booking-System
    ```

3. **Build the project:**
    ```sh
    mvn clean install
    ```

4. **Run the application:**
    ```sh
    mvn spring-boot:run
    ```

5. **Access the application:**
    - Open your browser and go to: `http://localhost:8080`

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

---

Feel free to tweak or add anything according to your preferences!
