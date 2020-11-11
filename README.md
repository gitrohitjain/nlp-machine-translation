# Seq2seq machine translation

Input language : German
Output language: English

Database used for training: Multi30k from torchtext.datasets 

Eg:-
German (input sentence) : ein boot mit mehreren männern darauf wird von einem großen pferdegespann ans ufer gezogen.

After training for 100 epochs,

Translated Sentence (english): a boat carrying several men is pulled to shore by a large team of horses.

----------
Google translation: a boat with several men on it is being pulled ashore by a large team of horses.
Microsoft translation: a boat with several men on it is pulled by a large horse team to the shore.

Training loss after 100 epochs: 0.25
validation loss after 100 epochs: 6.98
Bleu score: 19.52
