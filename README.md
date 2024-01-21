# ContrastWSD

ContrastWSD, a RoBERTa-based metaphor detection model that integrates the Metaphor Identification Procedure (MIP) and Word Sense Disambiguation (WSD) to extract and contrast the contextual meaning with the basic meaning of a word to determine whether it is used metaphorically in a sentence. By utilizing the word senses derived from a WSD model, our model enhances the metaphor detection process and outperforms other methods that rely solely on contextual embeddings or integrate only the basic definitions and other external knowledge. We evaluate our approach on various benchmark datasets and compare it with strong baselines, indicating the effectiveness in advancing metaphor detection.

The source code is based on MelBERT source code (https://github.com/jin530/MelBERT) and extended to add the ContrastWSD model and evaluation.
