This part will show you the basic commands in BASH

# Bash Basics — Mini Quiz

**Q1.** Which command shows your current folder?  
- [ ] `ls`
- [ ] `cd`
- [x] `pwd`

<details><summary>Show answer</summary>
`pwd`
</details>

**Q2.** How do you list files with sizes?  
- [x] `ls -lh`
- [ ] `cat -n`
- [ ] `du -a`

<details><summary>Show answer</summary>
`ls -lh`
</details>

**Q3.** View first 4 lines of a compressed FASTQ (`.fastq.gz`)?  
- [ ] `head -n 4 file.fastq.gz`
- [x] `zcat file.fastq.gz | head -n 4`
- [ ] `less file.fastq.gz`

<details><summary>Show answer</summary>
`zcat file.fastq.gz | head -n 4`
</details>

**Q4.** Count reads in a FASTQ file?  
- [x] `zcat file.fastq.gz | wc -l | awk '{print $1/4}'`
- [ ] `wc -l file.fastq.gz`
- [ ] `cat file.fastq.gz | grep -c '@'`

<details><summary>Show answer</summary>
`zcat ... | wc -l | awk '{print $1/4}'`
</details>

**Q5.** Make a folder named `results`  
- [ ] `newdir results`
- [x] `mkdir results`
- [ ] `touch results`

<details><summary>Show answer</summary>
`mkdir results`
</details>





[⬅️ Back to Home](README.md)
