Sample prompts for different tasks investigated to use ChatGPT as an automatic evaluator for some NLG tasks.

This work has been published in:

>Riyadh M., Shafiq O., "Towards Automatic Evaluation of NLG Tasks using Conversational Large Language Models" Proceedings of the 4th IFIP International Conference on Artificial Intelligence Applications and Innovations (AIAI 2023) 4. Springer US, 2023.

Please cite this paper if you leverage these prompt formats in your work.

---

## ChatGPT prompts for NLG tasks:

## Story-cloze test	
Consider the following sentences from a short story: 

`Betsy was about to celebrate her sixteenth birthday. Her parents surprised her with a nice dinner out and a small present. Happily, her parents gave her a monogram necklace. On the way home, Betsy misplaced the necklace in the car.`

Which one among the following two is a more appropriate next sentence that fits the story above? 

```
1. Betsy felt really bad for the rest of the night. 
2. Betsy wore the monogrammed necklace when she turned 14. 
```

Answer using only numbers 1 or 2. Do not write any other additional notes or explain your answer.

## Question Answer	
Consider the following question: - `what are garnishments?` 

Is the following a correct answer to the above question? 

- `A garnishment is a means of collecting a monetary judgment against a defendant by ordering a third party (the garnishee) to pay money, otherwise owed to the defendant, directly to the plaintiff. `

Answer with Yes or No. Do not write any additional notes.

## Paraphrasing	
Consider this statement: 

`How do I start up a new cafe? `

Is the following a correct paraphrasing of the above statement? 

- `What are requirements I would need to start my own cafe? `

Answer with Yes or No. Do not write any additional notes.

## ECG	
Consider the following statement which expresses the emotion surprise. The cause of this emotion is missing which is denoted by '_': 

`Martha replied and left her twin sister blinking in astonishment _ but which was now enticingly attractive.`

Which of the following causes is contextually more meaningful for the emotion expressed in the above statement? Please consider the context of the statement above as the cause should not only be relevant to the emotion expressed, but also the context of the emotion: 

```
A. at a possibility that had not occurred to her before 
B. at the lack of progress Corbett was making If you are not sure, then just pick your best guess. 
```

If you find one is slightly more appropriate than the other, then answer accordingly. Do not write any additional notes. Answer with letter: A or B. No need to explain your answer or rewrite the cause.

## ECSGen	
Consider this statement: 

`I feel bored because I have been here for so long.`

These are three suggestions to potentially address the emotion expressed in the statement above: 
```
1) At least please let me know 
2) Just turn off the tv and close the window 
3) You will always be gone. 
```

Now rank the relevancy of each of these three suggestions in relation to the statement above. Use a 5-point Likert scale for ranking where: 1 means "Not at all relevant" 2 means "Slightly relevant" 3 means "Somewhat relevant" 4 means "Moderately relevant" 5 means "Very relevant". 

Put your ranking in an array in the same order as the suggestion above. Don't write any additional notes.
