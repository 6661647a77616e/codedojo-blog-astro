---
title: 'Fullstack Development'
description: 'Lorem ipsum dolor sit amet'
pubDate: 'Jul 08 2022'
heroImage: '/blog-placeholder-3.jpg'
---
# Learn Fullstack Development

```mermaid
flowchart TD
    subgraph "Frontend"
        HTML["HTML, CSS, JS"] --> Tailwind
        Tailwind --> ReactJS
        ReactJS --> NextJS["Next JS (FE + BE)"]
    end
    NextJS --> Docker
    subgraph "Backend"
        Docker --> API["API (REST API)"]
        API 
    end
    subgraph "DevOps"
    API --> Deployment 
    end
```

//need to fix mermaid config

<img src="../../../public/w4/graph.jpg" alt="Graph" />


//template aftermath study group

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Image Collage</title>
    <style>
        .collage {
            display: flex;
            flex-wrap: wrap;
            gap: 10px;
        }
        .collage img {
            width: calc(33.333% - 10px);
            height: auto;
        }
    </style>
</head>
<body>
    <h1>In Memories</h1>
    <div class="collage">
        <img src="../../../public/w4/img.jpg" alt="Image 1">
    </div>
</body>
</html>