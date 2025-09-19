# CodeAlpha_task-4
CODE
def chatbot():
    print("Chatbot: Hello! Type something to chat. Type 'bye' to exit.")
    
    while True:
        user_input = input("You: ").lower()
        
        if user_input == "hello":
            print("Chatbot: Hi!")
        elif user_input == "how are you":
            print("Chatbot: I'm fine, thanks!")
        elif user_input == "bye":
            print("Chatbot: Goodbye!")
            break
        else:
            print("Chatbot: Sorry, I don't understand that.")

# Run the chatbot
chatbot()

result
![CodeAlpha task 4](https://github.com/user-attachments/assets/6398c45c-0af6-4779-bab5-25620c316b54)



