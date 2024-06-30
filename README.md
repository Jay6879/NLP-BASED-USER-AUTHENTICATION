Traditional static authentication methods, such as passwords, face increasing vulnerability due to technological advancements and evolving attack strategies. Continuous authentication emerges as a viable solution, wherein users granted account access are continually monitored to ensure ongoing verification against potential impostors with unauthorized access. Mouse dynamics, encompassing a user's mouse movement behavior, proves to be a promising biometric for continuous authentication schemes. Several evaluation scenarios are explored: RNN models including LSTM, BiLSTM and GRU models. A deep dive here the RNN models have been experimented with Embeddings and without embeddings. Additionally SVM and Random forest models have also been tested. The peak average test accuracy of 91.2% was achieved with BiLSTM models implemented with embeddings among the deep learning models.

DATASET URL: https://github.com/balabit/Mouse-Dynamics-Challenge

The Dataset used for the project is the Balbit mouse dynamics challenge. The collection is composed of anonymized and aggregated data related to mouse movements, encompassing the behaviors of 10 unique users. This data gathering occurred over a two-month period, during which participants conducted their regular day-to-day work tasks. The dataset includes a total of 5,500 sessions, with an average of approximately 55 sessions per user per day.

The data consists of a collection of csv files, each file representing session data for a particular user. The columns in the file are as follows -

●	record timestamp - The unix timestamp of the mouse event
●	client timestamp - The client side timestamp of the recorded mouse event.
●	button - The status of the mouse during the event, it takes values like NoButton, Scroll, Left, Right
●	state - state of the mouse, has values like Move, Up, Down, Pressed, Released
●	x - The x-coordinate of the mouse on the screen
●	y - The y-coordinate of the mouse on the screen

This project proposes a novel framework integrating sophisticated techniques such as
embeddings extraction using Transformer models with cutting-edge machine learning
algorithms such as Recurrent Neural Networks (RNN).

Layout of Experiments

<img width="485" alt="image" src="https://github.com/Imsravan/nlpBasedUserAuthentication/assets/41965112/b15d2f9f-9ec8-4fa5-8fde-a17e71f969bb">


