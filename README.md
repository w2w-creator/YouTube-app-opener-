# YouTube-app-opener-
Landing page to open YouTube app
<!DOCTYPE html>
<html>
  <head>
    <title>Open in YouTube App</title>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <style>
      body {
        font-family: sans-serif;
        text-align: center;
        margin-top: 50px;
      }
      button {
        background-color: #ff0000;
        color: white;
        font-size: 18px;
        padding: 12px 24px;
        border: none;
        border-radius: 8px;
        cursor: pointer;
      }
    </style>
  </head>
  <body>
    <h1>Open in YouTube App</h1>
    <p>Tap the button below to open our channel directly in the YouTube app.</p>
    <button onclick="window.location.href='youtube://www.youtube.com/@weekdayswanderer'">
      Open in YouTube App
    </button>
  </body>
</html>
