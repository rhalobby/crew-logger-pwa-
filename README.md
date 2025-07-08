<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Crew Logger PWA</title>
  <link rel="manifest" href="manifest.json" />
  <script>
    if ('serviceWorker' in navigator) {
      navigator.serviceWorker.register('service-worker.js');
    }
  </script>
</head>
<body>
  <h1>Welcome to Crew Logger PWA</h1>
</body>
</html>
