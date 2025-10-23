<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio Daden</title>
    <link rel="stylesheet" href="css/style.css">
</head>
<body>

    <header>
        <div class="main-logo"></div>

        <nav>
            <a class="border rounded p-2" href="#">Home</a>
            <a class="border rounded p-2" href="#">Our Profile</a>
            <a class="border rounded p-2"href="#">Portfolio</a>
            <a class="border rounded p-2"href="#">Message Us</a>
        </nav>
    </header>

    <main></main>
<form>
    <label for="name" class="block mb-2">Name:</label>
    <input type="text" id="name-input" name="name" class="border p-2 mb-4 w-full" required>

    <label for="email" class="block mb-2">Email:</label>
    <input type="email" id="email-input" name="email" class="border p-2 mb-4 w-full" required>

    <label for="message" class="block mb-2">Message:</label>
    <textarea id="message-input" name="message" class="border p-2 mb-4 w-full" rows="4" required></textarea>
</form>

<button class="bg-blue-500 text-white p-2 rounded">Send Message</button>
    <footer></footer>

    <script src="js/script.js"></script>
</body>
</html>
