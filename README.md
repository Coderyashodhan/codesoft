# codesoft
# TASK-01
 CodBot - Rule-Based Chatbot in Python

CodBot is a simple rule-based chatbot written in Python. It responds to basic user inputs using predefined rules with `if-elif-else` conditions. This project is great for beginners learning about Natural Language Processing and chatbot design.

 Features

- Greets the user
- Responds to common inputs like:
  - “hello”, “hi”, “hey”
  - “what’s your name?”
  - “how are you?”
  - “help”
- Ends the chat when user says “bye”
- Handles unknown inputs gracefully

 Sample Conversation
You: hello
CodBot: Hello! How can I assist you today?

You: what's your name
CodBot: I'm CodBot, your friendly AI assistant.

You: bye
CodBot: Goodbye! Have a great day 😊

# TASK-02

Tic-Tac-Toe with AI (Minimax Algorithm)

This is a simple **Tic-Tac-Toe** game in Python where a human player (`X`) plays against an unbeatable AI (`O`) powered by the **Minimax algorithm**. The game runs in the terminal and is designed to help understand game theory and basic AI search algorithms.

 About the AI

The AI uses the **Minimax algorithm** to evaluate all possible future game states and always makes the optimal move. It will never lose!

- `X`: Human player  
- `O`: AI opponent

 Sample Gameplay
Tic-Tac-Toe (You are X, AI is O)
| |
| |
| |
Enter row (0-2): 0
Enter col (0-2): 0
O| |
| |
| |
...


# TASK-03

Movie Recommendation System (Collaborative Filtering)

This is a simple **Collaborative Filtering** based movie recommender system built using **Python**, **Pandas**, and **scikit-learn**. It recommends movies to users based on the ratings of similar users using **cosine similarity**.

Key Features

- User-User Collaborative Filtering
- Uses cosine similarity to find similar users
- Recommends unrated movies based on similar users' preferences
- Simple, fast, and easy to understand

---

 Sample Dataset

```python
user_id | movie            | rating
--------|------------------|-------
1       | Avengers         | 5
1       | Iron Man         | 4
1       | Captain America  | 5
2       | Avengers         | 4
2       | Thor             | 5
3       | Iron Man         | 5
3       | Thor             | 3


