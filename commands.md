# GREP

```bash
grep text *.txt #show text in all files with extension txt
grep -A 1 text #show after line where is the text
grep -n "text" #show line where is the text
grep -e, #can find with pattern
```

# CUT

```bash
cut -f 1 -d "." #firt find before .
```

# LSOFT

```bash
lsof -f | grep program.log #show process is use program.log
```

# ECHO

```bash
echo -n #show without tr
```

# SED

```bash
sed -n "10p" text.txt #show line 10 in text.txt
sed 's/text/\n&/g' #replace for text with tr, when is use &
```

# TR

```bash
tr '\n' ' ' #replace tr for espace
```