<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <title>Wikitraveling Chatbot</title>

  <!-- Script Dialogflow -->
  <script src="https://www.gstatic.com/dialogflow-console/fast/messenger/bootstrap.js?v=1"></script>

  <style>

    body{
      margin:0;
      padding:0;
      font-family: Arial, sans-serif;
      background:#f5f5f5;
      height:100vh;
    }

    h1{
      text-align:center;
      margin-top:40px;
      color:#1e3a8a;
    }

    p{
      text-align:center;
      color:#444;
    }

    /* CHATBOT */
    df-messenger {
      --df-messenger-bot-message: #1e3a8a;
      --df-messenger-button-titlebar-color: #1e3a8a;
      --df-messenger-chat-background-color: #ffffff;
      --df-messenger-font-color: white;
      --df-messenger-send-icon: #1e3a8a;
      --df-messenger-user-message: #dbeafe;

      position: fixed;
      bottom: 16px;
      right: 16px;
      z-index: 999;
    }

  </style>
</head>

<body>

  <h1>🌎 Wikitraveling</h1>
  <p>Bienvenido a nuestro asistente virtual de viajes.</p>

  <!-- CHATBOT -->
  <df-messenger
    intent="WELCOME"
    chat-title="Wikitraveling"
    agent-id="968a7c4f-d9a7-45ac-960c-1329f5bbf952"
    language-code="es"
  ></df-messenger>

</body>
</html>
