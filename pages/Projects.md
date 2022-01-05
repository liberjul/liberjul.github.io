---
layout: page
title: Projects
permalink: projects/
---
## Engineering phyllosphere yeasts
<img src="/images/JL233-8_YPDA_001.JPG" alt="A plant with 6 yeast strains streaked ono it. They vary in color, texture, and colony shape" width="300"/>

Yeasts, of many different genera, are abundant and persistent members of the microbial communities on plant leaves. Genetic manipulation of yeasts may be useful to inform the fundemental processes involved in community assembly and host-microbe interactions, and may be leveraged to improve plant resiliency under stress.

## Effects of immune-deficient genotypes of *Arabidopsis thaliana* on eukaryotic phyllosphere microbiomes
<img src="/images/Arabidopsis_mbbc_example.JPG" alt="A mutant Arabidopsis plant with missing receptors of pathogens" width="300"/>

Several mutants of *Arabidopsis thaliana* which are missing receptors for recognizing pathogens can develop a harmful assembly of microorganisms in their leaves, called dysbiosis. We are interested in the role fungi may play in the process of dysbiosis.


## Associations of *Linnemannia elongata* with Arabidopsis thalina roots
<img src="/images/Col0_NVP64-_day25_wga_cf_60x_3d_slice_w_scale_003_merge_20um.png" alt="Blue Linnemania hyphae occupying spaces in Arabidopsis roots, shown by red cell walls" width="300"/>

Many fungi and close associations with host plants, and alter their physiology in ways that affect their fitness and agronomic traits. We examined the role of the abundant soil fungus *Linnemannia elongata* and its associated endohyphal bacteria on the growth of the model plant *Arabidopsis thaliana*.

Collaborators: Dr. Natalie Vande Pol

## Interactions of bacterial and fungal endophytes with plant disease
<img src="/images/Rhizopus_w_roots.jpg" alt="Rhizopus hyphae and fluorescent Enterobacter on Brachypodium roots" width="300"/>

Bacteria and fungi occupy tissues of plants and can affect phenotypes of their host, often in response to stress. How these communities colonize plant roots with respect to other symbionts and plant disease state is not well explained. Using co-inoculation of bacteria and fungi on <i>Brachypodium distachyon</i>, and infection with barley yellow dwarf virus, we have worked to explore the factors influencing microbial community assembly.

Collaborators: Natalie Golematis, Dr. Carolyn Malmstrom, Ellen Cole, Kota Nakasato

## Nematode vectoring of fungal endobacteria
<img src="/images/Aphe_avenae_100x.jpg" alt="Aphelenchus avenae (a nematode) on Mortierella hyphae" width="400"/>

Fungal endobacteria of the genus <i>Mycoavidus</i> show evidence of horizontal transfer between fungal lineages. However, the mechanism of this transmission is unknown. Fungivores in soil, such as <i>Aphelenchus</i> nematodes, may be a vector for these endobacteria. So far, we have detected enrichment of endobacterial DNA relative to fungal nuclear DNA in surface sterilized nematodes, compared to fungal tissue. Future work will include visualizing ingested endobacteria and testing transmission via feeding.

Collaborators: Natalie Golematis, Ashley Barstow

## CONSTAXv2: Consensus-based taxonomy assignment for metagenomics
![Classification performance of CONSTAXv2 classifier](/images/speed_and_region_classification_part_cv.png)

With increasing popularity of metagenomics barcoding studies, researchers require high-throughput taxonomic assignment tools to identify taxa or OTUs from NGS reads. CONSTAXv2 implements a consensus approach, using multiple classifiers (SINTAX, RDP, and UTAX or BLAST) to improve performance. Version 2 implements a new BLAST classification approach, with updated software requirements, an easier-to-use implementation, isolate mapping, and SILVA database compatibility.

