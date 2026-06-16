# 💘 Student Matchmaking using Linear Programming

What happens when you combine mathematics, personality quizzes, and a little bit of chaos?

This project takes the classic Assignment Problem from Linear Programming and uses it to play matchmaker among students. Instead of assigning workers to jobs, we assign students to other students based on how compatible they are.

Because apparently even romance deserves optimization.

---

## 🎯 The Idea

Students filled out a questionnaire about:

* Personality traits
* Interests and hobbies
* Lifestyle preferences
* Gender preferences
* Qualities they look for in a partner

These responses were then transformed into a compatibility score.

The lower the incompatibility score, the better the match.

Once the compatibility matrix was ready, the Hungarian Method stepped in and found the optimal set of matches while minimizing total incompatibility.

In simple terms:

**We let Linear Programming do the matchmaking.**

---

## 🤔 Why?

Because solving transportation problems and assigning workers to machines is cool...

...but assigning people to people is way more entertaining.

This project explores how optimization techniques can be applied to a completely different and surprisingly relatable problem.

---

## ⚙️ How It Works

### Step 1: Collect Data

Google form used : https://docs.google.com/forms/d/e/1FAIpQLSfxQ22DjXbBSaMfWzoY3nDYCMSGQmaDfoFqPUOJWbJqdTtEow/viewform?usp=header

Students answered a Google Form containing questions about their:

* Personality
* Interests
* Lifestyle
* Preferences

### Step 2: Build a Compatibility Matrix

Every student was compared with every other student.

A score was calculated based on:

✅ Shared interests

✅ Similar personalities

✅ Lifestyle compatibility

✅ Preference matching

The result was a giant matrix showing how compatible everyone was with everyone else.

### Step 3: Let Math Cook

The Hungarian Algorithm was applied to find the best one-to-one assignments.

The goal:

> Minimize incompatibility and maximize good matches.

No bias.

No favouritism.

Just pure mathematics.

---

## 📊 Example

Instead of:

```text
Alice → Bob
Charlie → Diana
```

the algorithm evaluates all possible pairings and selects the combination with the best overall compatibility score.

Sometimes one student may remain unmatched.

That's not a bug.

That's mathematics being brutally honest.

---

## 🛠️ Tech Stack

* Python
* Google Colab
* Pandas
* NumPy
* Hungarian Algorithm
* Linear Programming Concepts
* Google Forms

---

## 🚀 Future Ideas

* Add more personality dimensions
* Build a web app version
* Generate compatibility reports
* Add friendship matching mode
* Add "enemy matching" mode for maximum chaos

---

## ⚠️ Disclaimer

This project is for fun and educational purposes.

The algorithm does not guarantee friendship, love, marriage, soulmates, or happily-ever-afters.

If it accidentally predicts your perfect match, that's between you and the mathematics.

---

## 👥 Contributors

* Abitatha Roy
* Harshit Kumar Singh

Made with Python, Linear Programming, and questionable confidence in algorithms.
