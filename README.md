# Operating Systems - Exercise 4 - GitHashingExercise

## School of Electrical & Computer Engineering - Aristotle University of Thessaloniki

- Name: Strimpas Nikolaos
- SID: 10461
- Email: snikolag@ece.auth.gr

This repo houses the 4th exercise of the Operating Systems class. A brief explanation of each task is the following:

### Exercise 4 - Part 1

#### Task 1

The creation of the directory that houses this repo and this `README.md` file are the deliverables of this task. One can do this with the following commands:
```bash
mkdir GitHashingExercise
cd GitHashingExercise
touch README.md
<your-favourite-text-editor> README.md
# Write some text
```
#### Task 2

For this task, a shell script that generates the hash of a four digit number must be created. Said shell script is written in the `hash_script` file and is written in [`bash`](https://www.gnu.org/software/bash/). To run it, one may need to give more permissions to it (just `chmod +x hash_script`). The procedure can be described by the following commands:
```bash
touch hash_script
<your-favourite-text-editor> hash_script
# Write the script in your favourite language
# Give permissions to the script
chmod +x hash_script
AEM_digits=<four-last-digits-of-your-SID>
./hash_script $AEM_digits > hash_output.txt

# Bonus: The git commands I used
git add hash_script hash_output.txt
git commit
# Write the commit message
git push origin main
```

