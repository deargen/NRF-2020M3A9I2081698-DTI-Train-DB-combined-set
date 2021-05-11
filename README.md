# NRF-2020M3A9I2081698-DTI-Train-DB-combined-set
Drug-Target interaction binding set used as DTI train DB

## Data download link 
https://drive.google.com/file/d/1nXpcmGyfqA924nezJQr-iIwnJiLRZwuf/view?usp=sharing

## Data Source 
- ChEMBL
- Curated from the literature by BindingDB
- PDSP Ki
- PubChem
- Taylor Research Group, UCSD
- US Patent

## End point (nM unit)
- EC50
- IC50
- Kd
- Ki

## Data distribution
- Total pair counts : 1,804,964
  - curated pairs in which organism is virus : 6,186
  - pairs in which organism is not virus : 1,798,778

## Columns description

column name | description
  ------------- | -------------
compound_id |compound id provided from bindingDB(https://www.bindingdb.org/bind/index.jsp)
smiles        |smiles of compound
target_id          |uniprot id of target protein. if openDB didn't provide id, it shows as '-'
target_name          |name of target protein. if openDB didn't provide id, it shows as '-'
fasta               |fasta sequence of protein. For viruses, curated fasta is used.
organism       |orgaism of protein
reaction_id       |reaction id provided from binidngDB
measure        |end point of each pair
value (nM)        |interaction values of each pair in nM unit
pubmed     |pubmed id of each pair. if openDB didn't provide id, it shows as '-'
