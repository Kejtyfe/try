# These are my notes for Bioinformatics as a beginner to a beginner

I am learning Bash and Ubuntu to be able to analyse sequencing data.
I am much beginner and I want to be eventually helpful for another beginner who cannot seek professional help except the one the internet.
There are plenty of amazing pipelines and forums.
I want to share my day-to-day struggle and my beginner's approach to the subject.

## So, first step when I received my first FASTQ file

Open Bash
What is Bash?
First, let's start with what SHELL is.
It is a program in your PC which provides direct access to the system. 
It helps with almost all our mind's desires under the right "commander". 
Nevertheless, for us, it is great for repetitive commands and combining tasks into workflows.

Bash is a very popular and friendly shell.
I work on Windows, so I work with Windows Subsystem for Linux (WSL) - [Ubuntu](https://ubuntu.com/desktop/wsl).

Ubuntu runs the real Linux environment on Windows. It is possible to download it from the Windows Store.

Or you can download it directly with the PowerSHELL (for Windows)
Run the PowerSHELL as an administrator (right click and then select run as administrator)

```bash
wsl --install # we need to install the WSL system
curl.exe -L -o Ubuntu.appx https://aka.ms/wslubuntu2204
```

We will create a folder for Ubuntu
```bash
Rename-Item Ubuntu.appx Ubuntu.zip
Expand-Archive Ubuntu.zip Ubuntu
```
Now  we install Ubuntu and register it with WSL - create a username and a password
```bash
cd Ubuntu
.\ubuntu2204.exe
```


