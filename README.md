# README.md

## CEPSmart

A simple web application for ZIP code lookup using the ViaCEP API,
featuring a user-friendly interface, address listing, and modal system.
The project is structured in a modular way using pure JavaScript, making
maintenance and expansion easier.

------------------------------------------------------------------------

## Features

-   ZIP code lookup using the public ViaCEP API\
-   Basic user input validation\
-   Display of returned data in a dynamic list\
-   Modal control for viewing details\
-   Modular organization (Controllers, Services, Models)

------------------------------------------------------------------------

## Project Structure

    proj-cepsmart
    ├── index.html
    ├── css/
    │   ├── buttons.css
    │   ├── modal.css
    │   └── styles.css
    ├── js/
    │   ├── controllers/
    │   ├── models/
    │   └── services/
    └── README.md

------------------------------------------------------------------------

## Technologies Used

-   **HTML5**
-   **CSS3**
-   **JavaScript (ES6)**
-   **ViaCEP API**

------------------------------------------------------------------------

## How to Run

1.  Download or clone the repository:

    ``` bash
    git clone https://github.com/your-user/proj-cepsmart.git
    ```

2.  Enter the project folder:

    ``` bash
    cd proj-cepsmart
    ```

3.  Open the `index.html` file in your browser.

No backend or additional installations are required.

------------------------------------------------------------------------

## Code Organization

### **Models**

-   `address.js`: Represents an address returned by the API.

### **Services**

-   `request-service.js`: Handles HTTP requests.\
-   `address-service.js`: Manages the logic for data fetching and
    normalization.\
-   Custom exceptions in `exceptions/`.

### **Controllers**

-   `form-controller.js`: Manages the search form.\
-   `list-controller.js`: Displays and manipulates returned addresses.\
-   `modal-controller.js`: Shows data in a modal.\
-   `page-controller.js`: Integrates the other controllers.
