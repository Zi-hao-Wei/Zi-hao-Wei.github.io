# Research figure sources

Figures belong to their respective paper authors. Local WebP versions are resized for the publication cards; transparent backgrounds are composited on white. No diagrams were synthesized.

- `av-msf.webp`: https://zisenshao.github.io/AV-MSF/data/teaser.png
- `mdc.webp`: https://cfeng16.github.io/mdlm4vfl/method_no_back.001.png
- `mae.webp`: Figure 1, page 1, https://openaccess.thecvf.com/content/CVPR2024W/ECV24/papers/Wei_Masked_Autoencoders_are_Secretly_Efficient_Learners__CVPRW_2024_paper.pdf
- `cluster.webp`: Figure 2, page 3, https://openaccess.thecvf.com/content/CVPR2024/papers/Wei_Efficient_Vision-Language_Pre-training_by_Cluster_Masking_CVPR_2024_paper.pdf
- `microdiffusion.webp`: https://raw.githubusercontent.com/UCSC-VLAA/MicroDiffusion/main/figures/model.png
- `a-esrgan.webp`: https://raw.githubusercontent.com/stroking-fishes-ml-corp/A-ESRGAN/main/figures/TotalArch.png
- `swinmm.webp`: https://raw.githubusercontent.com/UCSC-VLAA/SwinMM/master/figures/SwinMMArch.png
- `synthesis.webp`: Figure 1, page 3 of the author-provided `6273_Bridging_Audio_Visual_Sem.pdf`. A copy is in `/file/bridging-audio-visual-semantics.pdf`. Public record: https://openreview.net/pdf?id=78aQMuQqYF

## Maintaining the publication cards

Edit `_data/projects.json`; the home and Publications pages both use `_includes/projects.html`. Each entry has a title, authors, venue, paper URL, summary, image, image_alt, image_source, and kind (`paper` or `report`). Optional fields: website, code, code_label, award. Omit resources that are not public instead of adding placeholder links. Keep image source attribution with any replacement figures.

Resource links were checked on 2026-09-22. AV-MSF's project page labels code as coming soon. No separate official website or code was identified for the efficient MAE paper or the technical report. The report uses the supplied local PDF because OpenReview requests browser verification.
