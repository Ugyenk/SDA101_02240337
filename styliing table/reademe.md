# My Semester Grades - HTML Table

This project is a simple HTML page that displays a table summarizing the grades received for various modules, assignments, and exams in a semester. It shows details such as the module name, assignment/exam name, maximum marks, marks obtained, percentage, and grade.

## Features
- **Responsive Table**: The table adapts to different screen sizes and provides a clean layout for displaying grade-related data.
- **Grade Overview**: Displays the module name, assignment/exam name, maximum marks, marks obtained, percentage, and letter grade.
- **Hover Effect**: Table rows highlight with a subtle color change when hovered over, improving user interaction.

## Table Structure

The table consists of the following columns:

| Column              | Description                                                                 |
|---------------------|-----------------------------------------------------------------------------|
| **Module**          | The course or subject code (e.g., SDA101, MAT101)                            |
| **Assignment/Exam Name** | The name of the specific assignment, homework, or exam.                  |
| **Maximum Marks**   | The total number of marks that could be awarded for the assignment/exam.     |
| **Marks Obtained**  | The number of marks the student received.                                   |
| **Percentage**      | The percentage score, calculated as `(Marks Obtained / Maximum Marks) * 100`.|
| **Grade**           | The letter grade based on the percentage (e.g., A, B+, S).                  |

## Usage Instructions

1. **Download the HTML File**: Save the provided HTML code into a file named `index.html` on your local computer.
2. **Open in Browser**: Open the `index.html` file in any modern web browser (Google Chrome, Firefox, Safari, etc.).
3. **Modify Data**: Replace the example rows in the table with your own assignment/exam data.

### Example Row:
```html
<tr>
    <td>SDA101</td>
    <td>Assignment 1: Figma Design</td>
    <td>10</td>
    <td>7</td>
    <td>70%</td>
    <td>B</td>
</tr>
