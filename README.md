hello 
landing page is webpage which i represented my ways of achieving happiness.
I created this page using HTML and CSS.

here is the preview of page :

<!DOCTYPE html>
<html lang="en">
<head>
    <title>MY LANDING PAGE</title>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <style>
        * {
            box-sizing: border-box;
        }
        body {
            font-family: Arial, Helvetica, sans-serif;
            margin: 0;
            padding: 40p;
            background: url('https://revistavelvet.cl/wp-content/uploads/2023/08/felicidad.webp') no-repeat center center fixed;
            opacity: 0.84;
        }
        /* Style the header */
        header {
            text-align: center;
            background-color: #333;
            color: white;
	    padding: 5px;
            margin-bottom:10px;   
        }
        /* Create two columns/boxes that float next to each other */
        /* Style the list inside the menu */
        nav ul {
            list-style-type: none;
            padding: 0;
        }
        article {
            float: left;
            padding: 20px;
            width: 40%;
            height: auto;
            margin: 20px;
            position: relative;          
           background-color: rgba(122, 90, 0, 0.3);       
        }
        /* Add transparent background to text within article */
        article h1, article p {
            background-color: rgba(110, 0, 0, 0.5);
            padding: 10px;
            color: white;
            border-radius: 5px;
        }
	nav {
            float: right;
            width: 40%;
            height: 100vh;
            padding: 20px;
            background-color: transparent;
            background: url('https://c.wallhere.com/photos/c4/be/AI_art_artwork_inkpunk_colorful_long_hair_smile_Color_Burst-2206963.jpg!d');
            background-size: cover;
            opacity: 0.8;
        }
        /* Clear floats after the columns */
        section::after {
            content: "";
            display: table;
            clear: both;
             background-color: rgba(0, 0, 0, 0.5);
        }
        /* Style the footer */
        footer {
            background-color: #333;
            padding: 10px;
            text-align: center;
            color: white;
        }
        /* Responsive layout - makes the two columns/boxes stack on top of each other instead of next to each other, on small screens */
        @media (max-width: 600px) {
            nav, article {
                 background-color: rgba(0, 0, 0, 0.5);
               width: 100%;
            }
        }
    </style>
</head>
<body>
    <header>
        <h2>MY HAPPINESS</h2>
    </header>
    <section>
        <nav>
            <!-- Empty content, as the background is set through CSS -->
        </nav>
        <article>
            <h1>HEALTHY DIET</h1>
            <p>A healthy diet is crucial for maintaining overall health. It includes essential nutrients such as proteins, vitamins, and fiber. Incorporating a balanced diet contributes to physical and mental well-being.</p>
            <img src="health.jpg" alt="Healthy Diet" width="100%" height="auto">
        </article>
        <article>
            <h1>EXPRESSIVE</h1>
            <p>Expressing emotions authentically is key to happiness. Suppressing emotions can hinder genuine happiness. Embracing and expressing feelings allows for a more fulfilling life.</p>
            <img src="https://www.spd.org.sg/wp-content/uploads/2021/03/shutterstock_1478739569-1200x650.jpg" alt="Expressive Emotions" width="100%" height="auto">
        </article>
        <article>
            <h1>WAY TO HAPPINESS</h1>
            <p>The ultimate path to happiness is through self-love. Cultivating self-love fosters inner happiness and a positive outlook on life. Embrace self-care and prioritize your well-being.</p>
            <img src="https://i.pinimg.com/736x/73/63/97/7363978596046fd68015a3a6dbb81609--love-painting-self-love.jpg" alt="Self-Love" width="100%" height="auto">
        </article>
        <article>
            <h1>IKIGAI</h1>
            <p>Ikigai is a Japanese concept that means "a reason for being." It refers to the idea of finding joy, fulfillment, and balance in life by aligning one's passions, values, talents, and activities.</p>
            <img src="https://res.cloudinary.com/teepublic/image/private/s--nCV9tug6--/t_Preview/t_watermark_lock/b_rgb:000000,c_lpad,f_jpg,h_630,q_90,w_1200/v1653392774/production/designs/30718397_0.jpg" alt="Ikigai" width="100%" height="auto">
        </article>
    </section>
    <footer>
        <p>&copy; 2023 My Happiness</p>
    </footer>
</body>
</html>
