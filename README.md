# gzclp
A local web app to track your GZCLP workouts (in progress). GZCLP is a linear progression based weightlifting program that focuses on compound lifts (squats, bench press, deadlift, overhead shoulder press) and progressive overload using a mix of intensity/rep ranges. More info here: https://www.saynotobroscience.com/gzclp-infographic/

# Motivation
This app is designed to be as simple to use as possible when you're in the gym.

The guiding principle is for there to be *as little configuration as possible.* On top of that, this app is designed to have a great user experience along with a beautiful interface.

# Design decisions
* Web app using vanilla JavaScript and as few frameworks as possible
* All data is stored locally on-device in HTML5 localstorage
  * Pros: no account management, no servers, can run as a static website hosted on github.io — this basically means its free, no ongoing costs to maintain
  * Cons: if users change their phone they have to start from scratch (potential for JSON export/import down the line)

# Features
* Plate calculator based on available weights
* 3 min rest timer that starts automatically after each set
* Custom rep count for failure / AMRAP sets
* No custom exercises / warmups (simplicity is a feature)

# Mockups
![image](https://github.com/p44v9n/gzclp/assets/3392057/f4de96bd-05d5-455e-b3a4-85875ac7a530)
