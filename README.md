# RMC – Roman Modifier Cipher

A cipher I made, being a mix of both a shift cipher (in a sense) and Morse (reason why literal spaces are represented with /), and also Roman numerals, because… why not.


---

How to MANUALLY Read

x2 - 1 Rule

Or basically, how to read any number.

Take -vii as an example:

1. Identify the Roman numeral: vii → 7


2. Multiply by 2 → 14


3. If there’s a - at the start, subtract 1 → 13



Hooray! Result is 13.


---

Modifiers

The fun part!

- Nothing / plain letters
   - Just take an RMC number (like -vii) → convert to a number (13) → find the corresponding letter in the alphabet → m (the 13th letter).

- numbers
   - outputs the number itself (assigning -i to 1, i to 2, … v to 0)

   - Example:

   - #-i → 1
#i  → 2
#-ii → 3
...
#v → 0

- & / symbols
   - Reads from a special table (top-to-bottom, left-to-right):
```
‎. | ) | " | / | -  
‎, | { | ' | \ | +  
‎! | } | : | < | #  
‎? | [ | ; | > | _  
‎( | ] | * | = | |
```

   - Example:

   - &-i → .
&i  → ,
...
&-xiii → |



---

# How to ~~be lazy~~ Read Easily

We also have a website for this, which lets you encode, decode, and even learn RMC if you know what you’re doing :3

That’s it. Bye.
