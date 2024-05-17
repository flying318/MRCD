# MRCD
multi-resolution change detection analysis, training and module design
![framework](https://github.com/flying318/MRCD/blob/main/fig/multi-scale.jpg)
<!-- ![framework](https://github.com/flying318/MRCD/blob/main/fig/frame.jpg) -->
# Abstract
Change detection (CD) in remote sensing imagery has become an increasingly substantial task in the monitoring of natural resources and disaster response. However, existing CD methods face a notable challenge in terms of resolution scalability, wherein the resolution gap during training and testing stages leads to a substantial performance decline. To address this issue, this paper first constructs two synthetic multi-resolution benchmark datasets through the resampling of existing public CD datasets. Subsequently, the impact of varying resolutions on CD models is systematically analyzed, accompanied by the introduction of a novel multi-resolution training (MRT) strategy aimed at improving the robustness of CD methods. Additionally, a plug-and-play module, termed the resolution pyramid constraint (RPC), is designed to facilitate alignments between multi-resolution features and original single-resolution features. With the impact analysis of varying resolutions, some interesting observations are found in this paper. Moreover, the proposed MRT and RPC are validated to be effective in enhancing the robustness of change detection.
## Getting started
Code will be available soon. 🚀

## Acknowlodgement
This work is built upon the following repositories:
* [MMSegmentation](https://github.com/open-mmlab/mmsegmentation.git)
* [Open-CD](https://github.com/likyoo/open-cd.git)
