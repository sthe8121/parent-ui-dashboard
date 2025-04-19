---
layout: default
title: Parent Dashboard
permalink: /parent/
---

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>GMIS Parent Dashboard</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://cdn.jsdelivr.net/npm/remixicon@3.5.0/fonts/remixicon.css" rel="stylesheet">
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        gmis: {
                            lightBlue: '#D4E9F7',
                            gold: '#E1A948',
                            navy: '#0E2A47',
                            grey: '#4A4A4A',
                            mist: '#F7F9FA'
                        }
                    }
                }
            }
        }
    </script>
    <style>
        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }
        .animate-fade-in { animation: fadeIn 0.5s ease-out; }
    </style>
</head>
<body class="bg-gmis-mist font-sans text-gmis-navy">
    <!-- original content here -->
</body>
</html>

