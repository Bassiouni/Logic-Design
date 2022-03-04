# Logic Design - Assignment 1

## 1. What is the difference between analog and digital signals?

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

## 2. List the main functionalities of computer system

- Takes date as input
- Stores data/instructions in its memory and uses them as required
- Processes data and converts it into useful information
- Generates the output

## 3. What are the advantages and disadvantages of computer systems?

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

## 4. What are the main features of the first, second, third, fourth, and fifth computer generations?

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
- Gave the ability of true AI, NLP and Computer Vision development
- Had the advancement in pararell processing and superconductor technology
- Had more user-friendly interface with multimedia features

## 5. Explain the main differences between PC, workstation, mini-computer, main frame, super-computer systems

### PC

- Can't use it for compute intensive tasks
- Has one CPU and low memory
- Suitable for personal use and business use
- Able to do daily personal tasks

### Workstation

- Has more hardware capability than PC like in terms of storage capability, RAM size, etc.
- More suitable for compute intensive applications
- Not limited to 4 or 8 cores in the CPU

### Mini-computer

- Midsized multi-processing system capable of supporting up to 250 users simultaneously

### Mainframe

- Large in size, expensive in price
- Capable of supporting thousands of users simultaneously
- Executes many programs concurrently and supports simultaneous execution of programs

### Super Computer

- Super fast
- Used for AI && security

## 6. Draw the computer architecture diagram

![Image](https://avatars.githubusercontent.com/u/60100307?v=4)

## 7. Explain the main functions of input and output devices

### Input Devices

Translate data from form that humans understand to one that the computer can work with

### Output Devices

Pices of equipment that translate the processed information from the CPU into a form that humans can understand

## 8. What are the basic components of CPU?

- Arethmatic and Logic Unit
- Registers
- Control Unit

## 9. How CPU execute the following instructions?

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

## 10. Explain the main operations of the control unit of CPU

The main function of the control unit is to fetch and execute instructions from the memory of a computer.

It receives the input instruction/information from the user and converts it into control signals, which are then given to the CPU for further execution.

The CU transmits coordinating control signals to other computer components.

## 11. What is the difference between primary and secondary memories?

| Primary Memory                                | Secondary Memory                               |
|-----------------------------------------------|------------------------------------------------|
| Higher in cost                                | Cheaper than primary memory                    |
| Without it the computer can't run             | Without it the computer can run but can't boot |
| Has smaller sizes compare to secondary memory | Larger in size                                 |
| Temporarily stores date                       | permanently stores data                        |
| Fast                                          | Slow                                           |

## 12. List the main features of RAM and ROM memory unites?

### RAM

- Primary storage
- temporarily stores data
- Consists of locations or cells, each one has a unique address

### ROM

- Permanent storage
- Part of memory
- Programmed at manufacturing time
- Its content can't be changed by users

## 13. What is the purpose of system software?

It acts as a translation layer between the applications and the hardware (aka the kernel) and enables the applications to interact with the hardware and utilize it

## 14. What is the difference between data, information and knowledge?

Data are facts, we process data to get information, from the information we get knowledge

---

Work done by Muhammad Basyouni.
