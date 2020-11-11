# Intrinsic Correlation Test
Begin test with following command:
	python3 IntrinsicScript.py

Testset and models are hardcoded into the script, see code for more details;

---

# Selective NER Test
The tool used to make the NER models can be found bellow: 
	<https://github.com/jneto04/ner-pt>

After cloning th repository and installing Flair 0.4.1 (Must be exactly this version), substitute the 'ner_flair.py' with the one found in the 'Selective NER Test' ZIP;

To begin the test, use the following command:
	
	python3 ner_flair.py [TRAIN DATASET] [TEST DATASET] [VAL DATASET] [WE MODEL] ['false' if WE model is a .model, 'true' if the WE model is a .txt] ['ft' if model is FastText, 'wv' if model is Word2Vec]

Example:
	
	python3 ner_flair.py train_0_bio.txt test_0_bio.txt val_0_bio.txt Publico-Hibrido\(Completo+NILC\).txt-FastText.model false ft

Command must be repeated for each cross-section.
