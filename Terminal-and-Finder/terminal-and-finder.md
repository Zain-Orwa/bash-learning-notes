# Terminal and Finder

## Q1. What is the basic REPL?
**A1:**
REPL stands for:

- **R**ead -> read command I type.
- **E**val -> execute/evaluate the command.
- **P**rint -> print the result if there is one.
- **L**oop -> wait for the next command.

---

## Q2. Why do some Unix commands produce no output?
**A2:** 
Many commands produce no output when they succeed.

Example:

```bash
mkdir foo
```
if the command succeeds, nothing may be printed.

---

## Q3. How do I go to the Desktop and create a directory? 
**A3:**

```bash
cd ~/Desktop
```

or:

```bash
cd ~/Desktop
mkdir foo
```

---

## Q4. How do I open the directory in Finder?
**A4:**
```bash
open foo
```
Example:

```bash
cd ~/Desktop
mdir foo
open foo
```

## Q5. Is a directory the same as a folder?
**A5:**
YES.
A **directory** in the terminal is what we normally call a **folder** in Finder.

---

## Q6. How do I create a file?
**A6:**
We use the command named **touch**.

Example:

```bash
touch file.txt
```
This create an empty file called:
```text
file.txt
```

---

## Q7. How do I open the file in Vim?
**A7:**

```bash
vim file.txt
```
Or for short version:
```bash
vi file.txt
```

## Q8. How do I displa the contents of a file?
**A8:**

```bash
cat file.txt
```

---

## Q9. How do I write text into a file?
**A9:**

```bash
echo "hi" > file.txt
```

output:

```txt
hi
```

---

## Q10. What does `>` do?
**A10:**
`>` redirect the output of a command into a file.

Example:

```bash
echo "hello" > filetxt
```

This writes:

```txt
hello
```

into `file.txt`.

---

## Q11. Does `>` overwrite the file?
**A11:** 
YES. 

If `file.txt` already contains:

```txt
hello
```

and you run:

```bash
echo "hi" > file.txt
```

the old contents are replaced with:

```text
hi
```

---

## Q12 How do I remove a file?
**A12:**

```bash
rm file.txt
```

`rm` means **remove**.