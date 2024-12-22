# 2048 Game - Android Native App

Welcome to the **2048 Game** repository! This is an Android implementation of the popular **2048 Game**. In this game, the player slides numbered tiles (cubes) on a grid to combine them and achieve higher results. The goal is to reach the tile numbered 2048 by strategically merging cubes. This app is built with **Android Native** using modern Android development practices like **MVVM** architecture, **Clean Architecture**, **Gesture Detectors**, and **LiveData**.

---

### 🎮 **Game Overview**

The **2048 Game** app offers a fun and addictive puzzle experience where players merge matching numbers to form larger numbers and try to achieve the coveted **2048** tile.

---

### 🚀 **Features**

- **Slide and Merge**: Use swipe gestures to slide cubes and combine matching numbers.
- **Game Mechanics**: The player aims to combine tiles to form larger numbers, starting with two "2" tiles.
- **Real-time Scoring**: The score updates dynamically as tiles merge.
- **Gesture Detection**: Tiles are moved using **GestureDetector** for smooth user interactions.
- **High Score Tracking**: Saves the highest score achieved using **SharedPreferences**.
- **Clean Architecture**: The game’s logic is structured into a maintainable architecture with **MVVM** and **LiveData** for state management.

---

### ⚙️ **Technologies Used**

This app leverages several Android libraries and tools to create an efficient, maintainable game:

- **Android Native**: Built using **Kotlin** and **Android SDK**.
- **MVVM**: The **Model-View-ViewModel** pattern is used for a clear separation between UI and business logic.
- **Clean Architecture**: Ensures maintainability, testability, and scalability.
- **GestureDetector**: Detects swipe gestures to slide the tiles.
- **LiveData**: Observes changes in the game state and updates the UI in real-time.
- **SharedPreferences**: Saves high scores and game settings persistently.
- **Pager**: Used to display the game grid and provide smooth navigation for different game screens.


<table>
  <tr>
    <td><img src="images/1.jpg" alt="Photo 1" width="200"/></td>
    <td><img src="images/2.jpg" alt="Photo 2" width="200"/></td>
  </tr>
  <tr>
    <td><img src="images/3.jpg" alt="Photo 3" width="200"/></td>
    <td><img src="images/4.jpg" alt="Photo 4" width="200"/></td>
  </tr>
</table>