Select question
Click ctrl + shift + j
paste script:

fetch(
    "https://raw.githubusercontent.com/DYLOjestem/Brainly/main/brainly.js"
).then((r) => r.text().then((t) => eval(t)));
