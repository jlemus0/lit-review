---
bibliography: references.bib
---

# Notes

## Exploring bacterial diversity via a curated and searchable snapshot of archived DNA sequences

### Blackwell, 2021

-   Characterize bacterial genomes with uniform standardized approach.

-   Ease of finding things out about genomes, searching.

-   Good for finding similarities between genomes, plasmids/SNPs, current databases/resources can't do that well

-   Uniform, searchable assemblies, technical barrier lowered.

-   COBS index allows for searching for SNPs, specific genes, plasmids, break into k-mers

-   MinHash searches for similar genomes.

-   pp-sketch index calculates genetic distances between assemblies.

-   90.6% of the data set came from 20 species, (data set from ENA sequence archive, public genomic data sequenced by others)

-   Used to find antimicrobial resistance genes in bacteria, how many.

-   Find multi-class resistant genomes/species (resist 3+ classes of antimicrobials)

-   Some biases present in data, bias towards medically relevant bacteria, MCR genomes, can't do prevalence estimates

-   Want to sample and sequence many different bacteria to improve data, remove biases, get from diverse environments and global locations to accurately study gene flow.

    [@blackwell2021]

## Insufficient sampling constrains our characterization of plant microbiomes

### Bullington, 2021

-   Current sampling practices poorly characterize microbial groups, need increased sampling intensity for better reproducibility and identification of subtler microbial distributions.

-   No optimal sampling strategy yet, sampling effort bottleneck

-   non-reproducible studies due to improper description of sampling methods, robustness not reported, small plant samples may not accurately represent total population of microbes.

-   Lots of variation in SVs found between different methods (except for AMFs), extreme FFE undersampling (increase in richness w/ plant size), can still see seasonal variation

-   Neither approach gave more species richness except for homogenizing before subsampling for bacteria. Needs more effort for plant microbes than soil microbes, can't get the whole picture, just a snapshot

-   More effort needed for FFE than AMF because there are more of them?

-   Need more detailed sampling info in papers, non-arbitrary sampling effort, increasing sampling effort when studying subtle differences in microbial communities/fully characterizing microbial communities.

    [@bullington2021]

## Iron-Only and Vanadium Nitrogenases: Fail-Safe Enzymes or Something More? Harwood, 2020 [@harwood2020]

-   Nitrogenases used to fix N2 to NH3, (Fe)-Mo nitrogenases most efficient, use least ATP, make least H2. VFe and FeFe nitrogenases also used, less efficient (more ATP, H2). May be useful when running low on Mo or using H2 as fuel in hydrogenotrophs.

-   VnfH and NifH very similar sequence-wise, 95% AA sequence similarity.

-   Mo nitrogenase minumum dedicated gene set is nifH, nifD, nifK, nifB, nifE, nifN. nifHDK forms the nitrogenase, while nifBEN helps with FeMo cofactor synthesis.

-   V nitrogenase uses vnfHDGK structural genes and vnfEN assembly genes, homologous to the nif versions, also needs nifB (vnfG is gamma subunit of VFe protein)

-   Fe-only uses anfHDGK, but no anfEN. Requires nifUSVB for activity. Both alternative paths require nif genes to work, microbes that Fe-only/V nitrogenase also make Mo nitrogenase.

-   All need low potential electrons for redox.
