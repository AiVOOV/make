# Make intigration for AiVOOV Text-to-Speech

Access all the best text-to-speech AI voices from Google, Amazon, IBM, Microsoft and OpenAI  using AiVOOV text-to-speech API. Our [AI voice generator](http://aivoov.com/) provides a single interface to convert text to audio using voices across different providers. 

Using a make intigration in your projects saves you time and offers many benefits:
1. You instantly get access to all the voices from Google, Amazon, IBM and Microsoft.
2. You maintain only one API integration.
3. You don't have to worry about API upgrades or changes made on Google, Amazon, IBM and Microsoft.
4. Any new voices added on these platforms are instantly available to you.

Take a look at the [Voice List page](https://aivoov.com/voices) to see a list of the available voices and languages. The file also contains audio samples to help you pick.

**Note:** You need to have a AiVOOV account with Characters Credit to be able to access the API.

## Requirements
To use the Leonardo.Ai modules, you must have a [aivoov.com](https://aivoov.com).

## Obtain your API key in aivoov.com
Follow the steps below to get your API key, which is required for accessing Aivoov's services.

1. **Log in to your Aivoov account**  
   Visit [https://aivoov.com](https://aivoov.com) and log in using your account credentials.

2. **Go to your Profile page**  
   Navigate to your [Profile page](https://aivoov.com/user/my_profile#apiAccess).

3. **Find the API section**  
   Scroll down or click on the **API Access** section/tab.

4. **Copy your API key**  
   Your API key will be displayed. Copy it and add in it securely for use in your applications.
You'll use this value in the API Key connection field in Make.


## aivoov.com modules
-  **Create Audio**
   To create audio, you need a voice ID and the transcribed text.
    - Output (JSON):
      ```jsonc
      {
        "status": "true || false",
        "message": "string",
        "transcribe_data": "string | Audio URL"
      }
      ```
    
    - Output Example (JSON):
      ```jsonc
      {
          "status": true,
          "message": "Audio successfully generated",
          "transcribe_uri": "https://aivoov.com/transcribe_file/user/92686e05-f1c2-47eb-8401-090fe266c49e.mp3"
      }
      ```
