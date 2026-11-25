# Q4.6 Portfolio Presentation Script

**Presenter:** Priyanshu Yadav  
**Programme:** B.Tech Computer Science and Engineering, K.R. Mangalam University  
**Specialisation interest:** Cybersecurity  
**Target duration:** 8–10 minutes. Replace the roll number and section prompts before presenting; rehearse with a timer.

> Only describe results you have actually completed. Do not claim certificates, solved-problem counts, a shell-script demo, or practice sessions unless you have done them.

## 0:00–1:00 — Introduction

Good morning/afternoon. I’m Priyanshu Yadav, a B.Tech Computer Science and Engineering student at K.R. Mangalam University, Gurugram. My roll number is **[add your roll number]**, and I’m in **[add your section]**. I’m interested in cybersecurity, especially how operating systems, networks, and secure software work. Today I’ll show the GitHub and API work I completed for CSE103, how I organised it, and the learning plan I’m following.

## 1:00–3:00 — Profiles and skills

Open the [GitHub profile](https://github.com/v1olation). My profile README summarises my course, current interests, skills, and project link. I’m still developing these skills, so I describe Python as beginner level and the other tools as coursework practice rather than advanced expertise.

Briefly open the [LinkedIn profile](https://www.linkedin.com/in/priyanshu-yadav-597823431/) and point out the headline, education, and CSE103 project. I have not attempted the HackerRank Python Basic certification yet, so I have no certificate to show. I will add it here only after earning it.

## 3:00–6:00 — Project demonstration

### GitHub repository (about 90 seconds)

Open [cse103-lab-LAB3](https://github.com/v1olation/cse103-lab-LAB3). The README explains the coursework. The `src/`, `tests/`, and `docs/` folders separate the program, a test placeholder, and setup notes. The repository also contains API response data and the Markdown guide.

In PowerShell, navigate to the local repository and run `git log --oneline --graph --all`. Explain: “This graph shows how the commits record the work over time, including the feature branch and the resolved merge conflict. The commit messages describe changes such as features, fixes, documentation, and repository maintenance.”

### API interaction (about 60 seconds)

Run `curl.exe https://api.github.com/users/v1olation` and, if jq is available, pipe it to `jq '.name, .public_repos'`. Explain: “curl makes an HTTP GET request. The API returns JSON, and jq selects the fields I want to inspect.” The observed public repository count may change, so read the value shown at presentation time.

### Shell scripting demonstration (about 60–90 seconds)

The assignment suggests running a LAB 2 script called `script6_sysreport.sh`. Use this demo only if that script exists and works in your actual LAB 2 folder. Before presenting, test it there and prepare the correct command. If you do not have it, say: “I don’t have that LAB 2 script available to demonstrate, so I’ll show my Git/API workflow instead.” Do not present a made-up script as completed work.

## 6:00–8:00 — Roadmap and goals

Open [`LEARNING_ROADMAP.md`](https://github.com/v1olation/developer-portfolio/blob/main/LEARNING_ROADMAP.md). My plan starts with Python, Linux, Git, and core computer science, then adds databases and networking before moving toward cybersecurity. One project idea is LogLens, a local dashboard that analyses synthetic or public sample authentication logs and highlights repeated failed logins. It is a future plan, not a completed project.

Open [`PROGRESS.md`](https://github.com/v1olation/developer-portfolio/blob/main/PROGRESS.md). It records completed coursework and work that is still pending. I have not started the listed HackerRank, LeetCode, or freeCodeCamp practice yet.

A concept I found challenging was a Git merge conflict. I learned to inspect the conflict markers, keep the intended lines, remove the markers, stage the resolved file, and commit the merge. The resulting history shows both branches and the merge commit.

## 8:00–9:00 — Portfolio website

Open the live GitHub Pages site at **[add the published URL after Pages is enabled]**. Show the About section, project cards, skills table, learning status, roadmap, and contact links. I built the page with HTML and CSS and published it using GitHub Pages.

## 9:00–10:00 — Conclusion and questions

The most challenging part of this lab was **[choose a truthful challenge]**, because **[brief reason]**. I worked through it by breaking the task into smaller steps and checking Git’s output at each stage. My next goal is to begin the coding-platform practice and build a small cybersecurity project after strengthening my fundamentals. Thank you. I’m happy to take questions.

If you do not know an answer, say: “I haven’t covered that yet, but it is on my learning roadmap.”

## Before presenting

- Fill in roll number and section.
- Replace the Pages URL after deployment.
- Confirm the LAB 2 script exists before using that demo; otherwise use the honest fallback above.
- Open GitHub profile, lab repository, portfolio repository, live site, and LinkedIn tabs.
- Rehearse the full talk twice with a timer and once for a classmate if available. Record the actual practice dates and times in your lab record; do not mark practice complete until done.
