Mineral Dataset for Machine Learning-based Mineral Classification

Overview

This dataset is designed for training machine learning models in mineral classification. It includes a collection of mineral formulas, metadata, and oxidation states, structured for easy integration into machine learning workflows. The dataset has been carefully curated with explicit oxidation states and formatted to facilitate automated classification, with an emphasis on scalability for future data additions.

Structure

The dataset is divided into several components to ensure consistency and clarity:

1. Mineral Formulas
Each mineral formula is represented in a machine-readable format: [['Element', count, 'oxidation state']].
Oxidation states are explicitly included to maintain chemical accuracy, especially for transition metals like Fe.
The dataset includes oxide wt% values as well as elemental wt% conversions where applicable.
2. Metadata
Each record in the dataset is associated with metadata that provides context for the mineral data. The metadata columns include:

Mineral Name (standardized using IMA naming conventions)
Mineral Frequency (e.g., common, rare, etc.)
Sample Label
Rock Name
Classification (e.g., metamorphic, igneous, hydrothermally altered, etc.)
Latitude
Longitude
DOI (Digital Object Identifier for reference)
IGSN (International Geo Sample Number)
Method (methods used for sample analysis)
Data Source (e.g., GEOROC, ARDC)
Vocabulary (controlled vocabularies for standardization)
3. Oxidation States
The oxidation states for each element are maintained explicitly and are critical for ensuring the chemical balance of each formula.
Oxidation states are particularly important for minerals that contain elements like Fe, Cu, and Mn.
4. Sample Data
The dataset includes examples from various mineral groups, including silicates, oxides, sulfides, carbonates, and more.
The data is presented in both oxide wt% and elemental wt% formats. Conversion factors are provided for users to switch between the two formats.
Data Management & Adding New Data

To ensure the dataset remains organized and easy to maintain, follow these guidelines when adding new data:

1. Format Consistency
Ensure new mineral formulas follow the established machine-readable format: [['Element', count, 'oxidation state']].
Include oxidation states for all relevant elements, including transition metals.
Represent groups like SO₄²⁻ or CO₃²⁻ as individual elements with oxidation states (e.g., [['S', 1, '2-'], ['O', 4, '2-']]).
2. Metadata
Include all relevant metadata fields for each new entry.
The Vocabulary column should be filled according to the controlled vocabularies used in the dataset.
Metadata should be consistent with existing records, ensuring fields like Mineral Name, Sample Label, and Rock Name are clearly defined.
3. Data Quality
Only include minerals that have verified, complete formulas.
Ensure that all oxidation states are correct and that charge balance is maintained in formulas.
For oxide minerals, verify the inclusion of both oxide wt% and elemental wt% values where applicable.
4. Adding New Entries
Add new mineral entries by appending them to the dataset in the same structure.
When adding new metadata, follow the standard vocabulary and ensure that all entries are populated with the correct fields.
5. Data Updates & Corrections
If updating or correcting data, please provide a brief note in the Commit Message to explain the changes.
When new data sources are added (e.g., new databases or publications), reference them in the Data Source field and update the DOI or IGSN fields accordingly.
Future Directions

This dataset is designed to be scalable, with future updates planned to include:

A broader range of mineral types.
More comprehensive oxidation state data.
Enhanced metadata for better dataset context and usability.
