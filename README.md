# Login Page

This is a sleek and modern login page designed and developed by [AR7](https://arvinrezaei.com/). It includes fields for username and password, a "Remember me" checkbox, and links for forgot password and registration.

## Table of Contents

- [Demo](#demo)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)

## Demo

You can see the live demo of the login page [here](https://github.com/ThisIsAR7/Login-Page.git).

## Features

- User-friendly interface
- Input fields for username and password
- "Remember me" checkbox
- Links for forgot password and registration
- Responsive design
- Background image with blur effect

## Installation

To use this login page locally, follow these steps:

1. Clone the repository:
    ```sh
    git clone https://github.com/ThisIsAR7/Login-Page.git
    ```
2. Navigate to the project directory:
    ```sh
    cd Login-Page-main
    ```

## Usage

Open the `index.html` file in your preferred web browser to see the login page in action.

### Project Structure

- **HTML**: The structure of the login page
- **CSS**: Styling for the login page, located in `css/style.css`
- **Icons**: Boxicons library for icons, included via CDN in the HTML file

### Example

The login page includes fields for username and password, a "Remember me" checkbox, and links for forgot password and registration.

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE-edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Login Page</title>
    <link rel="stylesheet" href="css/style.css">
    <link href='https://unpkg.com/boxicons@2.1.4/css/boxicons.min.css' rel='stylesheet'>
</head>
<body>
    <div class="wrapper">
        <form action="">
        <h1>Login Page</h1>
            <div class="input-box">
                <input type="text" placeholder="Username" required>
                <i class='bx bxs-user'></i>
            </div>
            <div class="input-box">
                <input type="password" placeholder="Password" required>
                <i class='bx bxs-lock-alt' ></i>
            </div>
            <div class="remember-forgot">
                <label><input type="checkbox"> Remember me...</label>
                <a href="#">Forgot password?</a>
            </div>
            <button type="submit" class="btn">Login</button>
            <div class="register-link">
                <p>Don't have an account? <a href="#">Register</a></p>
            </div>
            <div><h2>Developed and Designed By <a href="https://ar123456.netlify.app"><strong>AR7</strong></a></h2></div>
        </form>
    </div>
</body>
</html>
