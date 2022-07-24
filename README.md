# Caesars Cipher

# 📝 Description

Caesars Cipher project for freeCodeCamp <a href="https://learn.freecodecamp.org/javascript-algorithms-and-data-structures/javascript-algorithms-and-data-structures-projects/palindrome-checker)">JavaScript Algorithms and Data Structures</a> certification.

# 🔧 Technologies

- <img align="center" alt="Yann-Js" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-plain.svg">

# ⭕️ Rules & Tasks

> One of the simplest and most widely known ciphers is a Caesar cipher, also known as a shift cipher. In a shift cipher the meanings of the letters are shifted by some set amount.

> A common modern use is the ROT13 cipher, where the values of the letters are shifted by 13 places. Thus A ↔ N, B ↔ O and so on.

> Write a function which takes a ROT13 encoded string as input and returns a decoded string.

> All letters will be uppercase. Do not transform any non-alphabetic character (i.e. spaces, punctuation), but do pass them on.

# ⚙️ How It Works

```  
    ALPHA	KEY	BASE 	 	 	 ROTATED	ROT13
    -------------------------------------------------------------
    [A]     65  <=>   0 + 13  =>  13 % 26  <=>  13 + 65 = 78 [N]
    [B]     66  <=>   1 + 13  =>  14 % 26  <=>  14 + 65 = 79 [O]
    [C]     67  <=>   2 + 13  =>  15 % 26  <=>  15 + 65 = 80 [P]
    [D]     68  <=>   3 + 13  =>  16 % 26  <=>  16 + 65 = 81 [Q]
    [E]     69  <=>   4 + 13  =>  17 % 26  <=>  17 + 65 = 82 [R]
    [F]     70  <=>   5 + 13  =>  18 % 26  <=>  18 + 65 = 83 [S]
    [G]     71  <=>   6 + 13  =>  19 % 26  <=>  19 + 65 = 84 [T]
    [H]     72  <=>   7 + 13  =>  20 % 26  <=>  20 + 65 = 85 [U]
    [I]     73  <=>   8 + 13  =>  21 % 26  <=>  21 + 65 = 86 [V]
    [J]     74  <=>   9 + 13  =>  22 % 26  <=>  22 + 65 = 87 [W]
    [K]     75  <=>  10 + 13  =>  23 % 26  <=>  23 + 65 = 88 [X]
    [L]     76  <=>  11 + 13  =>  24 % 26  <=>  24 + 65 = 89 [Y]
    [M]     77  <=>  12 + 13  =>  25 % 26  <=>  25 + 65 = 90 [Z]
    [N]     78  <=>  13 + 13  =>  26 % 26  <=>   0 + 65 = 65 [A]
    [O]     79  <=>  14 + 13  =>  27 % 26  <=>   1 + 65 = 66 [B]
    [P]     80  <=>  15 + 13  =>  28 % 26  <=>   2 + 65 = 67 [C]
    [Q]     81  <=>  16 + 13  =>  29 % 26  <=>   3 + 65 = 68 [D]
    [R]     82  <=>  17 + 13  =>  30 % 26  <=>   4 + 65 = 69 [E]
    [S]     83  <=>  18 + 13  =>  31 % 26  <=>   5 + 65 = 70 [F]
    [T]     84  <=>  19 + 13  =>  32 % 26  <=>   6 + 65 = 71 [G]
    [U]     85  <=>  20 + 13  =>  33 % 26  <=>   7 + 65 = 72 [H]
    [V]     86  <=>  21 + 13  =>  34 % 26  <=>   8 + 65 = 73 [I]
    [W]     87  <=>  22 + 13  =>  35 % 26  <=>   9 + 65 = 74 [J]
    [X]     88  <=>  23 + 13  =>  36 % 26  <=>  10 + 65 = 75 [K]
    [Y]     89  <=>  24 + 13  =>  37 % 26  <=>  11 + 65 = 76 [L]
    [Z]     90  <=>  25 + 13  =>  38 % 26  <=>  12 + 65 = 77 [M]
```  

# ✅ Tests

rot13("SERR PBQR PNZC") should decode to the string FREE CODE CAMP</br>
Waiting:rot13("SERR CVMMN!") should decode to the string FREE PIZZA!</br>
Waiting:rot13("SERR YBIR?") should decode to the string FREE LOVE?</br>
Waiting:rot13("GUR DHVPX OEBJA SBK WHZCF BIRE GUR YNML QBT.") should decode to the string THE QUICK BROWN FOX JUMPS OVER THE LAZY DOG.</br>
