# Ex.08 Design of Interactive Image Gallery
## Date:
13-05-2025
## AIM:
To design a web application for an inteactive image gallery with minimum five images.

## DESIGN STEPS:

### Step 1:
Clone the github repository and create Django admin interface.

### Step 2:
Change settings.py file to allow request from all hosts.

### Step 3:
Use CSS for positioning and styling.

### Step 4:
Write JavaScript program for implementing interactivity.

### Step 5:
Validate the HTML and CSS code.

### Step 6:
Publish the website in the given URL.

## PROGRAM :
"""
/*
<html>

<head>
    <title> Peak Cinema in One Frame</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #db1a1a;
            margin: 0;
            padding: 0;
            height: 100vh;
            display: flex;
            flex-direction: column;
        }

        .gallery-container {
            display: flex;
            flex: 1;
            justify-content: space-between;
            align-items: center;
            padding: 20px;
            gap: 20px;
            height: calc(100% - 80px);
        }

        .side-column {
            display: flex;
            flex-direction: column;
            gap: 20px;
            height: 100%;
            width: 30%; /* Adjust this percentage as needed */
        }

        .gallery-item {
            cursor: pointer;
            border-radius: 15px;
            border: 2px solid #4bc8c8;
            transition: transform 0.3s;
            object-fit: cover;
            width: 100%;
        }

        .gallery-item:hover {
            transform: scale(1.05);
        }

        .left-column .gallery-item, 
        .right-column .gallery-item {
            height: calc(50% - 10px); /* Half of column height minus half the gap */
            flex: 1;
        }

        .center-column {
            height: 100%;
            display: flex;
            justify-content: center;
            width: 30%; /* Adjust this percentage as needed */
        }

        .center-column .gallery-item {
            height: 100%;
            width: 100%;
        }

        .modal {
            display: none;
            position: fixed;
            z-index: 1;
            left: 0;
            top: 0;
            width: 100%;
            height: 100%;
            background-color: rgba(0, 0, 0, 0.8);
            justify-content: center;
            align-items: center;
        }

        .modal-content {
            max-width: 80%;
            max-height: 80%;
        }

        .close {
            position: absolute;
            top: 20px;
            right: 30px;
            font-size: 30px;
            color: rgb(167, 61, 61);
            cursor: pointer;
        }

        .back {
            background-color: rgb(22, 21, 20);
        }

        h1 {
            font-family: Georgia, 'Times New Roman', Times, serif;
            color: rgb(246, 236, 233);
            text-align: center;
            padding: 20px 0;
            margin: 0;
        }
    </style>
    <script>
        function openModal(image) {
            const modal = document.getElementById('imageModal');
            const modalImg = document.getElementById('modalImage');

            modal.style.display = "flex";
            modalImg.src = image.src;
        }
        function closeModal() {
            const modal = document.getElementById('imageModal');
            modal.style.display = "none";
        }
    </script>
</head>

<body class="back">

    <h1>Peak Cinema in One Frame</h1>
        
    <div class="gallery-container">
        <!-- Left Column -->
        <div class="side-column left-column">
            <img src="images/img1.jpg" alt="Image 1" class="gallery-item" onclick="openModal(this)">
            <img src="images/img2.webp" alt="Image 2" class="gallery-item" onclick="openModal(this)">
        </div>
        
        <!-- Center Column -->
        <div class="center-column">
            <img src="images/img3.webp" alt="Image 3" class="gallery-item" onclick="openModal(this)">
        </div>
        
        <!-- Right Column -->
        <div class="side-column right-column">
            <img src="images/img4.webp" alt="Image 4" class="gallery-item" onclick="openModal(this)">
            <img src="images/img5.avif" alt="Image 5" class="gallery-item" onclick="openModal(this)">
        </div>
    </div>
    
    <div id="imageModal" class="modal" onclick="closeModal()">
        <span class="close">&times;</span>
        <img class="modal-content" id="modalImage">
    </div>

</body>

</html>
*/
"""
## OUTPUT:

![Exp5](https://github.com/user-attachments/assets/ab5249ff-1251-4d8a-8fb5-e773b1229553)

## RESULT:
The program for designing an interactive image gallery using HTML, CSS and JavaScript is executed successfully.
