# Address Autocomplete

This is a simple web application that allows users to enter a zip code and automatically fetches and displays the corresponding address using the OpenStreetMap Nomination API.

## Features

- Input validation: Only numeric zip codes are accepted. If alphabets or invalid input are entered, an alert message is displayed.
- Address autocomplete: When a valid zip code is entered, the application fetches and displays the corresponding address using the OpenStreetMap Nomination API.
- Reset functionality: Users can reset the form to clear the input fields and address output.

## Technologies Used

- HTML
- CSS
- JavaScript

## How to Use

1. Clone the repository or download the source code.
2. Open the `autoFillAddress.html` file in a web browser.
3. Enter a zip code in the provided input field.
4. The address corresponding to the zip code will be automatically filled in the address output field.
5. To reset the form, click the "Reset" button.

## Customization

You can customize the appearance of the application by modifying the CSS styles in the `<style>` section of the HTML file.

You can also customize the API endpoint or integrate a different API for address retrieval by modifying the `getAddressFromZipCode` function in the JavaScript code.

## Limitations

- The application uses the OpenStreetMap Nomination API for address retrieval, and the availability and accuracy of address data may vary.
- The application currently supports numeric zip codes only.

## Credits

- The application is developed using the OpenStreetMap Nomination API.
- This project serves as a demonstration and learning exercise.


