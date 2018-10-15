# Blind_Care
Authors: Naman Kanwar, Arun Suresh, Harnoor Singh, Shivam

## Inspiration
Inspired by a few blind people who use echolocation to "see" things around them, we have developed an interface that would help a blind person listen to have a feeling of where they belong in the society and enjoy the little things and experiences of everyday life.

## What it does
The interface is connected to a camera (which could be then possibly integrated with cameras on pen tips) which records real time videos of events, parse it into multiple frames - analyze it piece by piece and finally using a text to speech interface, dictates what it sees.

## How we built it
For Building the interface, we used the Apple Artificial Intelligence API that contains a pre-trained data set that could be readily used. However on experimenting we learned that real time video/image has a lot of noise, and that it would take a long time to train the data set for practical purposes. Therefore we created a small data set with real time images (taken using phone cameras) and further trained the available data set to a considerable degree of accuracy. With enough time, this can further be implemented and generalized into more diverse data sets, achieving its intended purpose.

## Challenges we ran into
As previously mentioned, we learned that the time it takes to train a simple data set is longer than we had previously anticipated. Therefore we had to restrict our data set and only work towards training specific limited amount of data. We also tried using the Microsoft Azure API to integrate into our interface - however, we soon learned that we had a few dependency issues that we could not resolve. We wasted over seven to eight hours trying to get that to work. In the end, we moved to using the Apple's AI API

## Accomplishments that we're proud of
In the course of this Hackathon, we managed to code and implement successfully in 3 languages - Python, Java and ios. Even though we did not pursue our completed Python project to integrate into an android app (we had to download and learn to use a cross platform program to execute that) - we were able to successfully implement and get positive results in all three languages.

## What we learned
We learned various new methods of coding with AI and Machine Learning Algorithms. We also gained a clearer picture on how to use APIs and integrate them into a common framework that we had in mind. Also, in addition to that, we were also able to learn a bit of implementation using neural networks.

## What's next for BlindCare
We hope to perfect our code in the future, so that it could be then used in various diverse environments. We are also trying to get to use pre-existing APIs and make the best use of them, therefore extending the reach and impact of BlindCare

## Built With
IOS,
machine-learning,
apple-machine-learning API
