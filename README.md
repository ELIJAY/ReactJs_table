
# React Threat Table

A React-based web application to display cyber and physical threat data in a professional and user-friendly table format. The table is styled with animations and transitions for a smooth and visually appealing user experience. It combines cyber and physical threat data and displays it using the React Table library.

## Features

- **Cyber and Physical Threat Data**: Displays threat data with various attributes such as context, platform, value score, and more.
- **Progress Bar**: Visualizes the threat value with a color-coded progress bar.
- **Responsive Design**: The table is styled to be responsive and usable across different screen sizes.
- **Animations & Transitions**: Table rows have hover effects, and progress bars have smooth transitions.
- **Icons**: Uses custom icons for different threat types and contexts.
- **Modular Code**: The table component is modular, allowing easy integration and customization.

## Technologies Used

- **React.js**: JavaScript library for building the user interface.
- **React Table**: For building and managing tables with sorting, pagination, and other features.
- **React Icons**: For custom icons representing various threat types.
- **CSS3**: For styling the table with animations and transitions.
- **JSON**: For data storage and management (cyber and physical threats).

## Installation

### Prerequisites

Make sure you have the following installed:

- [Node.js](https://nodejs.org/)
- [npm](https://www.npmjs.com/)

### Steps to Run

1. Clone this repository:

   ```bash
   git clone https://github.com/your-username/react-threat-table.git
   ```

2. Navigate to the project directory:

   ```bash
   cd react-threat-table
   ```

3. Install dependencies:

   ```bash
   npm install
   ```

4. Run the application:

   ```bash
   npm start
   ```

   This will start the development server and open the application in your default web browser.

## File Structure

```
react-threat-table/
│
├── public/
│   └── index.html           # The main HTML file
├── src/
│   ├── components/
│   │   ├── ThreatTable.js   # The main table component
│   │   ├── css/
│   │   │   └── ThreatTable.css  # CSS for styling the table
│   │   ├── data/
│   │   │   ├── cyberThreats.json   # JSON data for cyber threats
│   │   │   └── physicalThreats.json # JSON data for physical threats
│   ├── App.js               # Main app entry point
│   ├── App.css              # Global styles
│   ├── index.js             # Main React entry point
└── package.json             # Project metadata and dependencies
```

## Usage

Once the app is running, you will see a table that displays various threat data. The table will feature:

- **Icons**: Each row contains icons indicating the type of threat (cyber or physical).
- **Progress Bars**: A color-coded progress bar indicates the severity of the threat based on its value.
- **Hover Effect**: Rows change color when hovered, providing a more interactive user experience.

## Customization

You can customize the table by updating the `cyberThreats.json` and `physicalThreats.json` files with your own threat data. You can also adjust the table's appearance by modifying the `ThreatTable.css` file.

## Contributing

If you'd like to contribute to this project, feel free to fork the repository, create a branch, and submit a pull request. Make sure to follow the project's coding style and write clear commit messages.

## License

This project is open source and available under the [MIT License](LICENSE).

---

Made with ❤️ by [Elias J. Iortom](https://github.com/elijay)
