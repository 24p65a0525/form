<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Event Registration</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background: #f4f6f8;
        }
        .form-container {
            width: 100%;
            max-width: 400px;
            margin: 50px auto;
            background: #ffffff;
            padding: 20px;
            border-radius: 6px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
        }
        h2 {
            text-align: center;
        }
        label {
            display: block;
            margin-top: 12px;
        }
        input, select, button {
            width: 100%;
            padding: 8px;
            margin-top: 5px;
        }
        button {
            background-color: #007bff;
            color: white;
            border: none;
            margin-top: 20px;
            cursor: pointer;
        }
        button:hover {
            background-color: #0056b3;
        }
    </style>
</head>
<body>

<div class="form-container">
    <h2>Event Registration</h2>

    <form>
        <label>Full Name</label>
        <input type="text" required>

        <label>Email Address</label>
        <input type="email" required>

        <label>Phone Number</label>
        <input type="tel">

        <label>Attendance Type</label>
        <select>
            <option value="in-person">In Person</option>
            <option value="online">Online</option>
        </select>

        <label>Dietary Preferences</label>
        <input type="text" placeholder="None / Vegetarian / Vegan">

        <button type="submit">Register</button>
    </form>
</div>

</body>
</html>
