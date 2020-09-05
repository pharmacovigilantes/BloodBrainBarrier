# Blood Brain Barrier Project
The repo has the example codes that were used for the working paper titled "Predicting Drug Blood-Brain Barrier Penetration with Adverse Event Report Embeddings"<br>

##dataset
Semantic vectors derived from FDA Adverse Event Reports(AERs) with three different configurations. <br>
Will upload later <br>

## Usage
**Calculate_Tanimoto_Scores.ipynb** calculates the Tanimoto scores using offside data downloaded from: <http://tatonettilab.org/offsides><br>
<br>
**CrossTraining_TrainGao_TestMartin.ipynb** crosstraining configuration described in the paper. Trained on Gao et al reference set(n=208) and tested on Martin et al reference set(n=188).<br>
<br>
**Github_5CV_model_AUCROC_08282020.ipynb** train and test within the two reference sets with 5-fold cross validation. 
