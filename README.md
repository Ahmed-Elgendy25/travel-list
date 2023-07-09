# Travel List Project (Add Items)

This is a travel list project built using React.js that allows users to add new items to their travel list. Also they have three sorting ways: By input,By Description, By Packed status. Also you can remove item or toggle item if you add it or not in the list.
![image](https://github.com/Ahmed-Elgendy25/travel-list/assets/108876019/3bac12f1-b824-4502-8a64-c48143d2ad9c)


## Installation

To run the project locally, follow these steps:

1. Clone the repository:
   ```
   git clone <repository_url>
   ```

2. Navigate to the project directory:
   ```
   cd travel-list
   ```

3. Install the dependencies:
   ```
   npm install
   ```

4. Start the development server:
   ```
   npm start
   ```

   This will start the application on your local server (by default, [http://localhost:3000](http://localhost:3000)).

## Usage

Once the application is running, you can interact with the travel list project in your web browser. The main feature of this version is to add new items to the travel list. Here's how you can use it:

1. On the homepage, you will see a form labeled "Add Item".

2. Fill out the form with the details of the destination you want to add. The form fields include:
   - Place Name: Enter the name of the travel destination.
   - Description: Provide a brief description of the destination.
   - Date of Visit: Specify the date you plan to visit the destination.

3. After filling out the form, click on the "Add" button to add the item to your travel list.

4. The newly added item will appear at the top of the list, displaying the place name, description, and date of visit.

5. Repeat the above steps to add more items to your travel list.

## Project Structure

The project structure follows the standard conventions of a React.js application. Here is an overview of the main files and directories:

- `src/App.js`: This is the main component that renders the application. It handles the state management and contains the logic for adding items to the travel list.

- `src/components/`: This directory contains the reusable components used in the application.

- `src/components/ItemForm.js`: This component renders the form for adding a new item to the travel list.

- `src/components/ItemList.js`: This component renders the list of items in the travel list.

- `src/components/ItemCard.js`: This component renders an individual item card.

- `src/App.css`: This file contains the styles for the application.

## Dependencies

The project has the following dependencies:

- React.js: A JavaScript library for building user interfaces.
- React DOM: Responsible for rendering React components in the browser.
- React Scripts: Provides scripts and configuration used by Create React App.
- PropTypes: A library used for defining the types of props passed to components.

These dependencies are managed using npm and will be automatically installed when you run the `npm install` command.

## Contributing

If you would like to contribute to this project, you can fork the repository, make your changes, and submit a pull request. Your contributions are greatly appreciated!

## License

This project is licensed under the [MIT License](LICENSE). Feel free to use, modify, and distribute the code as per the terms of the license.

## Acknowledgements

This project was created as a simple demonstration of React.js capabilities. It was built with the help of various online tutorials and resources. Special thanks to the React.js community for their excellent documentation and support.
