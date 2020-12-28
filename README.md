<h1 align="center">
  <br>
  <a href="https://ain.ua/special/about-ucode/images/tild3034-3861-4435-b232-653832626664__ucode_logo_minimal.png"><img src="https://ain.ua/special/about-ucode/images/tild3034-3861-4435-b232-653832626664__ucode_logo_minimal.png" alt="logo" width="250"></a>
      <a href=" https://static.vecteezy.com/system/resources/thumbnails/001/192/548/small/x.png"><img src=" https://static.vecteezy.com/system/resources/thumbnails/001/192/548/small/x.png" alt="logo" width="50"></a>
    <a href="https://ain.ua/special/about-ucode/images/tild3034-3861-4435-b232-653832626664__ucode_logo_minimal.png"><img src="https://purepng.com/public/uploads/large/purepng.com-ubisoft-logologosubisoftgame-companydevelopment-821523994637dtm04.png" alt="logo" width="100"></a>
  <br>
  Puzzle
  <br>
</h1>

<p align="center">
  <a href="#tasks">Tasks</a> •
  <a href="#Description">Description</a> •
  <a href="#big-idea">Big Idea</a> •
  <a href="#essential-question">Essential Question</a>
</p>

###  Description

Welcome to the **Game Development track**!

Game development is a highly popular field of programming, and is becoming increasingly competitive. However, as fun as it is, it requires experience and knowledge of many various topics, such as graphics, algorithms, AI, game physics, etc.

Let's start with a classic game born in 1985 - **Tetris**. It might seem simple, but there are a lot of things to take into account. For example, collision, order of processing events, state machine, level system, timer, etc. Developing Tetris is a great opportunity to practice designing and implementing the complete logic of a game. In this challenge, you will need to think not only about the player experience (how interesting and fun the game is to play), but also about making the game configurable and editable from the development side.

When making a game, it's important to be able to change certain parameters without editing the source code. Data binding is widely used in **Ubisoft**. It's very convenient to have a generic way to configure various game parameters, such as character movement speed, enemy attack damage, and etc. by non-programmers (e.g., game designers). For backend servers, we use config files where we need to tweak different information: connection to database, number of database workers, internal endpoints, etc.

### Guiding Questions
We invite you to find answers to the following questions. By researching and answering them, you will gain the knowledge necessary to complete the challenge. To find answers, ask the students around you and search the internet. We encourage you to ask as many questions as possible. Note down your findings and discuss them with your peers.
* What are the defining characteristics of a **tetromino**?
    * **Tetrominos**, occasionally known alternately as **tetrads**, **blocks**, **Tetriminos** (official name), or **tetriminoes**, are the blocks used in every known Tetris game. They come in seven shapes, all of which can be rotated and then dropped. Tetrominoes all have an area of four squares. In certain Tetris games, the colors of them vary. [[1]](https://tetris.fandom.com/wiki/Tetromino)
* What is the best way to describe the geometry of objects like a **tetromino**
    * Tetramino as an object is 4 connected squares
* What are the differences between various rotation systems in Tetris?
    * Different wall-kicks
    * Different rotation axes
    * Right and Left handed version
    * Spawn point
* In your opinion, what parameters of a Tetris game should be customizable via a config file?
    * Game difficult
    * Fancy colors
    * Key-binds
* What formats work best for a config file?
    *  TOML
* What influences game difficulty in Tetris?
    * Tetromino falling speed
* At what exact moment should a shape stop being movable and be locked down?
    * There are three types of Lock Down defined by the guideline, Infinite Placement Lock Down (or [infinity](https://tetris.wiki/Infinity "Infinity")), Extended Placement Lock Down (or [move reset](https://tetris.wiki/Move_reset "Move reset")), and Classic Lock Down (or [step reset](https://tetris.wiki/edit/Step_reset?redlink=1 "Step reset (page does not exist)")). A piece has 0.5 s after landing on the stack before it locks down. With infinity, rotating or moving the piece will reset this timer. With move reset, this is limited to 15 moves/rotations. Finally step reset will only reset the timer if the piece moves down a row. Some games have an option to change between 2 or 3 of these modes.
* What is a **sprite**?
    * In computer graphics, a sprite is a two-dimensional bitmap that is integrated into a larger scene, most often in a 2D video game. The term was first used by Danny Hillis at Texas Instruments in the late 1970s. Originally, the term "sprites" referred to fixed-sized objects composited together, by hardware, with a background. Use of the term has since become more general.  [[1]](https://en.wikipedia.org/wiki/Sprite_(computer_graphics))
* Why do indie games often use sprites instead of 3d models?
    * Faster and easier to implement games
* How to write a good **README** file ?
    * Use all your imagination
* What **states** can you identify in a Tetris game?
    * Loading
    * Menu
        * Leaderboard
        * Options
        * etc.
    * InGame
    * Lose
    * Win
* What are the visual artifacts of low FPS?
    * Slow animations
    * Some visual deformation
    * etc.
* What is a **tearing**
    * Screen tearing is a visual artifact in video display where a display device shows information from multiple frames in a single screen draw
* What are the ghosting and temporal latency?
* What are **V-sync** and **G-sync** technologies?
    * Vertical synchronization G-sync NVidia v-sync implementation
* What is the effect of low FPS in VR-games ?
    * Nausea

