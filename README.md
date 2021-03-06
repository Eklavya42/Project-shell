# ASH (Ares SHell) - Unix Shell in C

OS Project for Operating System Course at Cluster Innovation Centre, University of Delhi:

## Language

 We are going with "C" as other familiar language like python has most of the low-level stuff already done and gives less opportunity to learn more about really making a unix shell. Another language option was Nim but it required us to learn Nim and then work on it, which was too much for us.

## Implementation

- Built-in functions:
  - cd/chdir
  - help
  - exit
  - ls
  - mkdir/md
  - pwd
  - rmdir/rd
- Check for dotfile
- Run normal application example `>> subl text.txt`

## ToDo

- [ ] Using dotfile
- [ ] Add more built-in functions
- [ ] Make better ui. Colors?
- [x] New Window
- [x] Add current location to prompt

## Usage

To run the shell get main executable first  

```
gcc main.c -o main
```

Then create runner  executable
```
gcc runner.c -o shell
```

Run shell output files

```
./shell
```


## Screenshot

![ash (Ares SHell)](https://github.com/Eklavya42/Project-shell/blob/master/images/Screenshot%20from%202018-11-10%2019-15-33.png?raw=true "ash help")
![ash (Ares SHell)](https://github.com/Eklavya42/Project-shell/blob/master/images/screenshot1.png?raw=true "ash new window")


## Members

- Dhairya Kathpalia
- Eklavya Chopra
- Gaurav
- Hardik Kapoor
- Harshit Joshi
