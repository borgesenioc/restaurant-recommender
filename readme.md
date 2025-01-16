# Restaurant Filter App

A simple TypeScript application that filters restaurants based on price, delivery time, distance, and operating hours.

## Features
- Filters by:
  - Price (`$$`)
  - Delivery time (max: 90 minutes)
  - Distance (max: 10 units)
  - Current operating hours
- Outputs availability messages:
  - No restaurants: `"There are no restaurants available right now."`
  - One restaurant: `"We found 1 restaurant: {name}."`
  - Multiple restaurants: `"We found {count} restaurants, the first is {name}."`

## Usage
1. Clone the repository:
   - `"git clone git@github.com:your-username/restaurant-recommender.git"`
2. Navigate to the project:
   - `"cd restaurant-recommender"`
3. Run the app:
   - `"npm start"`
   

## Example Restaurant Data
    {
      name: "Pizza Place",
      priceBracket: "2",
      deliveryTimeMinutes: 45,
      distance: 5,
      openHour: 10,
      closeHour: 22
    }


## Requirements
	•	Node.js installed.
	•	A restaurants dataset to import.

## License

MIT License
This version ensures all bash commands are in string format, as requested.