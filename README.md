# I can play Rock Paper Scissors  
This is a Rock Paper Scissors game application that uses a webcam to predict the player's move using a trained EfficientNet_B0 model.  
The application has a graphical user interface (GUI) built with Tkinter and uses PyTorch for model inference. For the first time use model must be configured to user's camera. So, at first run it will require to capture some images for each gesture. Responses will guide the user to show each gesture.     
***
## Features

Real-Time Prediction: Captures the player's hand gesture via webcam and predicts whether it is Rock, Paper, or Scissors.

**GUI Interface**: A clean  interface with:

* Live camera feed.  

* Labels for player prediction, score tracking, and bot's choice.  

* A "Predict" button to capture and evaluate gestures.  

**AI Bot**: Generates a random choice (rock, paper, scissors) to play against the user.  

*S*core Tracker**: Tracks the player's score versus the bot.  

**Model Integration**: EfficientNet_B0 for hand gesture classification.  

## Requirements  
Prerequisites:  
* Python 3.8 or later  
* Pip package manager  

Requirements can be installed by   
`pip install -r requirements.txt`  

## How It Works

**Camera Integration:**

* Captures real-time frames from the webcam using OpenCV.

**Model Prediction:**

* Uses a pretrained EfficientNet_B0 model to classify the captured frame as Rock, Paper, or Scissors.

**Bot:**

* Randomly generates its move.

**Score Evaluation:**

* Compares the player's move with the bot's move and updates the score accordingly.

**GUI Updates:**

* Displays real-time feedback and game updates.

## License

This project is licensed under the MIT License.
