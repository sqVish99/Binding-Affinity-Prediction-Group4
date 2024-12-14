# **Binding-Affinity-Prediction-Group4**

## **Overview**
This repository contains two implementations of a TCR-epitope binding prediction model:  
1. **ATM-TCR** (Base and Enhanced Versions)  
2. **catELMo**  

The models are designed for predicting TCR-epitope binding affinity. Pretrained model weights are stored on OneDrive (links provided below).

-----------------------------------------
# Team Members:
1. Rakesh Mallu
2. Parampally Vaishnavi Upadhya
3. Vishwas Mattur Harish
4. Brooke Bolsinger
5. Pradhi Tammannavar
----------------------------------------

![alt text](https://github.com/sqVish99/Binding-Affinity-Prediction-Group4/blob/main/Picture.png?raw=true)

OneDrive Link: 
ATM-TCR: https://arizonastateu-my.sharepoint.com/:f:/g/personal/vmharish_sundevils_asu_edu/EjSdTYBFgNpHre5BHp7KACwB2v1s62Q04URRjbM0gU9wCw?e=yK3dcu
catELMo: https://arizonastateu-my.sharepoint.com/:f:/g/personal/vmharish_sundevils_asu_edu/ErxdLkQETCtPqp_9jaM3LeABPWda2nLKWWmg1JmF8OjECA?e=zoyX4G

## **Repository Structure**

```plaintext
Binding-Affinity-Prediction-Group4/
│
├── ATM-TCR/
│   ├── Base/
│   │   ├── model_code.py          # Code for the base model
│   │   ├── tcr_split_weights.pt   # Model weights (TCR split)
│   │   ├── epi_split_weights.pt   # Model weights (Epitope split)
│   │   ├── test_labels_tcr.csv    # Test labels for TCR split
│   │   └── test_labels_epi.csv    # Test labels for Epitope split
│   │
│   ├── Model/
│       ├── model_code.py          # Code for the enhanced model
│       ├── tcr_split_weights.pt   # Model weights (TCR split)
│       ├── epi_split_weights.pt   # Model weights (Epitope split)
│       ├── test_labels_tcr.csv    # Test labels for TCR split
│       └── test_labels_epi.csv    # Test labels for Epitope split
│
├── catELMo/
│   ├── Base/
│   │   ├── model_code.py          # Code for the base model
│   │   ├── tcr_split_weights.pt   # Model weights (TCR split)
│   │   ├── epi_split_weights.pt   # Model weights (Epitope split)
│   │   ├── test_labels_tcr.csv    # Test labels for TCR split
│   │   └── test_labels_epi.csv    # Test labels for Epitope split
│   │
│   ├── Model/
│       ├── model_code.py          # Code for the enhanced model
│       ├── tcr_split_weights.pt   # Model weights (TCR split)
│       ├── epi_split_weights.pt   # Model weights (Epitope split)
│       ├── test_labels_tcr.csv    # Test labels for TCR split
│       └── test_labels_epi.csv    # Test labels for Epitope split
│
├── Picture.png                    # Visualization image
└── README.md                      # Project documentation
```

# Citation
# Context-Aware Amino Acid Embedding (catELMo)

This section introduces the catELMo model, a context-aware amino acid embedding designed for advancing the analysis of TCR-epitope interactions. The associated article is available on bioRxiv.

```bibtex
@article {catelmobiorxiv,
	author = {Pengfei Zhang and Seojin Bang and Michael Cai and Heewook Lee},
	title = {Context-Aware Amino Acid Embedding Advances Analysis of TCR-Epitope Interactions},
	elocation-id = {2023.04.12.536635},
	year = {2023},
	doi = {10.1101/2023.04.12.536635},
	publisher = {Cold Spring Harbor Laboratory},
	journal = {bioRxiv}
}
```

# ATM-TCR: TCR-Epitope Binding Affinity Prediction Using a Multi-Head Self-Attention Model

ATM-TCR demonstrates how a multi-head self-attention based model can be utilized to learn structural information from protein sequences to make binding affinity predictions.

```bibtex
@article {10.3389/fimmu.2022.893247,
	author = {Cai, Michael  and Bang, Seojin  and Zhang, Pengfei  and Lee, Heewook },
	title = {ATM-TCR: TCR-Epitope Binding Affinity Prediction Using a Multi-Head Self-Attention Model},
	journal = {Frontiers in Immunology},
    volume = {13},
    url = {https://www.frontiersin.org/journals/immunology/articles/10.3389/fimmu.2022.893247},
	year = {2022},
	doi = {10.3389/fimmu.2022.893247},
	issn = {1664-3224}
}
```