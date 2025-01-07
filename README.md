# ctgan-checkpoints
This code is a Fork of the original [CTGAN library](https://github.com/sdv-dev/CTGAN) which we made due to licencing. 
We used the code to generate synthetic data for experiments in our paper:

```
@inproceedings{rajabinasab2025,
    title={Metrics for Inter-Dataset Similarity with Example Applications in Synthetic Data and Feature Selection Evaluation},
    author={Rajabinasab, Muhammad and Lautrup, Anton D. and Zimek, Arthur},
    booktitle={Proceedings of the 2025 SIAM International Conference on Data Mining (SDM)},
    pages={TBD},
    year={2025},
    organization={SIAM}
}
```
For our purposes we had to modify a few parts of the code. The main changes are to the training loop where we saved and evaluated the model at each epoch. This allowed us to assess how our proposed metrics behaved during model training. 

See the project repository for the full experiments and code: [Inter-Dataset Similarity Metric Based on PCA](https://github.com/mrajabinasab/Interdataset-Similarity-Metrics)