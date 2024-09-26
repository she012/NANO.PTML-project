# NANO.PTML-project

*NANO.PTML Model for read-across prediction of nanosystems in neurosciences*

Shan He1,2,3, Karam Nader2, Julen Segura Abarrategi2, Harbil Bediaga3, Deyani Nocedo-Mena,4 
Estefania Ascencio1,2,3 , Gerardo M. Casanola-Martin1, Idoia Castellanos-Rubio2*, 
Maite Insausti2,5, Bakhtiyor Rasulev1, Sonia Arrasate2*, and Humberto González-Díaz2,6,7

1 Department of Coatings and Polymeric Materials, North Dakota State University, Fargo, ND 58108, USA.
2Department of Organic and Inorganic Chemistry, University of Basque Country UPV/EHU, 48940 Leioa, Spain.
3IKERDATA S.L., ZITEK, UPV/EHU, Rectorate Building, nº 6, 48940 Leioa, Greater Bilbao, Basque Country, Spain.
4Faculty of Physical Mathematical Sciences, Autonomous University of Nuevo León, San Nicolás de los Garza, Nuevo León 66455, México
5BCMaterials, Basque Center for Materials, Applications and Nanostructures, 48940 Leioa, Spain. 
6 BIOFISIKA: Basque Center for Biophysics CSIC, University of The Basque Country (UPV/EHU), Barrio Sarriena s/n, Leioa, Bizkaia 48940, Basque Country, Spain.
7IKERBASQUE, Basque Foundation for Science, 48011 Bilbao, Biscay, Spain.


# Abstract.

Neurodegenerative diseases are characterized by slowly progressive neuronal death. Conventional treatment strategies often fail due to poor solubility, lower bioavailability, and the inability to effectively cross the Blood–Brain Barrier (BBB). Therefore, the development of new Neurodegenerative Disease Drugs (NDDs) requires immediate attention. Nanoparticle (NP) systems are increasingly of interest for transporting NDDs to the central nervous system. However, discovering effective Nanoparticle Neuronal Disease Drug Delivery Systems (N2D3S) is challenging due to the vast number of NP and NDDS compound combinations, as well as various assays involved. Artificial Intelligence/Machine Learning (AI/ML) algorithms have the potential to accelerate this process by predicting the most promising NDDS and NP candidates for assay. Nevertheless, the relatively limited amount of reported data on N2D3S activity compared to assayed NDDs makes AI/ML analysis challenging. In this work, the IFPTML technique, which combines Information Fusion (IF), Perturbation Theory (PT), and Machine Learning (ML), was employed to address this challenge. Initially, we conducted fusion into a unified dataset comprising 4403 NDDS assays from ChEMBL and 260 cytotoxicity NP assays from journal articles. Through a resampling process, three new working datasets were generated, each containing 500,000 cases. We utilized Linear Discriminant Analysis (LDA) along with Artificial Neural Networks (ANN) algorithms like Multi-Layer Perceptron (MLP) and Deep Learning Networks (DLN) to construct linear and non-linear IFPTML models, respectively. The IFPTML-LDA models exhibited Sensitivity (Sn) and Specificity (Sp) values in the range of 70% to 73% (>375K training cases) and 70% to 80% (>125K validation cases), respectively. Conversely, the IFPTML-MLP and IFPTML-DLN achieved Sn and Sp values in the range of 85% to 86% for both training and validation series. Additionally, IFPTML-ANN models showed an Area Under the Receiver Operating Curve (AUROC) of approximately 0.93 to 0.95. These results indicate that the IFPTML models could serve as valuable tools in the design of drug delivery systems for neurosciences. 

*Corresponding author: E-mail: humberto.gonzalezdiaz@ehu.es (HGD)
