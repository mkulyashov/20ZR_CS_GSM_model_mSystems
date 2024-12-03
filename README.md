# Context-specific genome-scale metabolic model for 
# _Methylotuvimicrobium alcaliphilum_ 20Z<sup>R</sup>

This gitlab project represents all Supplementary files for the manuscrupt describing the reconstruction of a context-specific metabolic model of the haloalkalophilic aerobic methanotroph _Methylotuvuvimicrobium alcaliphilum_ 20Z<sup>R</sup> developed using algorithms implemented in the Python ([COBRApy](https://opencobra.github.io/cobrapy/), [EscherPy](https://github.com/zakandrewking/escher), [RIPTiDe](https://github.com/mjenior/riptide)), all stages of the model reconstruction using original transcriptomics data.

All files for context-specific (CS) modeling are presented at [BioUML](https://ict.biouml.org/) server, where an user can run Jupyter Notebooks with employed in the article's code for model modifications and reconstruction of CS models for different growth conditions. Here is a [link](https://sirius-web.org/bioumlweb/#de=data/Collaboration%20(git)/20ZR_CS_GSM_model/Data/CS_GSM_model) to the folder with those Jupyter Notebooks.

**Below is the instruction to modify the original iIA409 model according to the description in the maintext:**


**1.**  download the model `fbc_iIA409_20Z.xml` from [gitlab](https://gitlab.sirius-web.org/RSF/20ZR_CS_GSM_model/-/blob/master/Data/CS_GSM_model/file_collection.files/fbc_iIA409_20Z.xml);

**2.** login at BioUML and go to [Jupyter hub](https://sirius-web.org/jupyter/). It is your file system on the server, where BioUML is accessing under your login;

**3.** create folder with name `20Z` and then upload to there your model;

**4.** upload to the same folder Escher (json) map for 20Z from [here](
https://gitlab.sirius-web.org/RSF/20ZR_CS_GSM_model/-/tree/master/Data/CS_GSM_model/file_collection.files/Escher_json_maps). Only after uploading the initial model and map you can run Jupyter Notebook for the model modifications;

**5.** use Jupyter Notebook [model_modification](https://sirius-web.org/bioumlweb/#de=data/Collaboration%20(git)/20ZR_CS_GSM_model/Data/CS_GSM_model/model_modification.ipynb);


To reconstruct CS models and differential reaction flux (DRF) analysis, you needs to run `20Z_transcript` [Jupyter Notebook](https://sirius-web.org/bioumlweb/#de=data/Collaboration%20(git)/20ZR_CS_GSM_model/Data/CS_GSM_model/20Z_transcript.ipynb). All trancriptomics data which were used for the analysis and described reconstruction will be downloaded automatically. 


