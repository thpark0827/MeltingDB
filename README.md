# MeltingDB

Integrating Data Mining and Natural Language Processing to Construct Melting Points Database for Organometallic Compounds

Jinyoung Jeong+, Taehyun Park+, JunHo Song, Seungpyo Kang, Joonghee Won, Jungim Han*, and Kyoungmin Min*

# Installation
### Create your virtual environment (Supported Python 3.5 to Python 3.8)
`conda create -n cde python=3.8`

### Activate your virtual environment
`conda activate cde`

### Install chemdataextractor2 version 2.0.2
`pip install chemdataextractor2==2.0.2`

### Download a variety of data files
`cde data download`

# Usage
1. Article retrieval for the journal "Journal of Organometallic Chemistry"
   : `Downloading JOC Articles.ipynb`
2. Auto-extracting melting point information
   : `Auto Extraction (JOC).ipynb` `Auto Extraction (OMs).ipynb`

# Acknowledgements
This work was supported by a National Research Foundation of Korea (NRF) grant funded by the Korea government (MSIT) (No. 2022R1F1A1074339, No. 2022R1C1C1009387). The work was also supported by Samsung Advanced Institute of Technology.
