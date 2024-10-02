# Math-Game-iOS-App - made in SwiftUI

An iOS game written in SwiftUI, using MVVM.

## Gameplay
The game generates a question - two numbers you must add and generates four answers, only one of which is correct. You must tap a button with the correct answer in 5 seconds while the timer goes down, showing an animated color ring.

## Features:
- Full Firebase integration
- Five difficulties
- All highscore (for each difficulty) is stored locally using @AppStorage and is always synchronized with Firebase
- Login / register with email and password
- Upload your profile picture to Firebase Storage (resize and optimize image before uploading)
- Images are shown with AsyncImage and are cached on the device
- TopResultsView shows all users who have any high score of this difficulty
- All users' list is sorted and shows position of each user and your own position
- Animations, Gestures, Haptic feedback
- Dark mode support

