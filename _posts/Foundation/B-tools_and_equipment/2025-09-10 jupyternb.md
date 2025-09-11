---
toc: True
layout: post
data: tools
title: Jupyter Notebooks
description: Learn how to create and run Jupyter Notebooks
categories: ['DevOps']
permalink: /blogs/jupyternb
breadcrumb: True
author: veen456
---

Tools and equipment can be an effective way to implement things into your machines, which you otherwise wouldn’t be able to do.
We used Jupyter Notebooks to display a random joke on our personal sites.
Make sure VS code is working in your machine and set up in your student repository.
You will then need to add these code sections in the notebook.

```
%%javascript

var accounting_joke_list = [
    "Why did the accountant cross the road? To bore the people on the other side.",
    "What do accountants do when they're constipated? They work it out with a pencil.",
    "How does an accountant stay out of debt? He learns to act his wage.",
    "Why did the accountant stare at his glass of orange juice for three hours? Because on the box it said 'concentrate'.",
    "Why did the accountant get promoted? Because he knew how to balance his work and play.",
    "Why did the accountant go broke? Because he lost his balance.",
    "Why did the accountant get a job at the bakery? Because he was good at making dough.",
    "Why did the accountant get a job at the zoo? Because he was good with cheetahs.",
    "Why did the accountant get a job at the library? Because he was good at keeping books.",
    "Why did the accountant get a job at the circus? Because he was good at juggling numbers.",
    "Why did the accountant get a job at the gym? Because he was good at working out the numbers.",
    "Why did the accountant get a job at the farm? Because he was good at counting the chickens before they hatched."
]
var randomIndex = Math.floor(Math.random() * accounting_joke_list.length);
console.log("Joke #" + (randomIndex + 1) + ": " + accounting_joke_list[randomIndex]);
```

```
%%javascript
var compsci_joke_list = [
    { joke: "Why do programmers prefer dark mode? Because light attracts bugs.", complexity: "1" },
    { joke: "Why do Java developers wear glasses? Because they don't see sharp.", complexity: "2" },
    { joke: "How many programmers does it take to change a light bulb? None, that's a hardware problem.", complexity: "1" },
    { joke: "Why do Python programmers prefer snake_case? Because they can't C.", complexity: "2" },
    { joke: "Why was the JavaScript developer sad? Because he didn't know how to 'null' his feelings.", complexity: "3" },
    { joke: "Why do programmers always mix up Christmas and Halloween? Because Oct 31 == Dec 25.", complexity: "3" },
    { joke: "Why did the programmer quit his job? Because he didn't get arrays.", complexity: "O(n)" },
    { joke: "Why do Linux programmers prefer using the terminal? Because they don't like Windows.", complexity: "1" },
];
var randomIndex = Math.floor(Math.random() * compsci_joke_list.length);
var selectedJoke = compsci_joke_list[randomIndex];
console.log("Joke #" + (randomIndex + 1) + ": " + selectedJoke.joke + " (Complexity: " + selectedJoke.complexity + ")");
```

Now you can run the notebook and the jokes will appear in the developer console.
Next, if you want to add your jokes onto your student site, you will need to add this code to your code sections in notebooks.
<IPython.core.display.Javascript object>


Now your jokes will be randomly selected and displayed on your student website.


