This is my personal portfolio app, built entirely with Flutter. I originally created this as the final project for my SD2 Lab course to showcase what I've learned about modern app development,state management, and UI design.

# What's inside?
I wanted to make something that feels alive rather than just a static page, so I focused heavily on interactive animations and keeping the code architecture clean.

• GetX State Management: I used GetX to handle the logic. It manages things like the dark/light mode toggle and my projects list, keeping the UI completely separated from the business logic.

• Interactive UI: There are some animations built in:

* Click on any project card and it expands to show more details.

* The skill badges physically scale down when you press them.

* The dark/light theme toggle button morphs its shape, color and icon when clicked.

• Fully Responsive: The app adapts seamlessly whether you are viewing it in Light Mode or Dark Mode.

# How to run this locally
If you want to clone this repo and run it on your own machine, just follow
these steps:

1. Make sure you have Flutter installed on your machine.

2. Clone this repository:
git clone https://github.com/Saikat Das/MyPortfolio-flutter-app

3. Navigate into the project folder in Android Studio.

4. Install all the necessary packages:
flutter pub get

5. Run the app on your emulator, browser, or connected device:
flutter run
