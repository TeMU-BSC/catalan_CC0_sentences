# catalan_CC0_sentences
collected CC0 sentences written in Catalan

## Contents
* selected_club: 22714 sentences from <a href="https://huggingface.co/bsc">our own</a> corpora and datasets, published here under CC0 licence.
* literatura: 355 literature sentences, published <a href="https://cultura.gencat.cat/ca/ilc/que-fem/publicacions/postals-literaries/">here</a>.
* oscar_2000000: 92960 sentences selected from the first 2000000 of the corpus Oscar.
* plantilles_intents: 2663 intent-like sentences, generated by templates, published here for the first time.
* directory samples/: contains 1 out 25 (about 4%) sentences of each corpus
* openAI_generated_phrases.txt (experimental): Added 13846 unique phrases by prompting generative GPT-3 models (curie & davinci) from OpenAI with some of the original phrases, and retrieving the ones vetted by a lang identification library. Some English ones go through the filter, and others not factually true but in catalan, are generated. But most seem grammatical and idiomatic catalan.
* openai_davinci_dialogue_from_spl.txt: 1994 phrases obtained from the davinci model under a conversational/dialogic framework, using as prompts 1000 phrases from the Politica Lingüístca corpus (spl.txt), but filtering them using the java filtercorpus developed by members of SoftCatala. We have added some of the rejected strings (rejected_from_openai.txt) for further exploitation.
