# catalan_CC0_sentences
collected CC0 sentences written in Catalan

## Contents
* cgc_a*_frases_seleccionades_filtrades.txt:  25887 sentences selected from the <a href="https://zenodo.org/record/5500233#.YUSvh3uxXOt">Catalan Government Crawling</a>
* frases_spl.txt: 1711 sentences created by <a href="https://llengua.gencat.cat/ca/direccio_general_politica_linguistica/">Secretaria de política lingüística</a> for this project, published here for the first time.
* generades_spl_seleccionades.txt: 4469 new sentences, generated from frases_spl semi-authomaticaly by masking with <a href="https://huggingface.co/bsc/roberta-base-ca-cased">bsc/roberta-base-ca-cased</a>
* literatura.txt: 357 literature sentences, published <a href="https://cultura.gencat.cat/ca/ilc/que-fem/publicacions/postals-literaries/">here</a>, edited.
* openai_davinci_dialogue_from_spl.txt: 1994 phrases obtained from the davinci model under a conversational/dialogic framework, using as prompts 1000 phrases from the Politica Lingüístca corpus (spl.txt), but filtering them using the java filtercorpus developed by members of SoftCatala. We have added some of the rejected strings (rejected_from_openai.txt) for further exploitation. [experimental]
* openAI_generated_phrases.txt (experimental): Added 13846 unique phrases by prompting generative GPT-3 models (curie & davinci) from OpenAI with some of the original phrases, and retrieving the ones vetted by a lang identification library. Some English ones go through the filter, and others not factually true but in catalan, are generated. But most seem grammatical and idiomatic catalan. [experimental]
* oscar_3000000_seleccionades_filtrades.txt: 122424 sentences selected from the first 3000000 of the corpus Oscar.
* plantilles_intents.txt: 2664 intent-like sentences, generated by templates for this project, published here for the first time.
* selected_club.txt: 21237 sentences from <a href="https://huggingface.co/bsc">our own</a> corpora and datasets, published here under CC0 licence.

* directory samples/: contains 1 out 25 (about 4%) sentences of each corpus
