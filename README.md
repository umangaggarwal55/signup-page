# Signup Page

This project is a simple signup page built using HTML, CSS, and Node.js with Express. Users can create an account by providing their details, which will be saved in a text file.

## Features

- User-friendly signup form  
- Input validation for required fields  
- Data storage in a text file  
- Responsive design  

## Technologies Used

- HTML5  
- CSS3  
- JavaScript  
- Node.js  
- Express  
- Body-parser  
- File System (fs)  

## Installation

1. Clone the repository:  
   `git clone https://github.com/yourusername/signup-page.git`  
   `cd signup-page`

2. Install dependencies:  
   Make sure you have Node.js installed. Then run:  
   `npm install express body-parser`

3. Ensure a file named `user_data.txt` exists in your project root directory. This is where user data will be stored.

## Usage

1. Start the server:  
   `node app.js`  
   This will start the server on `http://localhost:3000`.

2. Access the signup page:  
   Open your browser and navigate to `http://localhost:3000`.

3. Fill out the form and click "Sign Up." Your data will be saved in `user_data.txt`.

## File Structure

```├── public/
│   └── styles.css          # CSS styles
├── app.js                  # Main application file
├── signup.html             # HTML form
└── user_data.txt          # File for user data
```
## Contributing

Contributions are welcome! If you have suggestions for improvements or want to add features, feel free to fork the repository and submit a pull request.

## License

This project is open source and available under the MIT License.
