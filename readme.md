# GraveMap

GraveMap is a web application for searching and locating graves within a cemetery. It provides a user-friendly interface with a map-based view to help visitors find specific graves.

## Features

*   **Search for Deceased:** Search for graves by name, surname, or year of death.
*   **Interactive Map:** View the cemetery layout and the location of graves on an interactive map.
*   **Grave Details:** Get detailed information about a selected grave.
*   **Multilingual Support:** The application supports multiple languages (English, Croatian, German, and Slovenian).
*   **Admin Panel:** An administrative interface for managing cemetery data.

## Screenshots

| Search Interface                                            | Map View                                        | Grave Details                                       |
| ----------------------------------------------------------- | ----------------------------------------------- | --------------------------------------------------- |
| ![Search Interface](https://placehold.co/600x400?text=Search+Interface) | ![Map View](https://placehold.co/600x400?text=Map+View) | ![Grave Details](https://placehold.co/600x400?text=Grave+Details) |

## Setup

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/your-username/GraveMap.git
    ```
2.  **Import the database:**
    -   Create a new database in your MySQL server.
    -   Import the `database.sql` file into your newly created database.
3.  **Configure the database connection:**
    -   Rename `includes/db.example.php` to `includes/db.php`.
    -   Open `includes/db.php` and update the database credentials.
4.  **Run the application:**
    -   Start your local web server (e.g., Apache, Nginx).
    -   Open the application in your web browser.

## Contributing

Contributions are welcome! If you would like to contribute to the project, please follow these steps:

1.  Fork the repository.
2.  Create a new branch for your feature or bug fix.
3.  Make your changes and commit them.
4.  Push your changes to your forked repository.
5.  Create a pull request with a detailed description of your changes.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more information.
