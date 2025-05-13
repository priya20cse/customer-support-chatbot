# customer-support-chatbot
#Implementation of a Contextual Chatbot in PyTorch.
Simple chatbot implementation with PyTorch.

The implementation should be easy to follow for beginners and provide a basic understanding of chatbots.
The implementation is straightforward with a Feed Forward Neural net with 2 hidden layers.
Customization for your own use case is super easy. Just modify intents.json with possible patterns and responses and re-run the training (see below for more info).

Installation
Create an environment
Whatever you prefer (e.g. conda or venv)

mkdir myproject
$ cd myproject
$ python3 -m venv venv






{
  "intents": [
    {
      "tag": "greeting",
      "patterns": [
         "Hi",
        "Hey",
        "How are you",
        "Is anyone there?",
        "Hello",
        "Good day"
      ],
      "responses": [
        "Hey :-)",
        "Hello, thanks for visiting",
        "Hi there, what can I do for you?",
        "Hi there, how can I help?"
      ]
    },
    ...
  ]
}






