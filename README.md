<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Story Writing Website</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
        }

        #story-section {
            max-width: 800px;
            margin: 0 auto;
        }

        #donation-section {
            max-width: 400px;
            margin: 20px auto;
            padding: 20px;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
    </style>
</head>
<body>

    <div id="story-section">
        <h1>Welcome to our Story Writing Website!</h1>
        <p>Start writing and sharing your stories with the world.</p>
        <!-- Your story writing section can go here -->
    </div>

    <div id="donation-section">
        <h2>Support Our Website</h2>
        <p>If you enjoy our website and stories, consider making a donation to support us!</p>
        <label for="donation-amount">Amount: </label>
        <input type="number" id="donation-amount" placeholder="Enter amount">
        <button onclick="makeDonation()">Donate</button>
    </div>

    <script>
        function makeDonation() {
            // This is where you would integrate with a payment gateway
            // For a real website, you would use a service like Stripe, PayPal, etc.
            // For this example, we'll just show an alert.
            var amount = document.getElementById('donation-amount').value;
            alert('Thank you for your donation of $' + amount + '!');
        }
    </script>

</body>
</html>
