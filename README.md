# Fields-records-and-files

## Quick fire five

- **What are the uses of random.shuffle(), random.getrandbits(1) and random.choice()?** Getrandbits generates numbers with that amount of bits e.g 1 bit could give you 0 or 1. Randomshuffle shuffles values. Randomchoice gives you a random item from a given sequence or list etc.

- **What is a nested block of code? Can subroutines definitions be nested? What visibility do they have?**

- **What are the problems with using global scope? What advantage do local namespaces have? In what ways are the different versions of import synax related to namespaces?** A disadvantage of the global scope would be that it would affect the whole program. Local scopes allow you to use the same variable name. If you import something FROM something you can use it directly rather than having to do the module.the function e.g import randint from random means you can use randint rather than random.randint. However, the name must not be the same as a function as there could be issues.

- **What is the difference between a variable declaration and assignement. Why would this perhaps confuse a Python programmer? What is the dead parrot sketch?**

## Files

A file is a data structure for storing data. The number of items of data stored in the file can vary in time and the amount of data is not limited in the way that other data structures are because files rely on **secondary storage** such as magnetic disk for their storage unlike arrays which rely on RAM storage.

By using secondary stoarage, files **persist in time** because secondary storage is non-volatile whereas RAM is volatile.

Files have types, such as **text**

## Text files

Text files are files whose contents are sequences of characters organised on a line by line basis. May be opened and read in a text editor such as Microsoft's WordPad.
