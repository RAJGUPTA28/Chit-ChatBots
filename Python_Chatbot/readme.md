# Simple Python Chatbot

# Data Format - JSON 
 - {Intents:[] , Responses:[] , tag:}

```
{
"intents": [
        {"tag": "greeting",
         "patterns": ["Hi there", "How are you", "Is anyone there?","Hey","Hola", "Hello", "Good day"],
         "responses": ["Hello, thanks for asking", "Good to see you again", "Hi there, how can I help?"],
         "context": [""]
        },
        {"tag": "goodbye",
         "patterns": ["Bye", "See you later", "Goodbye", "Nice chatting to you, bye", "Till next time"],
         "responses": ["See you!", "Have a nice day", "Bye! Come back again soon."],
         "context": [""]
        }
     ]
}
```

# Method Used
- Text Classification using BOW and Basic Neural Nets
- Used BOW (Bag of Words) for Text Representation
- Tokenizer 
