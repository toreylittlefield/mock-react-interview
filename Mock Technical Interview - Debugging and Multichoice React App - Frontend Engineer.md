# Technical Interview - Frontend Engineer

Thanks for taking the time to do this excercise with us! Just relax and take a deep breath. We know that interviews are stressful. Please take a few moments to try and calm your nerves.

The coding challenge will focus on your technical abilities and pair programming skills. Please feel free to ask questions or for opinions at anytime with your interviewer. You should do your best to verbally explain your approach throughout the interview as you are coding. If you need time to pause please take your time to collect your thoughts.

---

## Sections

#### The interview is two parts

- Part 1: Debugging and Error Handling: 20 Mins

- Part 2: React Multi-choice Quiz: 45 minutes

---

## Debugging & Error Handling: 20 Minutes

For this part of the challenge you will be tasked with debugging and improving some broken code. This would not be unlike the tickets you might receive as a engineer on our team.

Please just try to do your best to demonstrate and verbalize your approach to debugging and bug fixing. Please work with your interview to try to solve the bugs and if time allows fix and refactor the code. State why the bug occured in the first place and what improvements to the code could be made to prevent such bugs in the future.

Please use whatever debugging tools you prefer or you think are best for the job. You can debug in VS Code, the browser dev tools or whatever your preference. Please ask any questions at anytime. Feel free to use any outside resources or google.

### Debug Problem 1:

[Parents & Children](https://codesandbox.io/embed/mutable-wildflower-lnum3?fontsize=14&hidenavigation=1&theme=dark)

The goal here is to fix a bug. We want the colors of the parents and children to work independently when clicked. Currently, `click` events causes the parent & children to change background colors at the same time.

### Debug Problem 2:

```JS

```

---

## React Multiple Choice Quiz App: 45 Minutes

Please have a fresh create-react-app ready to go with the boilerplate code removed from the `App.js`.

Again please verbalize and communicate your approach with your interviewer. Please ask any questions at anytime. Feel free to use any outside resources or google.

For this exercise you and the interview will create a simple multiple choice quiz app.

### Tasks To Complete

1.  Go to [https://opentdb.com/api_config.php](https://opentdb.com/api_config.php)

    - Select the `Number of Questions` to be `5` and the `Type` as `Multiple Choice` you can pick whatever `category` or `difficulty` you want for fun or leave them blank.
    - Generate the `URL` for your app and we'll use it to fetch quiz data for our application.

2.  Use the `URL` to create the multiple choice quiz `containers`/elements in your `React` application.

3.  After that's working. Add make a `loading` or `progress` to screen. Like a loading spinner but no need to make it fancy. Make the loading screen appear for `2 seconds` before displaying the quiz data from `Task 2` above. Also if the is an `error` get the data show the `error` as a string on the screen.

4.  Create a `progress bar` to track the progress of the users responses to the multiple choice questions. For example if the selected 2 questions of 5 so far the `progress bar` can simply be a string `40%`. If they then select a third answer `60%` etc...
5.  When the user completes all `5` questions then the user you can either have a `submit` button or simply show the `total quiz` score for like the `progress bar` example it could say how many answers they got correct out of the total.

6.  More tasks are available if completed early.
