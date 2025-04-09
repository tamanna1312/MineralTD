MRMineral & MineralTD

MRMineral is a  dataset containing 400 unique minerals. It is designed as a ML-ready dataset derived from parsed and cleaned mineral formulas.

Each entry in MRMineral includes the following:

1. Mineral Name: Official name of mineral as recognised by standard references such as the International Mineralogical Association (IMA).
2. Chemical Formula: Stoichiometric mineral formula. 
3. Group: Top-level mineral classification based on chemical and structural characteristics (e.g., silicates, oxides, carbonates, sulphides).
4. Subgroup: Second-level mineral classification within each group, reflecting structural similarities (e.g., feldspars, pyroxenes, zeolites).
5. Machine Readable Formula: Nested list representation of the formula, including element symbol, stoichiometry, and oxidation state (e.g., [['Mg', 2, 2], ['Si', 1, 4], ['O', 4, -2]]).
6. Elemental wt%: Weight percentage of each element in the mineral, calculated from its chemical formula.

MineralTD is a training dataset — structured, metadata-rich collection of mineral data gathered from a variety of sources.

Each entry in MineralTD includes:
-Metadata fields such as:
  1. Mineral frequency (e.g., common, rare)
  2. Sample label or ID
  3. Rock type
  4. Data source
  5. DOI
  6. Analytical method.
  7. IGSN (International Geo Sample Number)
  8. Latitude and longitude 
  9. Source information, including references to original publications, databases (e.g., RRUFF, Mindat)
Oxide and element wt% data

Ultimately, these datasets provide a scalable framework that grows with community contributions.

We welcome contributions from the community!

### To contribute:
1. Fork this repository.
2. Add your new data in the mineralTDMeasured file — including the oxide or element wt% dataand all relevant metadata (e.g., mineral name, rock type, DOI, etc.).
3. Open a pull request so your data can be included in the main dataset after a quick format and quality check.

