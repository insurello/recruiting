# Elm code and System Design test

There are two parts of this test. 
1. The first is in code where your goal is to improve an existing web app to make it comply with the given new requirements.
2. In the second part you design the future backend system of the app. No code is needed here but be prepared to go through your idea at the code review meeting.

## 1. Rate it! - Elm code test

This is a code test in [elm-lang](http://elm-lang.org/) which we do not expect you to already know. You are given an existing application and some new requirements.
Your mission is to fulfill these requirement by changing the code in the existing application.
The main focus of the test is the discussion and code review afterwards.
What did you learn? What was your thought process? Possible problems and improvements? Was it boring? and so on.

These are some useful Elm resources:

- https://package.elm-lang.org
- https://guide.elm-lang.org/

### The App

In this little webapp you can rate ...it! ...with horses! But what is 'it'?. It is what ever the user want to rate.

The current version of the app can be found here https://ellie-app.com/6PDCnNzpN4Pa1

#### New requirements

- A textinput for the user to enter what thing the rating is concerns. E.g. "Titanic".
- Instead of the rating being showed as a number, it should be shown as 1 to 6 filled horses (♞).
- Initially, before any rating has been provided 6 unfilled horses (♘) should be shown.
- We also need a new "Reset" button that resets the rating input.
- Would also be nice to have a text field where the user can add a comment to complement the rating
- Despite having a lot of users only a few of them are Rating it. We suspect it has to do with the UX of the app. If you have any ideas how to make it more attractive to rate it in the app please bring them to the meeting or try implementing them.

#### Ship it

When you are done with the new requirements hit save in the ellie-app code editor and copy the new URL to the app and email it as a response to the mail where you got the test from. Feel free to leave some comments about the experience and result with the URL.

Good luck!

## 2. System Design

The Elm app is just the start of a proof of concept. For this system to become a reality the company needs your help to design the backend system to make this app into a real product.

### Requirements on the system

* A users should be able to login and see their previous ratings.
  - We don't want to handle the users' passwords.
* A users should be able to create several ratings.
* A users should be able to edit their ratings, but not other user's ratings.
