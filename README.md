# UKAN-for-Earth-Observation
**The research is now completed and the manuscript is being submitted to the ISPRS Journal of Photogrammetry and Remote Sensing. \
Preprint will be available soon.**

---

## Authors
- [Cristian Andreoli](https://github.com/CristianAndreoli94/)  
  *MSc in Data Science, Department of Electronic and Information Engineering, University of Pavia*  

- [Leonardo Magliolo](https://github.com/MaglioloLeonardo)  
  *MSc in Artificial Intelligence, Department of Computer Science, University of Turin* \
  *PHD Student, Grounding the information flow for frugal AI, Télécom Paris*  

- [Fabio Dell'Acqua](http://tlclab.unipv.it/index.php/people/the-team?view=article&id=75&catid=23)  
  *Full Professor of Remote Sensing, Department of Electronic and Information Engineering, University of Pavia*  

---

## Abstract
Monitoring crop type and conditions at a large scale is important for plan ning interventions and supporting policies for food security and sustainabil ity. Large-scale monitoring is generally facilitated by the injection of ancillary geospatial data defining field boundaries, as these latter tend to partition the observed area into homogeneous sub-areas. With few exceptions, however, precise information on field boundaries is not widely available, either because data is not publicly accessible, or because it does not exist at all. Nowadays, wide availability of spaceborne Earth observation data offers a pathway to large-scale mapping if accurate, efficient, and explainable field-boundary seg mentation models are available to extract relevant information. Recent work reports indeed the use of competitive KAN-based segmenters in remote sens ing, yet evidence on large benchmarks remains limited; comparisons often conflate neuron selection with architecture, loss studies are narrow, and effi ciency analyses rarely track total energy consumption or compute resources. Motivated by these practical requirements and gaps, this work proposes the use of the recent U-KAN architecture, adopting it to the intended application and benchmarking it on the large “Fields of the World” (FTW) dataset. A series of controlled, matched experiments systematically disentangle neuron level contributions from architectural choices impact. Multiple loss families were evaluated, training-time energy consumption and VRAM usage under consistent settings were profiled and Grad-CAM was applied for post-hoc explainability to assess explanation sensitivity and efficiency. Overall, the controlled comparisons clarify the relative role of KAN neurons versus archi tectural choices in driving U-KAN behavior across accuracy, efficiency and post-hoc explainability. Resource profiling reveals that KAN neurons come with higher computational and energy costs. Across the tested losses and ar chitectures, both performance trends and Grad-CAM explanations are more sensitive to the loss choice and architectural design than to the neuron type. These findings support more reproducible comparisons and more informed design choices for KAN-based segmentation under practical compute and energy budgets.

---

