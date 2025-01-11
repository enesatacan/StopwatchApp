🚀 Daily JavaScript App - 11

This repository is part of a daily challenge to build a JavaScript application every day. The goal is to enhance my JavaScript skills 🧠 and cultivate the habit of consistent coding. 💻✨

Stopwatch Project

Overview

This project is a simple stopwatch web application built using HTML, CSS, and JavaScript. The application allows users to start, stop, and reset the stopwatch. It dynamically updates the time display in hh:mm:ss format.

Features

Start: Begin counting time with a 1-second interval.

Stop: Pause the stopwatch without resetting the current time.

Reset: Stop the stopwatch and reset the time to 00:00:00.⏪

How It Works

HTML:

Contains a <div> element with the class stopwatch that houses the timer display and buttons.

Buttons (<img>) trigger their respective functions via onclick attributes:

watchStart()

watchStop()

watchReset()

CSS:

style.css styles the layout and appearance of the stopwatch.

A clean, responsive design ensures proper display across devices.

JavaScript:

Implements stopwatch functionality through the following:

stopwatch(): Updates time values every second and displays them in hh:mm:ss format.

watchStart(): Starts the timer using setInterval.

watchStop(): Stops the timer using clearInterval.

watchReset(): Resets the timer and clears the time display.

Usage Instructions

Clone or download the project to your local machine.

Open the index.html file in any modern web browser.

Use the buttons to control the stopwatch:

Start: Start the timer.

Stop: Pause the timer.

Reset: Reset the timer to 00:00:00.

1️⃣ Clone the repository:

git clone https://github.com/enesatacan/StopwatchApp

![image](https://github.com/user-attachments/assets/a09d0c47-7a7e-4bf1-9dad-c83be5746c05)
