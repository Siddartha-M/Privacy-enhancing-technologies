# Privacy-enhancing-technologies

This project is done as part of the Global enigneering concepts course. In this project, Different state-of-the-art privacy enhancing technologies are used for evaluation of their efficacy. This project also partly had inspiration from PET Lab hackathon conducted from Nov 8th - 11th 2022 by UN PET lab which is part of UN Big data team.  

Input dataset is the refugee information collected by UN Refugee agency https://microdata.unhcr.org/index.php/catalog/296/study-description, As this data is sensitive it was a good case to test the efficacy of the PET tools.  

In the Notebooks folder, the code required to recreate experiments are available.  
The data folder has the data used in the experiments.

As part of this project we have explored use of AWS Nitro which is a secure enclave that could perform computations in an encrypted fashion.  
Smart Noise SQL and Smart Noise Synth which are packages that could be used to query lot of databases like SQL, Postgres and Pandas and can be used to generate synthetic data for categorical and continuous data using different methods is used.  
Diffprivlib, IBM's package which is useful to train differentially private models. It is as easy as using sci-kit learn is also used.

Our experiments show that after using the tools, the results obtained are close to the results that one could have obtained if they have access to original data which seconds their ability to use to learn remotely from sensitive data.
