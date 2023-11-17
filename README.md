<html>
<head>
    <title>My Writings</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: lightblue;
        }
        h1 {
            text-align: center;
            color: white;
        }
        .container {
            width: 80%;
            margin: auto;
            display: flex;
            flex-wrap: wrap;
            justify-content: space-between;
        }
        .card {
            width: 30%;
            margin: 10px;
            padding: 10px;
            border: 1px solid black;
            box-shadow: 5px 5px 5px grey;
            background-color: white;
        }
        .card img {
            width: 100%;
            height: 200px;
            object-fit: cover;
        }
        .card h3 {
            text-align: center;
        }
        .card p {
            text-align: justify;
        }
        .card button {
            display: block;
            width: 100%;
            margin: 10px auto;
            padding: 10px;
            border: none;
            background-color: green;
            color: white;
            font-size: 20px;
            cursor: pointer;
        }
        .card button:hover {
            background-color: darkgreen;
        }
        .footer {
            width: 100%;
            margin: 20px auto;
            text-align: center;
            color: white;
        }
    </style>
</head>
<body>
    <h1>My Writings</h1>
    <div class="container">
        <div class="card">
            <img src="story1.jpg" alt="Story 1">
            <h3>Story 1: The Adventure of Tom and Jerry</h3>
            <p>This is a story about the famous cat and mouse duo, Tom and Jerry, who go on an exciting adventure to find a treasure hidden in a mysterious island.</p>
            <button onclick="pay(1)">Pay ₹50 and Read</button>
        </div>
        <div class="card">
            <img src="story2.jpg" alt="Story 2">
            <h3>Story 2: The Mystery of the Haunted House</h3>
            <p>This is a story about a group of friends who decide to explore a haunted house, only to discover that there is more to it than meets the eye.</p>
            <button onclick="pay(2)">Pay ₹50 and Read</button>
        </div>
        <div class="card">
            <img src="story3.jpg" alt="Story 3">
            <h3>Story 3: The Journey of the Little Prince</h3>
            <p>This is a story about a young prince who leaves his planet and travels across the universe, learning valuable lessons from different people and creatures he meets along the way.</p>
            <button onclick="pay(3)">Pay ₹50 and Read</button>
        </div>
    </div>
    <div class="footer">
        <p>© 2023 by My Writings. All rights reserved.</p>
    </div>
    <script>
        // This is a dummy function that simulates the payment process and redirects the user to the corresponding story page
        function pay(id) {
            alert("Thank you for your payment. You will be redirected to the story page shortly.");
            window.location.href = "story" + id + ".html";
        }
    </script>
</body>
</html>
