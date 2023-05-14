# Delicious Discoveries

Delicious Discoveries is a restaurant search application built with React, Bootstrap, and TypeScript. It utilizes the Yelp Fusion API (https://www.yelp.com/developers/documentation/v3) to fetch data about various restaurants based on location and cuisine type. The application allows users to search for restaurants, view their details such as their name, ratings, location, and hours of operation. Users can also bookmark their favorite restaurants and retrieve them later using local storage.

## Features

- Search functionality to find restaurants by location or cuisine type
- Display of restaurant details including name, ratings, location, and hours
- Bookmarking functionality to save favorite restaurants
- A Random Selector feature that suggests a restaurant within a specified radius
- Responsive design that adapts to different screen sizes and devices

## Technologies Used

- React.js
- React Router
- Bootstrap
- TypeScript
- CSS
- HTML
- RESTful API: Yelp Fusion API (https://www.yelp.com/developers/documentation/v3)


## Setup

To run this project, follow these steps:

1. Clone the repository to your local machine
2. Install dependencies by running `npm install` in the project directory
3. Obtain a Yelp Fusion API key by following the instructions in the [Yelp Fusion API documentation](https://www.yelp.com/developers/documentation/v3/get_started)
4. Create a new file named `.env` in the root directory of the project
5. In the `.env` file, add the following line and replace `YOUR_YELP_API_KEY` with your actual Yelp Fusion API key: REACT_APP_YELP_API_KEY = YOUR_YELP_API_KEY
6. Start the development server by running `npm start`
7. Open `http://localhost:3000` in your web browser to view the site

> **Note:** Make sure to keep your API key confidential and do not commit the `.env` file to any public repositories. The `.env` file is already added to the `.gitignore`, so it won't be uploaded to the repository.


## Disclaimer

This project, Delicious Discoveries, is a personal and educational endeavor. It uses the Yelp Fusion API (https://www.yelp.com/developers/documentation/v3) to fetch and display data but is not affiliated with or endorsed by Yelp Inc. This project is purely for the purpose of practicing and developing my skills in front-end development, with a focus on React.js and TypeScript. It is also an exercise in learning to integrate and use third-party APIs. All restaurant information is provided by the Yelp Fusion API, and this application claims no ownership or responsibility for this data.

## Contact

If you have any questions or feedback about this project, feel free to contact me at [brandonctle.dev@gmail.com](mailto:brandonctle.dev@gmail.com) or connect with me on [LinkedIn](https://www.linkedin.com/in/brandonctle/).  Thanks for visiting!
