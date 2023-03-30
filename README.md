## EMSFold
The scientific research to better understand the full potential and functions of proteins lies within the protein's structure. [EMSFold](https://esmatlas.com/about) is a great biological tool developed to predict protein structure based on the ESM-2 language model. The focus on this project is to build an algorithm to predict an end-end single sequence protein structure. This project is motivated by [Osanseviero](https://huggingface.co/spaces/osanseviero/esmfold).

<video controls autoplay src="images/protein_structure.mov" width="500"></video>

## Predictor App
Visit [streamlit app](https://ainard09-protein-structure-predictor-app-streamlit-app-2t6zeq.streamlit.app/) and make protein sequence prediction.
## Evaluation
The evaluation metric used to monitor the performance of the model is **predicted local distance difference test** (pLDDT). The predicted structures contain atomic coordinates and per-residue confidence estimates on a scale from 0 to 100, with higher scores corresponding to higher confidence. This confidence measure corresponds to the model's predicted per-residue scores on the **IDDT-Cα metric**.
## Acknowledgement
Thanks to [Data Professor](https://github.com/dataprofessor) for the support.
