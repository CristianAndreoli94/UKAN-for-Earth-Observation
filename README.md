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
Recent work reports competitive KAN-based segmenters in remote sensing, yet evidence on large benchmarks remains limited, comparisons often conflate neuron choice with architecture, loss studies are narrow, and efficiency analyses rarely track total energy or VRAM. This study addresses these gaps on the FTW benchmark with multi-temporal Sentinel-2 RGB+NIR, comparing matched-parameter U-Net, U-KAN, and NOKAN, which replaces KAN neurons with standard linear units while keeping the same layout. The evaluation spans several loss families, applies Grad-CAM for explainability, and profiles energy and VRAM during training. Across losses, U-Net achieves the strongest pixel-level metrics with higher recall. U-KAN yields sharper object delineation and higher object-level precision but lower recall. At equal parameter budgets, NOKAN matches or slightly exceeds U-KAN on both pixel- and object-level metrics, indicating that much of the perceived gain comes from macro-architectural design rather than the neuron type. Richer losses mainly shift the precision–recall balance and do not overturn this ranking. Efficiency measurements show that U-KAN requires more VRAM, runs slower, and accumulates higher energy consumption, while U-Net and NOKAN are more frugal. Grad-CAM reveals more localized attributions for U-KAN and NOKAN than for U-Net, with loss choice shaping explanations more than neuron type. The work disentangles neuron effects from architecture and offers practical guidance for segmentation and XAI under compute constraints.

---

