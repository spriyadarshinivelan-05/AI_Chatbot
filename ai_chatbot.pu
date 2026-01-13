import random

responses = {
    "hello": ["Hi!", "Hello!", "Hey there!"],
    "how": ["I'm doing good 😊", "I'm fine!"],
    "name": ["I'm an AI Chatbot 🤖"],
    "bye": ["Goodbye!", "See you later!"]
}

def chatbot_response(user_input):
    tokens = user_input.lower().split()

    for word in tokens:
        if word in responses:
            return random.choice(responses[word])

    return "Sorry, I didn't understand that 😕"

print("Chatbot: Hi! Type 'bye' to exit.")

while True:
    user_input = input("You: ")

    if user_input.lower() == "bye":
        print("Chatbot: Goodbye!")
        break

    print("Chatbot:", chatbot_response(user_input))
