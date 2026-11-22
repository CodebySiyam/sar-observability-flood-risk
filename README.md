# A Grid-based Explainable Multimodal GeoAI Framework for Present and Future Cyclone-Induced Flood Vulnerability Assessment and Adaptation Prioritization

Code for the BSc thesis (Department of Software Engineering, Daffodil International University).

## Run order
notebooks/analysis: P3_L1 -> P3_D -> P3_M -> Q1_Validation_Ladder -> Q1_Extra_Checks -> P4 -> P5 -> P6 -> Q1_NAWG -> P7.
Set ROOT at the top of each notebook to your own data folder. All seeds are fixed (42).

## Data
Large derived data (250 m grid, master table, labels, observability mask, predictions, risk and priority classes): [Zenodo DOI].
Raw input data are not redistributed; download them from the sources in Table 3.3 of the thesis.
The original Google Earth Engine scripts were not archived.

## Licences
Code: MIT. Derived data include values from FABDEM (CC BY-NC-SA 4.0, non-commercial) and OpenStreetMap (ODbL),
so the derived data are shared for non-commercial research use under the same terms.
