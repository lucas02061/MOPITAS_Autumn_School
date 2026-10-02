# Datasets

Data for the hands-on sessions. Files in here are **not tracked by git**, only the folder structure is.
Download or copy each session's data into its folder before running the notebooks.

Notebooks in `solutions/<session>/` and `work/<session>/` read from these paths (e.g. `../../datasets/<session>/`).

| Folder | Used by | Contents / source |
|---|---|---|
| `Hands_on_1_Spatial_Data/` | `scML_spatial_xneium.ipynb` | Xenium output folder, `scRNAseq_data.h5ad`, `xenium_data.h5ad`, `xenium_data_mapped.h5ad`, `CRC_UNB_10X_GSE132465.h5ad` |
| `Hands_on_2_LIANA_MistY/` | `image/*`, `spot/*` | Created by `image/00_setup.ipynb` (`brain_section.h5ad`) and the `liana` dataset cache (`anndata/`) |
| `Hands_on_3_NiCo/` | `NiCo.ipynb` | |
| `Hands_on_4_Tangram/Task_1/` | `Tangram_hands_on_task_1` | `markers.csv`, `ad_map.h5ad` |
| `Hands_on_4_Tangram/Task_2/` | `Tangram_hands_on_task_2` | `lu_scRNA_mouse_fetal_liver_pp.h5ad`, `lu_merfish_mouse_fetal_liver_2021.h5ad`, `ad_ge_tangram_2.h5ad`, `tangram_mapped_mouse_fetal_liver.h5ad` |
| `Hands_on_4_Tangram/Task_3/` | `Tangram_hands_on_task_3` | `c_sc_ad.h5ad`, `c_sp_ad.h5ad`, `c_atac_genes_ad.h5ad`, `ad_map_task3.h5ad` |
| `Hands_on_5_Spapros/` | `spapros_tutorial_*` | `pbmc3k_marker_list.csv`, `spapros_selection_*`, `spapros_evaluation_*` |
