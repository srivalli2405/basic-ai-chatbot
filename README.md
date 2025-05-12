# basic-ai-chatbot
Simple ai chatbot in python 
# chatbot.py

print("Hello! I am ChatBuddy. Ask me anything or type 'bye' to exit.")

while True:
    user_input = input("You: ").lower()

    if 'hello' in user_input or 'hi' in user_input:
        print("ChatBuddy: Hello! How can I help you?")
    elif 'your name' in user_input:
        print("ChatBuddy: I'm ChatBuddy, your virtual assistant.")
    elif 'how are you' in user_input:
        print("ChatBuddy: I'm just code, but I'm doing great! What about you?")
    elif 'bye' in user_input:
        print("ChatBuddy: Goodbye! Have a nice day!")
        break
    else:
        print("ChatBuddy: I'm not sure how to respond to that.")

