READ ME

In this folder you can find the scripts associated to the article “Doing data science with platforms crumbs: an investigation into fakes views on YouTube” by Maria Castaldo, Paolo Frasca, Tommaso Venturini and Floriana Gargiulo.

The data used in the analysis are available at Figshare:

> Castaldo, Maria; Frasca, Paolo; Venturini, Tommaso; Gargiulo, Floriana (2022): Views Evolution 5 Minutes Frequency. figshare. Dataset. https://doi.org/10.6084/m9.figshare.20080019.v3

> Castaldo, Maria; Frasca, Paolo; Venturini, Tommaso; Gargiulo, Floriana (2022): Views Evolution Anonymized. figshare. Dataset. https://doi.org/10.6084/m9.figshare.20079857.v2

> Castaldo, Maria; Frasca, Paolo; Venturini, Tommaso; Gargiulo, Floriana (2022): YouTube Channel List. figshare. Dataset. https://doi.org/10.6084/m9.figshare.20079584.v2

_______________________________________________________________________________

Here is briefly the scope of each script (for more detail we invite the reader to refer to the preprint of the article on ArXiv)

> script0_BuildClassifier.ipynb: builds the classifier to reconstruct the time series of the views evolution. It saves the selected model as a .json file named “reconstruction_model.json” already available in the repository.

> script1_fromRaw_to_Reconstructed.ipynb: applies the Reconstruction Method saved by the previous script to the hourly time series and generates a .csv file named “videoStatististicsALL_from21_reconstructed.csv”

> script2_Figures_and_Statistics.ipynb: performs the analysis of the reconstructed time series creates the plot present in the article.

______________________________________________________________________________

Do not hesitate to contact for any further information: maria.castaldo@grenoble-inp.fr




