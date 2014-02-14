buzzquiz
========

'Buzzfeed style' quiz (Disclaimer: I do not nor have I ever represented buzzfeed, this is simply a genre description)

Currently under development. I need to add more detail to how to use this, but you can find a working example @ http://www.cidercraft.com/flavor_profile and all of the necessary working code in this github. If you have any background in js this shouldn't be too hard to follow, but please don't hesitate to reach out to me @ freiberg.brandon@gmail.com for further info :). Happy quizzing.

This quiz will represent the "What _____ are you?" buzz style quizzes inundating the world courtesy of buzzfeed. 
There are no 'correct' or 'incorrect' answers, rather each answer adds to the previous to create a weighted
answer.

The way these answers are represented in the quiz is through a number system. There are n^m results, where
n = number of answer options for each question
m = number of questions

Thus if you have a 5 question quiz with 2 answers ('Do you prefer milk or dark chocolate?'), you have 2^5=32 results.
Results are represented by number strings, as such:
00000
00001
00010...
...
11111

I hope you enjoy :)
