<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Edmar's Personal Website</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
            text-align: center;
        }
        
        .container {
            max-width: 800px;
            margin: 0 auto;
            padding: 20px;
            background-color: #fff;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        
        header {
            margin-bottom: 30px;
        }
        
        h1 {
            font-size: 2.5em;
            color: #444;
            margin-bottom: 10px;
        }
        
        h2 {
            font-size: 1.5em;
            font-weight: normal;
            margin-top: 0;
        }
        
        main {
            display: flex;
            flex-direction: column;
            align-items: center;
        }
        
        .section {
            margin-bottom: 30px;
        }
        
        .video-container {
            position: relative;
            width: 100%;
            padding-bottom: 56.25%; /* 16:9 aspect ratio */
            height: 0;
            margin-bottom: 15px;
        }
        
        .video-container iframe {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
        }
        
        .projects ul, .contact ul {
            list-style: none;
            padding: 0;
        }
        
        .projects li, .contact li {
            margin-bottom: 10px;
        }
        
        a {
            color: #007bff;
            text-decoration: none;
        }
        
        a:hover {
            text-decoration: underline;
        }
        
        footer {
            margin-top: 30px;
            font-size: 0.9em;
            color: #777;
        }
    </style>
</
