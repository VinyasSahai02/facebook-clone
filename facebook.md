<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="icon" type="image/png" href="favicon.png" />
    <title>Facebook-log in or sign up</title>
    <link rel="stylesheet" href="input.css">
    <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="bg-slate-200">
    <div class="container mt-36 flex mx-auto justify-center items-center">
        <div class="left w-5/12 mx-10 -mt-16">
            <img class="w-72" src="fblogo.svg" alt="facebook logo">
            <p class="text-3xl mx-7 tracking-tight -my-3">Facebook helps you connect and share with the people in your life.</p>
        </div>
        <div class="right flex flex-col bg-white p-4 rounded-lg w-1/4 text-lg relative shadow-xl">
            <input class="px-4 h-12 my-1 border border-1 border-gray-300 rounded-md outline-blue-300" type="text" placeholder="Email address or phone number">
            <input class="px-4 h-12 my-2 border border-1 border-gray-300 rounded-md outline-blue-300" type="password" placeholder="Password">
            <button class="bg-blue-600 text-white my-2 py-3 rounded-md font-bold hover:bg-blue-700">Log In</button>
            <span class="text-blue-600 text-center text-sm my-2 cursor-pointer hover:underline">Forgotten Password ?</span>
            <hr class="my-3">
            <button class="bg-green-600 text-white my-2 py-3 rounded-md font-bold w-fit px-4 mx-auto hover:bg-green-700">Create New Account</button>
            <div class="absolute -bottom-12 text-sm inline-flex mx-5">
                <p class="px-1 cursor-pointer font-bold hover:underline">Create a Page
                </p>
                <p>for a celebrity, brand or business</p>
            </div>
        </div>
    </div>
</body>
</html>
