# ECBM 4060 Final Project
Implementation of P-NET, a biologically informed deep neural network for prostate cancer discovery.

**Project Authors:** Shiv Patil, Bruce Bu, Jong Ha Lee, Rafe Batchelor

The original paper by Elmarakeby et al. can be downloaded [here](https://www.nature.com/articles/s41586-021-03922-4).

Instructions for training and evaluating P-NET:
1. Download Train_Eval.ipynb. This notebook is made to be run locally and uses the bash kernel.
2. Set up bash kernel using pip and a self installer.
  ```
  pip install bash_kernel ; python -m bash_kernel.install
  ```
3. Follow the code comment instructions. After cloning the PNET repository of Elmarakeby et al. into your current directory, download 'environment01.yml' from this repository, extract prostate cancer genomics data from '_databases' file downloaded [here](https://drive.google.com/u/1/uc?export=download&confirm=dUH2&id=17nssbdUylkyQY1ebtxsIw5UzTAd0zxWb), and extract log data from '_logs' file downloaded [here](https://drive.google.com/uc?id=18dJ5fWvJyISROkLRCUMfhsrwZ_iNXSNP&export=download).
4. Place 'environment01.yml', '_database', and '_logs' folders in current directory/pnet_prostate_paper.
5. Poceed with the rest of the code to train the P-NET model with various parameters and evaluate the performance.

Instructions for running AutoML:
1. Download AutoML_Prostate.ipynb. This notebook made to be used in Google Colab.
2. Follow the code comment instructions. After cloning the PNET repository of Elmarakeby et al. into your current directory, download 'environment01.yml' from this repository and extract prostate cancer genomics data from '_databases' file downloaded [here](https://drive.google.com/u/1/uc?export=download&confirm=dUH2&id=17nssbdUylkyQY1ebtxsIw5UzTAd0zxWb).
3. Place 'environment01.yml' into your current directory. Additionally, add '_database' folder to current directory/pnet_prostate_paper.
4. Proceed with the rest of the code to run AutoML.

Note: We found that there were bugs in the environment.yml file downloaded when the PNET repository was cloned. Thus, we wrote environment01.yml as a replacement for this yml file.
