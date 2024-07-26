<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            background: #748D92;
            font-family: Arial, Helvetica, sans-serif;
            color: #D3D9D4;
            display: flex;
            flex-direction: column;
            align-items: center;
        }

        /* Navigation Bar */
        .navigations ul {
            list-style: none;
            background: rgb(214, 125, 8);
            padding: 0;
            margin: 0;
            width: 100%;
            display: flex;
            justify-content: center;
        }

        .navigations li {
            display: inline-block;
        }

        .navigations a {
            text-decoration: none;
            color: #FFD700;
            width: 100px;
            display: block;
            padding: 15px 20px;
            text-transform: uppercase;
            font-weight: bold;
            text-align: center;
            transition: background 0.3s;
        }

        .navigations a:hover {
            background: #0056b3;
        }

        /* Content Styling */
        .container {
            text-align: center;
            padding: 20px;
            max-width: 1200px;
            width: 100%;
        }

        h1 {
            color: #00FFFF;
            background-color: #3D2B1F;
            display: inline-block;
            padding: 10px 20px;
            border-radius: 5px;
        }

        h2, h3 {
            color: #D3D9D4;
        }

        hr {
            border: 0;
            height: 1px;
            background: #D3D9D4;
            margin: 20px auto;
            width: 80%;
        }

        /* Video Section */
        .video-section {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 20px;
        }

        .video-section ul {
            list-style: none;
            padding: 0;
            margin: 0;
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
        }

        .video-section li {
            margin: 10px;
        }

        .video-section iframe {
            border: 2px solid #000;
            border-radius: 5px;
            transition: transform 0.3s;
            max-width: 100%;
            height: auto;
        }

        .video-section iframe:hover {
            transform: scale(1.05);
        }

        /* Responsive Design */
        @media (max-width: 768px) {
            .navigations a {
                width: 80px;
                padding: 10px;
            }

            .video-section iframe {
                width: 100%;
            }
        }
    </style>
</head>

<body>
    <div class="navigations">
        <ul>
            <li><a href="./homepage.html">Home</a></li>
            <li><a href="./About.html">About</a></li>
            <li><a href="./Certificates.html">Certificates</a></li>
            <li><a href="./Services.html">Services</a></li>
            <li><a href="./Contact.html">Contact</a></li>
        </ul>
    </div>

    <div class="container">
        <h1>Charles Jordan Condez Portfolio</h1>
        <hr>
        <h2>Sample Videos</h2>

        <div class="video-section">
            <ul>
                <li>
                    <iframe src="https://www.youtube.com/embed/4Qqttx5ZtCc?si=bxYveW-Yfhru9WBx" title="YouTube video player" allowfullscreen></iframe>
                </li>
                <li>
                    <iframe src="https://www.youtube.com/embed/9ihiIpGxaOs?si=4V3ISbOH0jgygVJH" title="YouTube video player" allowfullscreen></iframe>
                </li>
                <li>
                    <iframe src="https://www.youtube.com/embed/GuuvLnUkvWQ?si=GpWeH3qdp56hy8sX" title="YouTube video player" allowfullscreen></iframe>
                </li>
                <li>
                    <iframe src="https://www.youtube.com/embed/ie-Wzhce1pQ?si=9a13acr_Vhr-IL65" title="YouTube video player" allowfullscreen></iframe>
                </li>
                <li>
                    <iframe src="https://www.youtube.com/embed/Crf7VeKdVqc?si=nfd0T3SzMMMlg27s" title="YouTube video player" allowfullscreen></iframe>
                </li>
                <li>
                    <iframe src="https://www.youtube.com/embed/PYEKONfsCEs?si=X0vmPz4SmQNYcAyZ" title="YouTube video player" allowfullscreen></iframe>
                </li>
            </ul>
        </div>
    </div>
</body>

</html>
