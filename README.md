

## Find Meals For Your Ingredients

This is a simple web application that allows users to find recipes based on the ingredients they have. The app integrates with the [TheMealDB API](https://www.themealdb.com/) to fetch meal data and display detailed recipes.

## Features

- **Search Meals by Ingredient:** Input an ingredient and get a list of meals that can be prepared with it.
- **View Recipes:** Click on a meal to view detailed cooking instructions, along with an image and video tutorial.
- **Interactive UI:** User-friendly interface with dynamic rendering of search results and recipe details.


## Getting Started

Follow these steps to set up the project on your local machine:

### Prerequisites

- A modern web browser
- A text editor or IDE (e.g., VS Code)
- Basic knowledge of HTML, CSS, and JavaScript

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/find-meals-for-ingredients.git
   ```

2. Navigate to the project directory:

   ```bash
   cd find-meals-for-ingredients
   ```

3. Open the `index.html` file in your browser to view the app.

### Dependencies

The project uses the following libraries and tools:
- [Font Awesome](https://fontawesome.com/) for icons.
- [TheMealDB API](https://www.themealdb.com/) for meal data.

## Usage

1. Open the application in your browser.
2. Enter an ingredient in the search box (e.g., "chicken").
3. Click the **Search** button to get meal suggestions.
4. Click **Get Recipe** for detailed cooking instructions and a video tutorial.

## File Structure

```
.
├── index.html          # Main HTML file
├── style.css           # Stylesheet
├── script.js           # JavaScript logic
└── README.md           # Project documentation
```

## API Integration

The application leverages the [TheMealDB API](https://www.themealdb.com/api.php). Key API endpoints used:

- Search meals by ingredient:  
  `https://www.themealdb.com/api/json/v1/1/filter.php?i=ingredient`

- Get meal details by ID:  
  `https://www.themealdb.com/api/json/v1/1/lookup.php?i=mealId`


## Future Improvements

- Add functionality to search for multiple ingredients.
- Enhance UI with more animations and responsiveness.
- Provide filtering options for dietary preferences.

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature:  
   `git checkout -b feature-name`
3. Commit your changes:  
   `git commit -m "Add some feature"`
4. Push to the branch:  
   `git push origin feature-name`
5. Submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
