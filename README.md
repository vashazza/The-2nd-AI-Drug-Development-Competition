# The 2nd AI Drug Development Competition (JUMP AI 2024)

**KPBMA AI Drug Discovery Institute, Sep. 2024, Team Leader**

Activity (QSAR) prediction for drug candidate molecules.

## Approach
- Started from a Random Forest baseline on molecular fingerprints.
- Added external ChEMBL data and compared graph-based (GAT) and language-model-based (ChemBERTa) molecular representations.
- Explored a multimodal pipeline combining graph and text representations.

## Files
- `Baseline RandomForest JUMP AI 2024.ipynb`: Fingerprint + Random Forest baseline
- `ChEMBL Import.ipynb`: External data collection from ChEMBL
- `GAT QSAR JUMP AI 2024.ipynb`, `GAT QSAR CORR.ipynb`: Graph Attention Network QSAR models
- `ChemBERTa JUMP AI 2024.ipynb`: ChemBERTa-based SMILES model
