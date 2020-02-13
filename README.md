#ProGrad

##LAB | CricPro ScoreBoard 

##What should you do?

Fork this repo
Clone this repo
Practice JavaScript basics - operators, conditions, loops
How do you submit?
Upon completion, run the following commands:

git add .
git commit -m "prograd ID"
git push origin master
Create a pull request so your teaching mentors can check your work.

Starter code
The src/data.js contains an array of 250 players. We are talking about the array of 250 objects containing the info about each player. Here is one example of how the data is displayed:

{
    name: 'Ashley Young',
    age: 34,
    debut: 2011,
    team: 'Manchester Utd',
    position: 'Defender',
    country: 'England',
    awards: [
        {
            name: "Golden Foot",
            year: 2015
        }
    ]
}
Tests
Ohh yes! We have our beloved tests, and you already know how this works. Open the SpecRunner.html file on your browser and start coding to pass the test. Remember to focus on one test at a time and read carefully the instructions to understand what you have to do.

Trial 1: Gotta coach em all!
Every team starts off with a manager. We need someone to take care of them when Alex isn't around. Create a function createManager() that gets the manager's details managerName, managerAge, currentTeam, trophiesWon in the same order, and return an array with the manager's details.

Trial 2: Plan of Action!
