# Dog Food Calculator

A comprehensive web application that calculates daily dog food requirements based on weight, activity level, and food specifications. Includes cost analysis and feeding recommendations.

## Features

- **Weight Selection**: Choose from 5-125 lbs in 5-pound increments
- **Activity Level**: Select from inactive, typical, active, or very active
- **Flexible Calorie Input**: Enter calories per cup or per ounce
- **Cost Analysis**: Calculate daily feeding cost and days per bag
- **Feeding Recommendations**: Get suggested daily amounts and feeding schedule
- **Responsive Design**: Works on desktop and mobile devices

## Usage

1. **Select your dog's weight** from the dropdown (5-125 lbs)
2. **Choose activity level** (inactive, typical, active, very active)
3. **Enter food specifications**:
   - Select calorie unit (per cup or per ounce)
   - Enter caloric content per selected unit
   - Enter calories per kg
   - Enter bag weight in pounds
   - Enter bag cost in dollars
4. **Click "Calculate Food Amount"** to get recommendations

## Output

The calculator provides:
- Daily caloric requirements
- Daily food amount in cups
- Daily feeding cost
- Days per bag of food
- Suggested feeding schedule (morning/evening split)
- Complete food specification summary

## Calculation Method

The calculator uses veterinary-recommended calorie requirements based on:
- **Base metabolic rate** by weight (5-125 lbs)
- **Activity multipliers**:
  - Inactive: 0.82x
  - Typical: 1.00x
  - Active: 1.14x
  - Very Active: 1.59x

## Technologies Used

- HTML5
- CSS3 with Google Fonts (Roboto)
- Vanilla JavaScript
- Responsive design principles

## Live Demo

Visit the calculator at: [Dog Food Calculator](https://enigmaticspaz.github.io/dog-food-calculator)

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/EnigmaticSpaz/dog-food-calculator.git
   ```
2. Open `dog-food-calculator.html` in your web browser

## Contributing

Feel free to submit issues, fork the repository, and create pull requests for any improvements.

## License

This project is open source and available under the [MIT License](LICENSE).

## Disclaimer

This calculator provides general feeding guidelines based on standard veterinary recommendations. Always consult with your veterinarian for specific dietary needs and feeding recommendations for your dog.