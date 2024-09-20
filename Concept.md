# Detailed Description of Student Stat Card System Implementation

## General Appearance
- The application runs in a 1024x768 pixel window
- All screens feature a dark blue (RGB: 0, 50, 100) background with 200 randomly placed white stars of varying sizes (1-3 pixels), creating a night sky effect

## Loading Screen
1. Displays "Loading Student Stat Card System" in large white text at the top center
2. Shows a white rectangular outline (924x30 pixels) below the text
3. A blue progress bar fills the outline from left to right
4. The progress bar fills at a variable rate, simulating data loading
5. Once the bar is full, it transitions to the main menu

## Main Menu
1. Displays "Student Stat Card System" in large white text at the top center
2. Features three buttons, vertically aligned in the center of the screen:
   - "Add Student" (positioned at y=300)
   - "View Stat Card" (positioned at y=400)
   - "Exit" (positioned at y=500)
3. Buttons are blue rectangles (200x50 pixels) with white borders and white text
4. Buttons change to light blue when the mouse hovers over them
5. Clicking a button performs the corresponding action

## Add Student Screen
1. Briefly shows a black background
2. Displays "Student Added!" in large green text at the center
3. This screen appears for 1.5 seconds before returning to the main menu

## View Stat Card Screen
1. Displays a large white rectangle (924x668 pixels) with a blue border, centered on the screen
2. Top-left corner:
   - Gray square (150x150 pixels) with "Student Photo" text, representing a placeholder for a student image
3. To the right of the photo:
   - Large black text: "John Doe" (student name)
   - Below the name: "Age: 16" in medium-sized black text
   - Below the age: "Grade: 11" in medium-sized black text
4. Below this information, for each subject (Math, English, Science, History, Art):
   - Light gray bar spanning most of the card's width
   - Subject name on the left side of the bar
   - Blue progress bar representing the score (width proportional to the score)
   - Numerical score at the right end of the bar
5. Top-right of the card:
   - Radar chart showing the student's performance across all subjects
   - Each subject is a point on the chart, with lines connecting to form a pentagon
   - The shape is filled with semi-transparent blue
   - Subject names are displayed around the chart
6. Bottom of the card:
   - "Achievements:" header in medium-sized black text
   - List of achievements, each with a gold circle icon and achievement name in small black text

## Interactivity
- The main menu buttons respond to mouse hover and clicks
- The View Stat Card screen can be exited by pressing the Escape key

## Additional Notes
- The system uses a clean, professional color scheme (dark blue, white, light blue, and gold accents)
- The starry background and radar chart give it a modern, slightly futuristic appearance
- The layout is well-organized and easy to read, with clear separation between different types of information
