### Hi there 👋 Im' Egil Dankel 

🔭 I’m currently working with Cloud Engineering working with Azure governance and compliance. <br>
⚡ MBA master thesis on AI (Artifical intelligence). <br>
🌱 Studying Cloud Computing and programming. <br>
👯 In my spare time I enjoy Music and Music technology, playing in Jazz big band. <br> 

Let's Connect<br>
[![Let's Connect](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/egildankel/)
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Stavanger Map</title>
    <link rel="stylesheet" href="https://unpkg.com/leaflet/dist/leaflet.css" />
    <style>
        #map { height: 600px; }
    </style>
</head>
<body>
    <div id="map"></div>
    <script src="https://unpkg.com/leaflet/dist/leaflet.js"></script>
    <script>
        const map = L.map('map').setView([58.9690, 5.7331], 13); // Center on Stavanger

        L.tileLayer('https://{s}.tile.openstreetmap.org/{z}/{x}/{y}.png', {
            maxZoom: 19,
        }).addTo(map);

        const stavangerPolygon = L.polygon([
            [58.9650, 5.6763],
            [58.9730, 5.6763],
            [58.9730, 5.6833],
            [58.9650, 5.6833],
            [58.9600, 5.6750],
            [58.9600, 5.6700],
            [58.9550, 5.6700],
            [58.9550, 5.6750],
            [58.9650, 5.6750],
            [58.9650, 5.6800],
            [58.9700, 5.6800],
            [58.9700, 5.6850],
            [58.9650, 5.6850],
            [58.9650, 5.6800],
            [58.9650, 5.6763]  // Closing the polygon
        ], {
            color: 'blue',       // Outline color
            fillColor: 'blue',   // Fill color
            fillOpacity: 0       // Make fill transparent
        }).addTo(map);
    </script>
</body>
</html>

<details>
<summary>Programming Languages list</summary>

| Rank | Languages |
|-----:|-----------|
|     1| Markdown  |
|     2| Powershell|
|     3| Python    |
</details>

<details>
<summary>Favorite Quotes</summary>

| Quote| Author |
|-----:|-----------|
|     L'avenir appertient à ceux qui se lèvent tôt.| Unknown  |
|     | |
|     |    |
---


</details>
<picture>
 <source media="(prefers-color-scheme: dark)" srcset="https://github.com/user-attachments/assets/e8301d8a-ee3f-4c5c-a25d-48b2266a89be">
 <source media="(prefers-color-scheme: light)" srcset="https://github.com/user-attachments/assets/e8301d8a-ee3f-4c5c-a25d-48b2266a89be">
 <img alt="Robot" src="https://github.com/user-attachments/assets/e8301d8a-ee3f-4c5c-a25d-48b2266a89be">
</picture>

