<script src="https://github.com/Cognigy/WebchatWidget/releases/latest/download/webchat.js"></script>
    <script src="https://github.com/Cognigy/WebchatWidget/releases/download/v2.48.0/speech-input.webchat-plugin.js"></script>
    <script src="https://github.com/Cognigy/WebchatWidget/releases/download/v2.48.0/speech-output.webchat-plugin.js"></script>
    <script>
      const settings = {
        userId: "stt-tts-demo",
        //settings: { enableSTT: true, enableTTS: true }
        settings: {
          enableSTT: true,
          enableTTS: false,
          disableBranding: true,
          enableUnreadMessageTitleIndicator: true,
          enableUnreadMessageSound: true,
          showEngagementMessagesInChat: true,
          startBehavior: "button",
          getStartedButtonText: "ابدأ",
          getStartedText: "ابدأ",
          useSessionStorage: true
        }
      };

      initWebchat(
        "https://endpoint-trial.cognigy.ai/8e6f9cbc9c28f5d06133d9740d5595e2e6a3ffdf8851cbf9af088ee8a22e165b",
        settings
      ).then((webchat) => {
        window.cognigyWebchat = webchat;
        webchat.open();
      });
    </script>

    <script src="https://github.com/Cognigy/WebchatWidget/releases/latest/download/webchat.js"></script>
