<!DOCTYPE html>
<html>
<head>
    <title>Student Registration Form</title>

    <style>
        *{
            margin:0;
            padding:0;
            box-sizing:border-box;
            font-family:Segoe UI, sans-serif;
        }

        body{
            min-height:100vh;
            display:flex;
            justify-content:center;
            align-items:center;
            background:linear-gradient(135deg,#667eea,#764ba2);
            padding:20px;
        }

        .container{
            width:500px;
            background:rgba(255,255,255,0.15);
            backdrop-filter:blur(15px);
            border:1px solid rgba(255,255,255,0.3);
            border-radius:20px;
            padding:30px;
            box-shadow:0 8px 32px rgba(0,0,0,0.2);
            color:white;
        }

        h2{
            text-align:center;
            margin-bottom:20px;
            font-size:28px;
        }

        label{
            display:block;
            margin-top:12px;
            margin-bottom:5px;
            font-weight:bold;
        }

        input,
        select,
        textarea{
            width:100%;
            padding:12px;
            border:none;
            border-radius:10px;
            outline:none;
            background:rgba(255,255,255,0.2);
            color:white;
            font-size:15px;
        }

        input::placeholder,
        textarea::placeholder{
            color:#e0e0e0;
        }

        select{
            color:white;
        }

        option{
            color:black;
        }

        .gender{
            margin-top:8px;
            display:flex;
            gap:20px;
        }

        .gender input{
            width:auto;
        }

        button{
            width:100%;
            padding:14px;
            margin-top:25px;
            border:none;
            border-radius:10px;
            background:white;
            color:#764ba2;
            font-size:16px;
            font-weight:bold;
            cursor:pointer;
            transition:0.3s;
        }

        button:hover{
            transform:translateY(-3px);
            box-shadow:0 5px 15px rgba(0,0,0,0.3);
        }
    </style>
</head>

<body>

<div class="container">

    <h2>Student Registration Form</h2>

    <form>

        <label>Full Name</label>
        <input type="text" placeholder="Enter Full Name">

        <label>Email Address</label>
        <input type="email" placeholder="Enter Email Address">

        <label>Phone Number</label>
        <input type="tel" placeholder="Enter Phone Number">

        <label>Date of Birth</label>
        <input type="date">

        <label>Gender</label>
        <div class="gender">
            <label><input type="radio" name="gender"> Male</label>
            <label><input type="radio" name="gender"> Female</label>
        </div>

        <label>programme</label>
        <select>
            <option>Select programme</option>
            <option>Computer Science</option>
            <option>Information Technology</option>
            <option>Networking</option>
            <option>Cyber Security</option>
        </select>

        <label>Address</label>
        <textarea rows="4" placeholder="Enter Address"></textarea>

        <label>home address</label>
        <input type="home address" placeholder="Enter home address">

        <label>Student Id</label>
        <input type="Student Id" placeholder="Enter student Id">

        <button type="submit">Register Now</button>

    </form>

</div>

</body>
</html>
