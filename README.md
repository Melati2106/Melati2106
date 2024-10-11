<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Daily Progress Tracker</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <h1>Daily Progress Tracker</h1>
    
    <!-- Form untuk input progress -->
    <form id="progress-form">
        <label for="task">Task:</label>
        <input type="text" id="task" name="task" required><br>

        <label for="status">Status:</label>
        <select id="status" name="status">
            <option value="done">Done</option>
            <option value="in-progress">In Progress</option>
            <option value="pending">Pending</option>
        </select><br>

        <label for="date">Date:</label>
        <input type="date" id="date" name="date" required><br><br>

        <input type="submit" value="Submit Progress">
    </form>

    <!-- Table untuk menampilkan progress -->
    <h2>Progress Summary</h2>
    <table id="progress-table">
        <tr>
            <th>Task</th>
            <th>Status</th>
            <th>Date</th>
        </tr>
    </table>

    <script src="script.js"></script>
</body>
</html>
