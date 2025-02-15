# Visual R1: Transfer Reasoning Ability from R1 to Visual R1

DeepSeek-R1 demonstrates outstanding reasoning abilities across various problems except visual-related problems. Although there are some efforts to implement multimodal R1, they all focus on enhancing the reasoning ability of VL models. 

We build this project to create a model that can transfer reasoning Ability from LLMs (R1) to MLLMs (Visual R1).

## Stage1: Multimodal Pretraining
At this stage, we focus on enhancing textual R1 for visual perception by bridging a visual encoder and an adpter. Now, we obtained a preliminary version of Visual R1.

## Stage2: Multimodal Anneal
At this stage, we focus on enhancing Visual R1's multimodal ability while maintaining its ability to think slowly about text through various multimodal data, general text data, and textual reasoning data.

## Stage3: Multimodal SFT
At this stage, we utilize multimodal reasoning data to enable Visual R1 to acquire multimodal reasoning ability.

## Stage4: Multimodal RL
At this stage, we further enhance Visual R1's multimodal reasoning ability. 

Thus, we have transfer reasoning ability from R1 to Visual R1 that can reason with both text and images. 
