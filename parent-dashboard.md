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
    < ---
layout: default
title: Parent Dashboard
permalink: /parent/
---

<div class="container mx-auto px-4 py-8 max-w-4xl">
  <!-- Navigation -->
  <nav class="mb-6 flex justify-between items-center">
    <h1 class="text-3xl font-bold text-gmis-navy">Parent Dashboard</h1>
    <div class="flex space-x-2">
      <button
        id="langToggle"
        class="px-3 py-1 bg-gmis-gold text-white rounded hover:bg-opacity-90 transition">
        <i class="ri-translate-2-line mr-1"></i> 한국어
      </button>
    </div>
  </nav>

  <!-- Weekly Notice Board -->
  <div
    class="bg-white p-6 rounded-lg shadow-lg mb-8 animate-fade-in">
    <h2 class="text-2xl font-bold text-gmis-navy mb-4">
      Weekly Notice Board
    </h2>

    <!-- Important Event Notice -->
    <div class="bg-gmis-lightBlue p-4 rounded-lg mb-4">
      <h3
        class="text-lg font-bold text-gmis-navy mb-2">
        Early Years Winter Concert – This Friday
      </h3>
      <div class="space-y-2">
        <p><strong>Time:</strong> 2:00 PM – 3:30 PM</p>
        <p>
          <strong>Attire Required:</strong> White polo shirt, navy blue
          trousers/skirt
        </p>
        <p>
          <strong>Items to Bring:</strong> Water bottle, change of clothes
        </p>
      </div>
    </div>

    <!-- Other Notices -->
    <div class="space-y-4">
      <div class="border-l-4 border-gmis-gold pl-4">
        <h4 class="font-bold">Monday, April 8</h4>
        <p>Swimming lessons – please bring swimwear and towel</p>
      </div>
      <div
        class="border-l-4 border-gmis-grey pl-4 opacity-75">
        <h4 class="font-bold">Tuesday, April 9</h4>
        <p>Parent‑Teacher Meeting sign‑up opens</p>
      </div>
    </div>
  </div>

  <!-- Child‑Specific Information -->
  <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
    <!-- Academic Progress -->
    <div
      class="bg-white p-6 rounded-lg shadow-lg animate-fade-in">
      <h3
        class="text-lg font-bold text-gmis-navy mb-4">
        Sarah&#39;s Progress
      </h3>
      <div class="space-y-4">
        <div
          class="flex justify-between items-center border-b pb-2">
          <span>Reading Level</span>
          <span class="text-gmis-gold font-semibold">Advanced</span>
        </div>
        <div
          class="flex justify-between items-center">
          <span>Next Assessment</span>
          <span class="text-gmis-navy">April 15</span>
        </div>
      </div>
    </div>

    <!-- Upcoming Activities -->
    <div
      class="bg-white p-6 rounded-lg shadow-lg animate-fade-in">
      <h3
        class="text-lg font-bold text-gmis-navy mb-4">
        Upcoming Activities
      </h3>
      <ul class="space-y-3">
        <li
          class="flex items-center justify-between">
          <div class="flex items-center">
            <i
              class="ri-calendar-event-line text-gmis-gold mr-2"></i>
            Art Exhibition
          </div>
          <span class="text-sm text-gmis-grey">April 12</span>
        </li>
        <li
          class="flex items-center justify-between">
          <div class="flex items-center">
            <i
              class="ri-calendar-event-line text-gmis-gold mr-2"></i>
            Science Fair
          </div>
          <span class="text-sm text-gmis-grey">April 18</span>
        </li>
      </ul>
    </div>
  </div>
</div>

<script>
  document
    .getElementById("langToggle")
    .addEventListener("click", () => {
      alert("Korean translation feature coming soon!");
    });

  // Fade‑in delay for each section
  document
    .querySelectorAll(".animate-fade-in")
    .forEach((el, idx) => {
      el.style.animationDelay = `${idx * 0.2}s`;
    });
</script>-->
</body>
</html>

