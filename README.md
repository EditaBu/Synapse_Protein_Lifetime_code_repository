# Synapse_Protein_Lifetime_code_repository
Created by Edita Bulovaite (Edita.Bulovaite@ed.ac.uk), Zhen Qiu (z.qiu@ed.ac.uk) and Seth Grant (seth.grant@ed.ac.uk).

### Introduction
Matlab code to generate figures for the manuscript: Bulovaite, E., Qiu, Z., Kratschke, M., Fricker, D.G., Tuck, E.J., Gokhale, R., Jami, S.A., O'Dell, T.J., Merino-Serrais, P., DeFelipe, J., Husi, E., Holtmaat, A., Fransén, E., Komiyama, N.H., Grant, S.G.N. (2021). Synapses with diverse protein lifetimes provide the building blocks for memory systems.

### License
The code is licensed under the MIT License (refer to the LICENSE file for details).

### Prerequisites
Mathworks Matlab 2014b or above.

### Descriptions
#### 1. CA1_gradients.mlx
Matlab code to generate Fig.2D and 5C: gradient line plot of mean (+/- SD) fraction of puncta remaining at day 7 compared to day 0 across segments of apical and basal dendrites of CA1.

#### 2. Correlation_density_intensity_halflife.mlx
Matlab code to generate Fig.S11: scatter plot and pearson correlation coefficient estimation for density- and intensity-based half-life estimations.

#### 3. Correlation_eGFPvsSiR.mlx
Matlab code to generate Fig.S7: scatter plot (+/- SD) and pearson correlation coefficient estimation for PSD95-eGFP and PSD95-HaloTag puncta densities across 110 brain subregions from compound heterozygous mice.

#### 4. LPL_subtypes_barplot.mlx
Matlab code to generate Fig.4D: bar plot showing the LPL (long protein lifetime) synapses as a percentage of total synapse number across subregions of the brain.

#### 5. TotalIntensity_decay_part1.mlx
Matlab code to extract individual puncta size, mean intensity and total puncta number from all experimental animals across all regions and subregions of the brain. The data is later used in part2 to fit an exponential decay function and produce the half-life values that are presented in Figs. 2A, S10, S11, and S12.

#### 6. TotalIntensity_decay_part2.mlx
Matlab code to fit an exponential decay function on puncta total intensity values to estimate PSD95 half-life. Results presented in Figs. 2A, S10, S11 and S12.

#### 7. similarity_matrix_halflife.mlx
Matlab code to generate Fig.5D: differences in PSD95 half-life across 110 subregions is transformed into a measure of similarity between pairs of subregions using a Gaussian kernel function. The result is plotted as a heatmap.

#### 8. sorted_halflife.mlx
Matlab code to generate Fig.2C: sorted reginal half-life measures are plotted as scatter plots and colour-coded according to the overarching brain area.

#### 9. subtype_PSD95_protein_lifetimes.mlx
Matlab code to generate Fig.4B: estimated PSD95 half-lives in different subtypes across brain subregions were plotted as a heatmap with subtypes on the x-axis and brain subregions on the y-axis. The heatmap is plotted with scaled rows.
