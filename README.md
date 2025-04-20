# Drug Gene Interaction Hypergraph Analysis
---
TODO:
Hypergraph properties
Gene + optionally disease, get all drugs it could've came from

---
### Description
---
This is the repo associated with the [INSERT PAPER] paper. Take a look at Tools/Visualization to see results

### Install
---
Requires `python3.7`
`pip install -r requirements.txt`

### 📂 Folder Descriptions

- **`Data/`** – Holds raw and processed datasets, including genetic variant files, phenotype labels, demographic metadata, and drug treatment information.
- **`Gen_Hypergraph/`** – Includes scripts for generating the incidence matrices of hypergraphs used in the methods. Each notebook will generate a single layer. Each is weighted with the PPI network.
DrugGeneHypergraph => Specific Disease (leave None for no diseases)
MSigDB => Full Layer
K-Hop => Requires an importance score from methods
hypergraphs for a specific disease, Outputs will be under **`Gen_Hypergraph/outputs`**
- **`Methods/`** – Contains the Random Walk with Restart on a single layer, Multilayer approach, and unidirectional multilayer approach



