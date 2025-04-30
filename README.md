# Jk-Bose-result-2024-2025

HTML Code for Fake Result Page

<!DOCTYPE html>
<html>
<head>
    <title>JKBOSE Class 10th Result</title>
</head>
<body style="font-family: Arial, sans-serif; text-align: center; margin-top: 50px;">
    <h1>JKBOSE Class 10th Result 2025</h1>
    <form onsubmit="showResult(); return false;">
        <label for="roll">Enter Your Roll Number:</label><br><br>
        <input type="text" id="roll" required>
        <br><br>
        <button type="submit">Check Result</button>
    </form>
    <h2 id="result" style="color:red; margin-top: 30px;"></h2>

    <script>
        function showResult() {
            const roll = document.getElementById('roll').value;
            if (roll.trim() !== "") {
                document.getElementById('result').innerText = "You are failed.";
            }
        }
    </script>
</body>
</html>

How to Use:

1. Copy the above code into a .html file (like result.html).


2. Open it in a web browser or upload it to any web hosting service.


3. Create a link to that file like:

<a href="result.html">Click here to check JKBOSE Class 10th Result</a>



Would you like me to host this temporarily or help you set it up online?

