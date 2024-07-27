# Course Project with Toastify in React

This React project displays a list of courses with features such as filtering by category, liking courses, and showing notifications using Toastify. The application includes a navigation bar, a spinner for loading states, and uses an API to fetch course data.

## Component Details

### `App.js`

- **Manages State**: Handles the state for courses, loading status, and selected category.
- **Data Fetching**: Fetches course data from an API and updates the state.
- **Component Rendering**: Renders `Navbar`, `Filter`, and `Cards` components.
- **Loading Indicator**: Uses `Spinner` to show a loading indicator while data is being fetched.

### `Navbar.js`

- **Displays Navigation Bar**: Shows a navigation bar with the title "Top Courses."

### `Filter.js`

- **Filter Buttons**: Displays filter buttons based on `filterData`.
- **Category Filtering**: Allows users to filter courses by category.

### `Cards.js`

- **Receives Props**: Takes the list of courses and selected category as props.
- **Renders Cards**: Renders `Card` components for each course based on the selected category.

### `Card.js`

- **Course Details**: Displays individual course details including title, description, and image.
- **Like/Unlike Functionality**: Allows users to like or unlike a course with a notification using Toastify.

### `Spinner.js`

- **Loading Indicator**: Displays a spinner and a loading message while data is being fetched.

## Styling

The CSS styles are defined in `App.css`, `index.css`, and `Spinner.css`. These styles include:

- **Responsive Layouts**: Ensures components are displayed correctly across different screen sizes.
- **Component Styling**: Provides visual styling for each component, including spacing, colors, and animations.
