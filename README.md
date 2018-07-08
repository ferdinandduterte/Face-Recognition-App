# Face-Recognition-App

##Simple face recognition app that you could use for your projects

## Requirements:
    Python3

## How to:
    1. `python -r dependencies.txt` to install dependencies

    2. Download pretained models at : https://drive.google.com/file/d/0Bx4sNrhhaBr3TDRMMUN3aGtHZzg/view?usp=sharing

        Then extract those files into the 'models' folder
    
    3. `python main.py --mode "input"` to register you as a new user. Input your name. Then start turning left, right, up, and down slowly to avoid blurred images as our training data. Try to mimick the demo below as much as possible to achieve best accuracy.

    ![GIF Demo](https://media.giphy.com/media/3o7aD7CZ6C3RLCvLgs/giphy.gif)

    4. `python main.py` to run the program of Face Recognition. You'll see something similar to the demo below.

    ![GIF Demo](https://media.giphy.com/media/l378mx3j8ZsWlOuze/giphy.gif)

    5. To register new user, repeat step 3 with that new person.

## Credits:
    -  Code from:
    https://github.com/vudung45/FaceRec
    -  Pretrained models from: https://github.com/davidsandberg/facenet