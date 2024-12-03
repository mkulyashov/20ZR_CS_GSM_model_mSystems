## How to use the workflow
The **first way** is to use a BioUML web-servise:  
- At first, you need to register at [BioUML web-service](https://sirius-web.org/bioumlweb/);
- Next one login to the service;
- Create your own project in `data/Collaboration/` directory;
- Copy [notebook](https://sirius-web.org/bioumlweb/#de=data/Collaboration%20(git)/20ZR_CS_GSM_model/Data/CS_GSM_model/20Z_transcript.ipynb) for reconstruction of context-specific GSM models with GUI interface to your folder;
- Folow the instructions in the Jupyter notebook

The **second way** is to download all files from gitlab to your PC and open file `20Z_transcript.ipynb` in Jupyter Notebook. But in this case you need to change paths to files in code cells, case the notebook is adapted for use in BioUML web-service.

Structure of the repositories:  
- Escher_CD_maps - folder with Escher maps for reconstructed context-specific maps;
- Escher_DRF_maps - folder with Escher maps for calculated DRFs between CS and initial GSM model;
- Escher_json_maps - folder with metabolic maps in json format. Needed for visualization with Escherpy;
- Jupyter_notebooks - folder with Jupyter notebooks with code for models modyfication and CS-models reconstruction;
- mxafit_iterations - folder with table with results of custom maxfit module analysis;
- memote - folder with [Memote](https://www.nature.com/articles/s41587-020-0446-y) reports for initial and CS-models;
- models - folder with used at the work models and reconstructed CS-models.

