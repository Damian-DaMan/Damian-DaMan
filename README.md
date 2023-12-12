<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Greetings</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            background-color: #f7f7f7;
            text-align: center;
            padding: 20px;
        }

        .container {
            max-width: 600px;
            margin: 0 auto;
            background-color: #fff;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }

        h1 {
            color: #333;
        }

        p {
            color: #555;
        }
    </style>
</head>

<body>

    <div class="container">
        <h1>Greetings!</h1>
        <p>Hi, I'm <span id="name">Your Name</span>, a <span id="role">Software Engineer</span>.</p>
        <p>Thanks for dropping by! I hope you find some of my work interesting.</p>

        <script>
            document.addEventListener("DOMContentLoaded", function () {
                function SoftwareEngineer() {
                    this.name = "Your Name";
                    this.role = "Software Engineer";
                    this.languagesSpoken = ["en_US"];
                }

                SoftwareEngineer.prototype.sayHi = function () {
                    alert("Thanks for dropping by, hope you find some of my work interesting.");
                };

                // Create an instance of the SoftwareEngineer object
                var me = new SoftwareEngineer();

                // Update the HTML content with dynamic values
                document.getElementById("name").textContent = me.name;
                document.getElementById("role").textContent = me.role;

                // Call the sayHi method of the me instance
                me.sayHi();
            });
        </script>
    </div>

</body>

</html>

### <h1 align="center">Hello there, I'm Damian 👋 </h1>

<!--
**Damian-DaMan/Damian-DaMan** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.
-->
<a href="https://git.io/streak-stats"><img src="https://streak-stats.demolab.com?user=Damian-DaMan&theme=nightowl&border_radius=4" alt="GitHub Streak" /></a>

Here are some ideas to get you started:

- 🔭 I’m currently working my personal portfolio
- 🌱 I’m currently learning React!
- 🤔 I’m looking for help with landing a job in the tech field
- 📫 How to reach me: damian.richard.solis@gmail.com
