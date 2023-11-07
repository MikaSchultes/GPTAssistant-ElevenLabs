# GPTAssistant-ElevenLabs

Connecting the new  [OpenAI Assistant API](https://openai.com/blog/new-models-and-developer-products-announced-at-devday), which is persistent and has infinitely long threads, with the ElevenLabs Text to Speech and Azure Speech to Text API.

  

1: Fill in OpenAI, ElevenLabs and Azure Speech Services API keys, as well as the Azure Location/Region.

  

2: Execute `python newassistant.py` and follow the on-screen instructions to make an assistant. The language code must be [supported by Azure](https://learn.microsoft.com/en-us/azure/ai-services/speech-service/language-support?tabs=stt). When choosing GPT 4, your account must have access to the GPT 4 API.

  

3: Execute python `"yourassistantname.py"` to create a thread with the assistant created at step 2

  

4: Now execute python `"yourassistantname_thread.py"`  to send voice messages to the assistant and get TTS answers back.
