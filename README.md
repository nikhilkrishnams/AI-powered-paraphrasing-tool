# AI-powered-paraphrasing-tool


 I created a simple AI-powered paraphrasing tool using Python and a T5 transformer model

The tool takes text from the user and tries to rewrite it using different words while keeping the original meaning.

I also included grammar checking, spelling correction, and evaluation methods to check the generated text.

1. The user enters a sentence or paragraph.
2. The T5 model generates possible paraphrases.
3. The program selects an output based on meaning similarity.
4. LanguageTool checks grammar and spelling.
5. The program calculates similarity, wording difference, and readability scores.

Evaluation Results

I tested the model using five sample sentences.


Evaluation Results:
Meaning Similarity (%) : 99.87
Wording Difference (%) : 0.26
Grammar Errors Before : 1
Grammar Errors After : 0
Readability Score : 34.64

The meaning preservation pass rate is based on a 75% similarity threshold. It does not represent the model's overall accuracy.


Limitations

The model does not always change the original sentence. Sometimes it also changes the meaning of certain words.

I noticed that technical sentences were more difficult to paraphrase correctly. I added a basic check to protect some important technical terms.

The evaluation scores are useful, but they cannot guarantee that every generated sentence is correct.

