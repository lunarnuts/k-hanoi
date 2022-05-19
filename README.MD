### General solution for k-peg case for Hanoi towers puzzle

##### Program asks user to input number of disks and number of pegs, then prints solution in form:

```

MacBook-Pro-Nursultan-Kuandyk:k-hanoi nursultan$ ./K\ Peg\ Tower\ of\ Hanoi
Number of pegs? 4
Number of disks? 6

---

State of Peg 1 (Top to Bottom): 1 2 3 4 5 6
Number of Steps = 0

---

Move disk 1 from Peg 1 to Peg 4 (Legal)
Move disk 2 from Peg 1 to Peg 2 (Legal)
Move disk 3 from Peg 1 to Peg 3 (Legal)
Move disk 2 from Peg 2 to Peg 3 (Legal)
Move disk 1 from Peg 4 to Peg 3 (Legal)
Move disk 4 from Peg 1 to Peg 4 (Legal)
Move disk 5 from Peg 1 to Peg 2 (Legal)
Move disk 4 from Peg 4 to Peg 2 (Legal)
Move disk 6 from Peg 1 to Peg 4 (Legal)
Move disk 4 from Peg 2 to Peg 1 (Legal)
Move disk 5 from Peg 2 to Peg 4 (Legal)
Move disk 4 from Peg 1 to Peg 4 (Legal)
Move disk 1 from Peg 3 to Peg 1 (Legal)
Move disk 2 from Peg 3 to Peg 2 (Legal)
Move disk 3 from Peg 3 to Peg 4 (Legal)
Move disk 2 from Peg 2 to Peg 4 (Legal)
Move disk 1 from Peg 1 to Peg 4 (Legal)

---

State of Peg 4 (Top to Bottom): 1 2 3 4 5 6
Number of Steps = 17

```

### Generating executable

Program is provided with Makefile, to compile it simply type "make -f Makefile" in cmd if you have cmake or make installed.
This will generate executable file name "K Peg Tower of Hanoi"

[![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2Flunarnuts%2Fk-hanoi&count_bg=%2379C83D&title_bg=%23555555&icon=&icon_color=%23E7E7E7&title=hits&edge_flat=false)](https://hits.seeyoufarm.com)
