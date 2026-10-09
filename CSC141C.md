# CSC141-C: Foundations of Computer Science I/Lab

[Home](index.md) | [About Me](about.md) | [All Courses](index.md#my-fall-2026-courses)

---

## About This Class

Hi, my name is **Michael Cruz**, and this page is about my Foundations of Computer Science I/Lab class. I am learning basic programming with Python and getting more practice writing code.

## Python Work I've Done: Pets and Dictionaries

One of my programs uses **dictionaries** to store information about pets and their owners. I used characters from Sonic games as examples, which made the assignment a little more interesting to me.

### My Python Code

```python
# Store dictionaries about pets in a list.
pet_1 = {'animal': 'chao', 'owner': 'cream'}
pet_2 = {'animal': 'fox', 'owner': 'tails'}
pet_3 = {'animal': 'echidna', 'owner': 'knuckles'}

pets = [pet_1, pet_2, pet_3]

for pet in pets:
    print(pet['owner'], "has a", pet['animal'])
```

### What the Program Prints

```text
cream has a chao
tails has a fox
knuckles has a echidna
```

### What This Code Does

- Each **dictionary** stores an animal and its owner.
- The **list** named `pets` keeps all three dictionaries together.
- The **`for` loop** goes through the list one pet at a time.
- The **`print()` function** shows the owner and animal from each dictionary.

The last line says `a echidna` because that is the exact text in my code. A future improvement would be to make it print `an echidna`.

## What I've Learned

This program helped me practice using lists, dictionaries, loops, and printing information. It also showed me how one loop can do the same task for multiple items without writing a separate `print()` statement for each one.

## My Goals

I want to get better at writing Python on my own and understanding why my code works. I also want to improve my problem-solving and debugging skills.

## Course Image

<img src="images/csc141-python.jpg" alt="Python programming for Foundations of Computer Science" width="650">

*I can add a screenshot of this program or my Python editor here.*

---

[Back to the homepage](index.md)
