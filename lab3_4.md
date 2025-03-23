
# Experiment 3: Viewing Man Pages and Finding Commands

## Objective
Learn to view manual pages and search for commands related to specific keywords using the `man` command.

## Steps

### *1. View the `gedit` Man Page*
Use the following command to view the `gedit` manual page:
```bash
man gedit
```

### *2. Find the Command to Tune ext4 File-System Parameters*
Use the `man -k` command to search for commands related to `ext4`:
```bash
man -k ext4
```

## Conclusion
Successfully viewed the `gedit` manual page and located the command for tuning ext4 parameters.

## Screenshot
![Screenshot 2025-03-19 112157](https://github.com/user-attachments/assets/c383487d-6f14-4a94-ab06-0dd6c49253db)


---

# Experiment 4: Brace Expansion in Linux

## Objective
Understand how to use brace expansion to generate strings and sequence expressions in Linux.

## Steps

### *1. Basic Brace Expansion*
Use brace expansion to generate multiple strings:
```bash
echo {apple,banana,orange}


### *2. Sequence Expression with Brace Expansion*
Use brace expansion to generate a sequence of numbers:
```bash
echo {1..10..2}
```


### *3. Combining Strings and Sequences*
Combine brace expansion with sequences:
```bash
echo file{1..3}.txt
```

## Conclusion
Successfully used brace expansion to generate strings and sequences.

## Screenshot
![Screenshot 2025-03-19 112932](https://github.com/user-attachments/assets/9d0fd970-477a-4b26-b415-6abf559ced9d)
