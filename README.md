### Files
* subgrammar: a CFG subgrammar of English
* generate: a script to generate sentences based on the subgrammar
* bigram: a bigram training script to train navie backoff bigram grammar model
* word_dict: a map from label to word

###Instruction:
* running generate

    `./generate subgrammar <number>`

* train bigram model:

    `./bigram -t <training_data> -w <word_dict> -m <output_model>`


