MRMineral & MineralTD

MRMineral is a  dataset containing 400 unique minerals. It is designed as a ML-ready dataset derived from parsed and cleaned mineral formulas.

Each entry in MRMineral includes the following:

Mineral Name: Official name of mineral as recognised by standard references such as the International Mineralogical Association (IMA).
Chemical Formula: Stoichiometric mineral formula. 
Group: Top-level mineral classification based on chemical and structural characteristics (e.g., silicates, oxides, carbonates, sulphides).
Subgroup: Second-level mineral classification within each group, reflecting structural similarities (e.g., feldspars, pyroxenes, zeolites).
Machine Readable Formula: Nested list representation of the formula, including element symbol, stoichiometry, and oxidation state (e.g., [['Mg', 2, 2], ['Si', 1, 4], ['O', 4, -2]]).
Elemental wt%: Weight percentage of each element in the mineral, calculated from its chemical formula.

MineralTD is a training dataset — structured, metadata-rich collection of mineral data gathered from a variety of sources.

Each entry in MineralTD includes:
-Metadata fields such as:
  Mineral frequency (e.g., common, rare)
  Sample label or ID
  Rock type
  Data source
  DOI
  Analytical method.
  IGSN (International Geo Sample Number)
  Latitude and longitude 
  Source information, including references to original publications, databases (e.g., RRUFF, Mindat), or datasets

Ultimately, these datasets provide a scalable framework that grows with community contributions.

We welcome contributions from the community!

### To contribute:
1. Fork this repository.
2. Add your new data in the mineralTDMeasured file — including the oxide or element wt% dataand all relevant metadata (e.g., mineral name, rock type, DOI, etc.).
3. Open a pull request so others can review and merge your contribution into the main dataset.


