<!DOCTYPE html>  
<html lang="en">  
<head>  
    <meta charset="UTF-8">  
    <meta name="viewport" content="width=device-width, initial-scale=1.0">  
    <title>Login Form</title>  
    <script src="https://cdn.tailwindcss.com"></script>  
</head>  
<body class="flex items-center justify-center h-screen bg-gray-100">  
    <div class="bg-white p-6 rounded shadow-md w-96">  
        <h2 class="text-2xl font-bold mb-4">Login</h2>  
        <form action="login.php" method="POST"> <!-- Submit to login.php -->  
            <div class="mb-4">  
                <label for="email" class="block text-sm font-medium text-gray-700">Email</label>  
                <input type="email" id="email" name="email" required class="mt-1 block w-full border-gray-300 rounded-md shadow-sm focus:border-blue-500 focus:ring focus:ring-blue-200">  
            </div>  
            <div class="mb-4">  
                <label for="password" class="block text-sm font-medium text-gray-700">Password</label>  
                <input type="password" id="password" name="password" required class="mt-1 block w-full border-gray-300 rounded-md shadow-sm focus:border-blue-500 focus:ring focus:ring-blue-200">  
            </div>  
            <button type="submit" class="w-full bg-blue-500 text-white py-2 rounded">Login</button>  
        </form>  
        <div id="error-message" class="text-red-500 mt-4"></div> <!-- Error message display -->  
    </div>  
</body>  
</html>
