<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bonus Actvity</title>
    <script src="https://code.jquery.com/jquery-3.5.1.min.js"></script>

    <link rel="stylesheet" href="style.css">
</head>

<body>
    <script>
        console.log("Hello World of Pandemics")
    </script>
    <main>

        <div>
            <h2>Student Registration</h2>
            <form id="registration-form">
                <div>
                    <label for="name">Name:</label>
                    <br>
                    <input type="text" id="name" required>
                </div>
                <div>
                    <label for="email">Email:</label>
                    <br>
                    <input type="email" id="email" required>
                </div>
                <br>
                <div>
                    <button type="submit">Submit</button>
                </div>
            </form>
        </div>

        <div>
            <h2>Student List</h2>
            <ul id="student-list"></ul>
        </div>

    </main>
</body>
<script src="script.js"></script>

</html>
