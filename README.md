# Movie Portfolio Web App

This project is a **Streamlit-based web application** designed to display and categorize movies based on personal preferences (Loved, Liked, Disliked) and genres (Comedy, Thriller, Horror). It uses **APIs**, **interactive widgets**, and a clean UI for easy navigation.

---

## Features

### 1. Genre-Based Categorization
- **Genres**: Select from `Comedy`, `Thriller`, or `Horror`.
- Each genre includes movies grouped by:
  - **Loved**
  - **Liked**
  - **Disliked**

### 2. Interactive Elements
- **Checkboxes**: Reveal movies within a specific category.
- **Expandable Plot Section**: Displays the movie's plot fetched from the OMDB API.
- **Trailer Links**: Clickable buttons to watch trailers directly.
- **Movie Posters**: Each movie is paired with its corresponding poster.

### 3. Dynamic Data
- **OMDB API Integration**: Fetch movie plots dynamically.
- **Images**: Displays related movie posters.

### 4. Sidebar
- **About Me Section**:
  - Personal bio, profile picture, and links to social platforms like LinkedIn, GitHub, and email.
- **Links to Projects and Resume**.

### 5. Portfolio Additions
- **Education Section**: Displays courses, skills learned, and GPA.
- **Professional Experience**: Highlights internships and leadership roles with images.
- **Projects Section**: Lists personal projects with descriptions.
- **Skills Section**: Includes programming and spoken languages with progress bars.

---

## Technologies Used

- **Streamlit**: Framework for creating interactive web apps.
- **Python**: Core language for functionality.
- **OMDB API**: Fetch movie metadata and plot details.
- **Pandas**: Used for data manipulation and displaying educational details.
- **Pillow (PIL)**: For working with images.

---

## Key Components

1. **Genre Selection**:
   - Users can select a genre from the sidebar to filter movie lists.
   
2. **Dynamic Movie Details**:
   - Automatically fetches movie information such as the plot using the OMDB API.

3. **Trailer Links**:
   - Allows users to watch trailers via clickable buttons.

4. **Portfolio Features**:
   - Interactive sections for displaying personal and professional details.

---

## File Structure

- `app.py`: The main application script.
- `info.py`: Contains personal details for the portfolio (e.g., profile picture, education data, etc.).
- `Images/`: Folder containing all images used in the app (e.g., movie posters, profile picture).
- `requirements.txt`: File containing all necessary dependencies.

