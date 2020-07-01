# FairMOT_plus_plus
multi-object person detect and tracking
# 2020中兴捧月算法大赛-多目标检测与跟踪
1、赛题思路见PDF文件

2、重要说明：
   在FairMOT基础上，进一步研究了半监督训练的方法的可行性。具体而言，使用未标记的数据在预训练的FairMOT的基础上生成伪标记，在这个过程中只对目标检测的centerness branch（目标中心分支）进行训练，不回归box size
