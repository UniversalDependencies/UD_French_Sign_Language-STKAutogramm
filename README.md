# Summary

A Universal Dependencies corpus for French Sign Language (Langue des Signes Française, LSF), a sign language used in France.

# Introduction

This treebank is an automatic conversation of the SUD_French_Sign_Language-STKAutogramm, annotating diverse genre of videos gathered from different corpora. 

Sentences are annotated with the following metadata: 
 - `sent_id`: unique identifier for a sentence
 - `text`: lexical tokenisation
 - `source_file`: the video file corresponding to the sample
 - `text_fr`: a free translation in French
 - `text_en`: a free translation in English
 - `document_id`: the name of the sample
 - in certain samples, `speaker_id` if multiple signers are present


## Structure

The data comes from 3 different pre-existing projects. 
 - One sample (**STK_vacances-sud**) from the ANR project SignToKids, conducted at Paris Nanterre University. This video is a semi-spontaneous narration of a story. It was recorded with the intention of eliciting different types of plural forms. We realized the translation and glossing of this sample.
 - Two samples (**LS-Colin_champignon** and **LS-Colin_cheval**) from the corpus **LS-Colin**. This corpus was recorded in 2002 and contains different signers' participation, realizing different tasks.
   - **LS-Colin_champignon** is the recording of a recipe. The prompt for the signer was to present her favorite recipe. The extract used has the following time code: 18:17 to 19:46, from the video CUC022_low of a total length of 36:43.
   - **LS-Colin_cheval** is the recording of a short narration. The prompt was to retell the story presented in 5 images, about a horse jumping a fence, accompanied by a cow and a bird. The extract used has the following time code: 00:06 to 01:07, from the same video. 
 - Two samples (**Alpha_entretien_etudiant_souvenir** and **Alpha_entretien_etudiant_trajet**) from the corpus **ALPHA SOURDS**. In this corpus, we find interviews between the researchers and different deaf students. 
   - **Alpha_entretien_etudiant_souvenir** is the recording of a narration, with a few interactional elements. The prompt was for the student to tell her best memory.
   - **Alpha_entretien_etudiant_trajet** is the recording of a description, with more interactional elements. The prompt was for the student to describe a common route he was taking daily.


## References

### STK
 - Cuxac, Christian, & Boutet, Dominique. (2015). Corpus LS-Colin sur plusieurs genres discursifs (Laurent Vallo, Nasredine Chab et Anthony Guyon). COCOON - https://cocoon.huma-num.fr (Huma-Num - CNRS). https://doi.org/10.34847/COCOON.6D4B96B9-83C2-38B4-8FD6-ACB62E57DE4D

 - Corpus ALPHA SOURDS. ORTOLANG (Open Resources and TOols for LANGuage) - www.ortolang.fr, https://doi.org/10.82270/corpus-alpha-sourds   

# Changelog

* 2026-11-15 v2.19
  * Initial release in Universal Dependencies.


<pre>
=== Machine-readable metadata (DO NOT REMOVE!) ================================
Data available since: UD v2.19
License: CC BY-SA 4.0
Includes text: yes
Parallel: no
Genre: spoken
Lemmas: manual native
UPOS: manual native
XPOS: not available
Features: manual native
Relations: converted from manual
Contributors: Kahane, Sylvain; Herrera, Santiago; Périn, Philomène; Bogliotti, Caroline; Guillaume, Lou
Contributing: elsewhere
Contact: skahane@parisnanterre.fr
===============================================================================
</pre>