Tool Github and Tutorial: [https://github.com/liberjul/CONSTAXv2](https://github.com/liberjul/CONSTAXv2)
Preprint: [CONSTAX2: Improved taxonomic classification of environmental DNA markers](https://www.biorxiv.org/content/10.1101/2021.02.15.430803v1)

Collaborators: [Dr. Gian Maria Niccolo' Benucci](https://github.com/Gian77)

## Fungal communities of leaf litter
![Barchart of the relative makeup of fungal communities by genus](/images/top30_genera_gg_constax.png)
Decomposition of leaf litter in forest ecosystems largely depends on fungi and is a critical process in the terrestrial carbon cycle. Fungi also live in soil and the tree phyllosphere, but the relative contribution of these communities to the leaf litter is unknown. We used ITS amplicon sequencing to characterize and compare fungal communities in leaf litter, soil, leaf surfaces (epiphytes), and leaf internal tissues (endophytes).

Collaborators: Jud Van Wyk, Douglas Minier, Anna Stouffer-Hopkins, Reid Longley

## Comparative genomics of <i>Mycoplasma</i>-related endobacteria (MRE)
![Stacked barchart of proportions of KEGG BRITE annotations for genes](/images/Level2_BRITE_barplot.png)

Fungi in the Mucoromycota are known to have <i>Mycoplasma</i>-related bacteria inhabiting their cells. These bacteria are likely obligate endosymbionts, some with highly reduced genomes, and can have [impacts on host phenotypes](https://www.nature.com/articles/s41396-018-0053-9). We are looking for signatures of endosymbiosis in their genomes, and aim to infer the phylogeny of these symbionts and their hosts. While these symbionts may be
obligate, there may be horizontal transfer between hosts.

Collaborators: Alicja Okrasińska
## Systematics of Mortierellaceae
<img src="/images/Mortierella_rosette.jpg" alt="Rosette of Mortierella elongata on MEA + YE" width="300"/>

Mortierellaceae is a family of globally-distributed fungi often associated with soil, insects, or dung. This is a highly diverse group, with undescribed genera and species. We are working to culture new strains from globally-collected substrates, sequence and characterize these strains, and describe new taxa. Some strains in this group may also be useful for arachidonic acid production, microalgae harvesting, or plant symbiosis.

Paper: [Resolving the Mortierellaceae phylogeny through synthesis of multi-gene phylogenetics and phylogenomics](https://link.springer.com/article/10.1007/s13225-020-00455-5)
[PDF](/pdfs/Vandepol2020_Article_ResolvingTheMortierellaceaePhy.pdf)
Collaborators: Dr. Natalie Vande Pol, Natalie Golematis, Audrey Peiker, Abigail Bryson

## Automated phenotyping of filamentous fungi
<video src="/images/tip_tracking_vid.mp4" poster="/images/tip_tracking_poster.jpg" width="600" controls preload></video>

Filamentous fungi are difficult organisms to phenotype, because of the small number of characters which are easily observed. In order to characterize the diversity of groups such as Mortierellaceae, we developed a [TensorFlow](https://www.tensorflow.org/)-based object detection model trained on a manually-curated set of hyphal tip images. This model is accompanied by tools to annotate time-lapse image series infer growth rate by connecting nearest-neighbor annotations between consecutive images.

Tool Github and Tutorial: [https://github.com/liberjul/Hyphal_feature_tracking](https://github.com/liberjul/Hyphal_feature_tracking)

Collaborators: Natalie Golematis, Audrey Peiker

## Algal-fungal co-culture and flocculation
<img src="/images/Algae_010.jpg" alt="Wild algae captured in Mortierella hyphae" width="600"/>

Microalgae are highly productive photosynthetic organisms which have the potential to make valuable products for food, energy, and other industries. Some species of microalgae adhere to Mortierella hyphae which may be [exploited for harvesting microalgae](https://biotechnologyforbiofuels.biomedcentral.com/articles/10.1186/s13068-018-1172-2). We are working to undercover mechanisms of this interaction.

Review paper: [Harvesting microalgae for food and energy products](https://onlinelibrary.wiley.com/doi/abs/10.1002/smtd.202000349)
[PDF](/pdfs/smtd.202000349.pdf)

Collaborators: Dr. Zhi-Yan Du, Conor Bertucci
