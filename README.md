<!-- # 🐷 Pig Latin Activity

[Oday ouyay eakspay igpay atinlay?](http://www.wikihow.com/Speak-Pig-Latin)

In this activity we're going to create an application that translates regular English words into Pig Latin.

### 💬 Rules of Pig Latin

- For words beginning with a vowel, add "way" to the end.
- For words beginning with one or more consonants, move all of the first consecutive consonants to the end, and add "ay".
- If the first consonants include "qu", move the "u" along with the "q". Don't forget about words like "squeal" where "qu" doesn't come first!
- "y" is treated like a vowel in appropriate circumstances.

There are many [examples](http://funtranslations.com/pig-latin) of Pig Latin translators out there on the internet to give you inspiration.

### ▶️ Getting started

This is a very difficult problem to solve. Take the time to plan your approach and brainstorm with your team.

This project is going to utilize React for the UI and the JavaScript logic. There is already some code inside the React application that will provide a UI for the Pig Latin project. Your job is to create the logic. All the code you'll need to write for this app is going to be inside one function in the `/src/App.js` file.

After you accept the assignment from GitHub Classroom, you'll want to install all the necessary dependencies.

```bash
$ cd pig-latin-challenge
$ yarn
```

Then you are ready to start a server to run the application.

```bash
$ yarn start
```

Now you're ready to code!

To get started, find the `myPigLatinCodeHere` function, and write your code. Every time you save your updated file, the browser window displaying your app will reload.

---

### 🐽 Pig Latin Challenge

Oday ouyay eakspay igpay atinlay? If you are scratching your head at that statement, we at LEARN Academy have you covered. Our development team has been tasked with creating a Pig Latin translator application. This app will take regular English words and covert them to Pig Latin. With this application you will eakspay igpay atinlay uentlyflay in no time!

**Story 1: In order to see English words converted to Pig Latin, as the user of the application, I need to see words beginning with a vowel translated to add "way" the end.**

**Branch:** vowel-functionality

**Acceptance Criteria**

- Can type any word that begins with a vowel in the text input (e.g. apple)
- Can hit the submit button
- Can see the words that begin with a vowel translated to Pig Latin and rendered to the page (e.g. appleway)

**Story 2: In order to see English words converted to Pig Latin, as the user of the application, I need to see words that have "qu" in the first syllable translated by moving all the consonant and the "u" to the end and add "ay".**

**Branch:** qu-functionality

**Acceptance Criteria**

- Can type any word that has a "qu" in the first syllable in the text input (e.g. squeal)
- Can hit the submit button
- Can see the words that have a "qu" in the first syllable translated to Pig Latin and rendered to the page (e.g. ealsquay)

**Story 3: In order to see English words converted to Pig Latin, as the user of the application, I need to see words that have no vowels other than "y" translated by moving all the consonant to the end and add "ay".**

**Branch:** y-functionality

**Acceptance Criteria**

- Can type any word that has no vowels other than "y" in the text input (e.g. fry)
- Can hit the submit button
- Can see the words that have no vowels other than "y" translated to Pig Latin and rendered to the page (e.g. yfray)

**Story 4: In order to see English words converted to Pig Latin, as the user of the application, I need to see words that have one or more consonants translated by moving all the consonant to the end and add "ay".**

**Branch:** consonant-functionality

**Acceptance Criteria**

- Can type any word that starts with one or more consonants in the text input (e.g. through)
- Can hit the submit button
- Can see the words that start with one or more consonants translated to Pig Latin and rendered to the page (e.g. oughthray)

### 🏔 Stretch Challenges

- As a user, I can see pleasant stylings on the application.
- As a user, I can input a sentence that includes punctuation.
- As a user, I can input a sentence that includes lower and upper case words.
- As a user, I can see a message if I am not using the application correctly.

### 👩‍💻 Developer Stretch Challenges

- As a developer, I have a well commented application.
- As a developer, I have well written README file with instructions on how to access my repository.
- As a developer, my variables are all named semantically.
- As a developer, I have refactored and efficient code.
- As a developer, I have my application [deployed as a live website](https://render.com/docs/deploy-create-react-app).

### 🎙 Project Demos

Each team will give a brief (3 minute) presentation of their application. Presenting your project will allow you to practice communication and coding vocabulary. Presentations are not a judgement of your work or ability as each team will have different weaknesses and strengths. Presentations allow other members of the cohort to appreciate a different approach to solving a complex problem.

- Full team: show off your application's user interface (UI)
- First team member: What was your team's approach to solving this problem? Did the initial approach work out in the end?
- Second team member: What was the hardest thing about this project? What is your biggest take away?
- Third team member (if applicable): How did you manage the workflow in a group of three? -->


Team Venus Pseudocode
Project Name: Pig Latin Translator
- Want to create a function called myPigLatinCodeHere that will accept a string as an argument
- Goal: translate English words into Pig Latin
- Tackle each story separately, one at a time
- Once we get the functionality down for each story, in the end, it'll come together as one

Story 1 Psuedocode
- Checkout a new branch name vowel-functionality
- Input is a word (string) that begins with a vowel
- Create a function myPigLatinCodeHere
- Using conditional statements, we will want to determine if the word begins a vowel
- If it does begin with a vowel we'll want to add "way" to the end of that word using concatenation
- Output would be that word with "way" added to the end


Story 2 Psuedocode
- Checkout a new branch name qu-functionality
- Input is a word (string) that begins with "qu" in the first syllable
- In the function, myPigLatinCodeHere, we will use conditional statements to determine if the word starts with "qu" 
- If it does begin with "qu" we will want to move the "qu" to the end of the word using for loop?
- Once the "qu" has been moved to the end of the word, we'll now want to add "ay" to the end of that new word
- Output is the word translated to pig latin
    - "qu" moved to the end of the word and then adding "ay" to the end of that


Story 3 Psuedocode
- Checkout a new branch name y-functionality
- Input is a word (string) that has no vowels other than "y"
- In the function, myPigLatinCodeHere, we'll use conditional statements to determine if the word has no other vowels other than "y"
- If there are no other vowels other than "y" we will move the constonants to the end of the word
- Then we will add "ay" to the end of that new word
- Output is the word translated to pig latin
    - The constonants moved to the end of the word and then adding "ay" to the end of that
    - "fry" would be "yfray"


Story 4 Pseudocode
- Checkout a new branch name consonant-functionality
- Input is a word (string) that starts with one or more consonants
- In the function, myPigLatinCodeHere, we will use conditional statements to determine if the word starts with consonants
- If it starts with one or more consonants, we will move those consonants to the end of the word
- Then we will add "ay" to the end of that new word
- Output is the word translated to pig latin
    - The consonants moved to the end of the word and then adding "ay" to the end of that
    - "through" would be "oughthray"


