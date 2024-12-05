# Pivot Based Evaluation

Evaluating machine translation (MT) systems for low-resource languages has long been a challenge due to the limited availability of evaluation metrics and resources. As a result, researchers in this space have relied primarily on lexical-based metrics like BLEU, TER, and ChrF, which lack semantic evaluation. In this first-of-its-kind work, we propose a novel pivot-based evaluation framework that addresses these limitations; after translating low-resource language outputs into a related high-resource language, we leverage advanced neural and embedding-based metrics for more meaningful evaluation. Through a series of experiments using five low-resource languages: Assamese, Manipuri, Kannada, Bhojpuri, and Nepali, we demonstrate how this method extends the coverage of both lexical-based and embedding-based metrics, even for languages not directly supported by advanced metrics. Our results show that the differences between direct and pivot-based evaluation scores are minimal, proving that this approach is a viable and effective solution for evaluating translations in endangered and low-resource languages. This work paves the way for more inclusive, accurate, and scalable MT evaluation for underrepresented languages, marking a significant step forward in this under-explored area of research.

FLORES folder has the devtest of FLORES dataset.
entoIL folder contains the translations from English FLORES sentences to low resource IL using IndicTrans2
TILtoIL folder contains the translations from low resources IL to high resource IL
ILtoIL folder has the translations of FLORES low resrouce IL sentences to high resource IL

Paper Link:

#References:
