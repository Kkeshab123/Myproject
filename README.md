<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Registration Form</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
        }

        .container {
            background-color: white;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            width: 300px;
        }

        h2 {
            text-align: center;
            margin-bottom: 20px;
        }

        .form-group {
            margin-bottom: 15px;
        }

        .form-group label {
            display: block;
            margin-bottom: 5px;
        }

        .form-group input {
            width: 100%;
            padding: 8px;
            box-sizing: border-box;
            border: 1px solid #ccc;
            border-radius: 4px;
        }

        button {
            width: 100%;
            padding: 10px;
            background-color: #28a745;
            color: white;
            border: none;
            border-radius: 4px;
            cursor: pointer;
        }

        button:hover {
            background-color: #218838;
        }
    </style>
</head>
<body>
    <div class="container">
        <h2>Registration Form</h2>
        <form id="registrationForm">
            <div class="form-group">
                <label for="login">Login Icon:</label>
                <input type="text" id="login" name="login" required>
            </div>
            <div class="form-group">
                <label for="fatherName">Father's Name:</label>
                <input type="text" id="fatherName" name="fatherName" required>
            </div>
            <div class="form-group">
                <label for="motherName">Mother's Name:</label>
                <input type="text" id="motherName" name="motherName" required>
            </div>
            <div class="form-group">
                <label for="idProof">ID Proof:</label>
                <input type="text" id="idProof" name="idProof" required>
            </div>
            <div class="form-group">
                <label for="townVillage">Town/Village:</label>
                <input type="text" id="townVillage" name="townVillage" required>
            </div>
            <div class="form-group">
                <label for="state">State:</label>
                <input type="text" id="state" name="state" required>
            </div>
            <div class="form-group">
                <label for="nationality">Nationality:</label>
                <input type="text" id="nationality" name="nationality" required>
            </div>
            <div class="form-group">
                <label for="profession">Profession:</label>
                <input type="text" id="profession" name="profession" required>
            </div>
            <div class="form-group">
                <label for="work">Work:</label>
                <input type="text" id="work" name="work" required>
            </div>
            <div class="form-group">
                <label for="education">Education:</label>
                <input type="text" id="education" name="education" required>
            </div>
            <div class="form-group">
                <label for="phoneNumber">Phone Number:</label>
                <input type="tel" id="phoneNumber" name="phoneNumber" required>
            </div>
            <div class="form-group">
                <label for="district">District:</label>
                <input type="text" id="district" name="district" required>
            </div>
            <div class="form-group">
                <label for="pincode">Pincode:</label>
                <input type="text" id="pincode" name="pincode" required>
            </div>
            <button type="submit">Submit</button>
        </form>
    </div>

    <script>
        document.getElementById('registrationForm').addEventListener('submit', function(event) {
            event.preventDefault();
            alert('Form submitted successfully!');
        });
    </script>
</body>
</html>
