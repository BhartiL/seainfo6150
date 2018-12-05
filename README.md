# INFO6150
Class Syllabus: https://docs.google.com/document/d/16Hy7E2KatczXEOLyoD9mkvXPskL3-3vD1f4jLBxXppo/edit?usp=sharing

Class notes:

* Week 1: Overview of web, HTML and CSS: https://drive.google.com/open?id=183GyHTHopPpp8_eapuzyDj5hvTFOKwdMxZlinZ_Q9a0
* Week 2: HTML, part 1: https://drive.google.com/open?id=1kg9Vdc4yLpA5fJMJ5sHcriZ1J7HuqQSIRBz3UpOrB1c
* Week 3: HTML, part 2: https://drive.google.com/open?id=1OUOAsgpek7-4xVTdcidWQ4I8tticJJaUBRb24T7JIBw
* Week 4: CSS, part 1: https://drive.google.com/open?id=1a2Nnvs4dnRQ-_1mR_mMCzRJJwkLgimKh5OkqxcjMNPE
* Week 5: CSS, part 2: https://drive.google.com/open?id=1DDuwy6L9xuBG4kpLDK8F-L2XZqsVkhcRKjRvSbNNCRI
* Week 7: Responsive layouts: https://docs.google.com/document/d/1qYERTKMIPTlHJ7yKko3ylIsRpXwdpbRZUmAPtw2xkF0/edit?usp=sharing
* Week 8: HTML and CSS for web apps:
https://docs.google.com/document/d/1WzM3DMNr09TBIymz66hbvgkX4d53_yQ2LIiufhaBmYg/edit?usp=sharing
* Week 8: Git repo for example react web app
https://github.com/aprilbingham-neu/seainfo6150-webapp
* Week 10: DOM
https://docs.google.com/document/d/1KGx6I1CJCUdzpUMnMXhZzyrS5ynLTTNogys2H_jMtis/edit?usp=sharing
* Week 12: Usability and accessibility
https://docs.google.com/document/d/1dWuZNRGW0AsSa84-BbVyNtxGA7CaehF_qrnbsm6gX40/edit?usp=sharing

Repository of notes and in-class practice files.

# Forking class repo and setting upstream remote
1. Install git: https://git-scm.com/downloads
2. Go to the git repo for this class: https://github.com/aprilbingham-neu/seainfo6150
3. Click “Fork” to create your copy of the repo
4. Click “Clone or download” to get a link to copy your fork on your computer
5. Click “Use HTTPS”
6. Copy link
7. Open command line and use these commands
```
git clone [copied link]
cd seainfo6150
git remote add upstream https://github.com/aprilbingham-neu/seainfo6150
```

# Pushing your changes to your fork
1. Make changes in your fork
2. Open command line and use these commands
```
cd seainfo6150
git add .
git commit -m “[commit name]”
git push origin master
```

# Pulling updates from main repo
```
cd seainfo6150
git pull upstream master
```
