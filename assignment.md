# Logic Design - Assignment 1

## What is the difference between analog and digital signals?

<!-- ### Analog Signals

- Have infinite number of values
- Have minimum and maximum values
- It can be either periodic or non-periodic
- Mostly denoted by sign waves
- The analog signal bandwidth is low
- Analog signals are deteriorated by noise throughout transmission as well as write/read cycle
- Consumes lesser bandwidth compared to a digital signal

### Digital Signals

- Digital signal has a finite number, i.e., 0 and 1
- It is denoted by square waves
- Digital signal uses discrete 0 and 1 to represent information
- The digital signal bandwidth is high
- Relatively a noise-immune system without deterioration during the transmission process and write/read cycle -->

| Analog Signals                            | Digital Signals                                               |
|-------------------------------------------|---------------------------------------------------------------|
| Have infinite number of values            | Digital signal has a finite number, i.e., 0 and 1             |
| Have minimum and maximum values           | It is denoted by square waves                                 |
| It can be either periodic or non-periodic | Digital signal uses discrete 0 and 1 to represent information |
| Mostly denoted by sign waves              | It is denoted by square waves                                 |
| The analog signal bandwidth is low        | The digital signal bandwidth is high                          |
| Analog signals are deteriorated by noise throughout transmission as well as write/read cycle | Relatively a noise-immune system without deterioration during the transmission process and write/read cycle |

## List the main functionalities of computer system

- Takes date as input
- Stores data/instructions in its memory and uses them as required
- Processes data and converts it into useful information
- Generates the output

## What are the advantages and disadvantages of computer systems?

### Advantages

- It can process data in high speed
- It has high accuracy rate
- Can store a lot of data in different ways
- It is not a human so it can't say "I'm tired of work"
- it has the ability to adapt or be adapted to many different functions or activities
- It can reduce human interactivity while executing the instructions or in processing
- it can reduce the cost of paper making and paper work

### Disadvantages

- Can't think by itself
- Depends on human in building it and giving it instructions
- It is affected by the environment
- It can't feel or taste

## What are the main features of the first, second, third, fourth, and fifth computer generations?

### First Generation

- Used vacuum tube technology
- Was very big, not portable and slow
- Was programmed by binary (I believe it used punch cards at sometime)
- Had a very high cost
- Depended on AC and had a high power consumption

### Second Generation

- Used transistors, as a result its size was smaller than the first generation and faster
- Was more reliable
- Had lower power consumption and generated heat
- Was programmed by assembly and machine language
- Still had a high cost and required AC

### Third Generation

- Used ICs in place of transistors, which lead to:
  - a smaller size
  - a faster performance
  - less power consumption and generated heat
- Was more reliable
- Had less maintenance
- Still not cheap and required AC
- Supported high-level programming language

### Forth Generation

- Used VLSI technology
- Was very cheap
- Was portable as its size was smaller and reliable
- Used pipeline processing
- Ditched the require of AC
- Supported the interconnected networks (aka the internet)
- In that time the computers became easily available and used for personal use

### Fifth Generation

- Used ULSI technology
- Gave the ability of true AI development and NLP
- Had the advancement in pararell processing and superconductor technology
- Had more user-friendly interface with multimedia features

## Explain the main differences between PC, workstation, mini-computer, main frame, super-computer systems

### PC

### Workstation

### Mini-computer

### Mainframe

### Super Computer

## Draw the computer architecture diagram

## Explain the main functions of input and output devices

## What are the basic components of CPU?

## How CPU execute the following instructions?

```text
int a=10;
int b=20;
if (a!=b)
then c=a+b;
else c=a;
end if
```

<https://github.com/MuhammadBasyouni/A1Q9-CPU-ASM-Code>

```asm
.code:
  mov dx, 1010b
  mov a, dx
  mov dx, 10100b
  mov b, dx
  cmp a, b
  jne .NEQ
  mov c, a
  jmp STOP
.NEQ:
  mov c, a
  add c, b
STOP:
  ret
```

## Explain the main operations of the control unit of CPU

The main function of the control unit is to fetch and execute instructions from the memory of a computer.

It receives the input instruction/information from the user and converts it into control signals, which are then given to the CPU for further execution.

## What is the difference between primary and secondary memories?

## List the main features of RAM and ROM memory unites?

## What is the purpose of system software?

## What is the difference between data, information and knowledge?
