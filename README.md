# Residue-detection
This repository is part team Tom Resiude's submission for the festival of hope hackthon. Makes use of a CNN to detect crop residue cover from an image, along with a localhost server using flask as a user interface.  

# About the project


This repository covers the files required to deploy a localhost server providing a user interface for a crop resiude prediction model. The prediction model is built via tensorflow, and makes use of around 60,000 parameters trained and saved to the model.h5 file. The prediction makes use of a convolutional neural network trained on data <a href = "https://doi.org/10.5066/F7930SDB">here</a>, and uses 5 convolutional, 5 max-pool, and 2 fully connected dense layers with a linear activation to then provide a percentage value. Potential limitations may be faced with overfitting and excess augmentation, while the model could have expanded by also making use spectral wave detection data. The project also involved heavy secondary research, with a presentation prepared to spread awareness <a href = "https://www.canva.com/design/DAFZJidBfsI/uRtDGMkel1RH-a8dJwA7PA/view?utm_content=DAFZJidBfsI&utm_campaign=designshare&utm_medium=link&utm_source=homepage_design_menu">here</a>, and information included in the html pages.




