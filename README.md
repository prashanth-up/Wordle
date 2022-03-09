# Wordle

<!-- PROJECT TITLE -->
### An interactive solver for the word game [Wordle](https://www.nytimes.com/games/wordle/index.html) 



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>


<!-- ABOUT THE PROJECT -->
## About The Project

This Wordle solver is based on linear search within a solution set sorted by probability and confidence score closest to latest attempt while eliminating out characters which don't appear or appear in the wrong position. 

### Built With

This project uses Python3 and its in-built libs only.

* collections.Counter
* itertools.chain
* pathlib
* operator


<!-- GETTING STARTED -->
## Getting Started

Clone this repo to your folder by using for 

HTTPS:
```
https://github.com/prashanth-up/Wordle.git
```
GITHUB CLI
```
gh repo clone prashanth-up/Wordle
```


<!-- USAGE EXAMPLES -->
## Usage

1. Run the Wordle.ipynb till the last cell where `Solve()` triggers the game to start.

2. Try one of the top suggestions presented by the Bot into your Game.

3. Enter the colour coded score(Green, Yellow, Grey) as (2, 1, 0) respectively into the interactive input shell

4. Repeat `Step 2 and Step 3` until you get your solution is accepted by wordle. (Avg Attemps 3.5)

<a href="https://github.com/prashanth-up/Wordle/blob/master/assets/example01.PNG">
  <img src="https://github.com/prashanth-up/Wordle/blob/master/assets/example01.PNG" alt="Logo" width="440" height="260">
</a>

*Here the solution was `MONTH` on (March 9, 2022)*

<!-- CONTRIBUTING -->
## Contributing

Contribute before everyone forgets this game. Then this will be sent to archive hell. 

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request


<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE.txt` for more information.


<!-- CONTACT -->
## Contact

Prashanth Umapathy - ujprashant@gmail.com

Project Link: [https://github.com/prashanth-up/Wordle/](https://github.com/prashanth-up/Wordle)
