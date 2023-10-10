<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
   
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
    <link rel="stylesheet" href="styles.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Poppins&display=swap" rel="stylesheet">

    
</head>
<body>
    <div class="container">
        <div class="left-pane">
            <div class="buttons">
            <button class="left-pane-button" id="newChatButton">
                <i class="fas fa-plus"></i> 
                New Chat
            </button>
            <button class="left-pane-button hide-button">
                <i class="fa-solid fa-bars"></i>
            </button>
        </div>  
           <div class="chat-list" id="chatList">
                <!-- Dummy Chat Items -->
                <div class="chat-item">
                    <i class="fa-solid fa-message"></i>
                    New chat 1</div>
                <div class="chat-item"><i class="fa-solid fa-message"></i>
                    New chat 2.</div>
                <div class="chat-item"><i class="fa-solid fa-message"></i>
                    New chat 3</div>
            </div>
        </div>
        <div class="right-pane">
            <div class="top-buttons">
                
                <button class="floating-button">GPT-3.5</button>
                
                <button class="floating-button">GPT-4</button>
            </div>
            <div class="chatgpt-name"><P>ChatGPT</P></div>
            <div class="message-area" id="messageArea">
                <!-- Message Display Area -->
            </div>
            <div class="floating-input">
                
                <input type="text" class="input-box" id="messageInput" placeholder="Send a message">
                <button class="floating-button-three" id="sendMessageButton">
                    <i class="fas fa-paper-plane"></i>
                </button>
            
                
            </div>
            <div class="r-preview">
                <p>Free Research Preview. ChatGPT may produce inaccurate information about people, places, or facts. ChatGPT August 3 Version</p>
            </div>
          </div>
       </div>
    </div>
    <script src="script.js"></script>

    
</body>
</html>
