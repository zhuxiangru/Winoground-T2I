# Winoground Dataset

original_winoground_dataset.txt: The Winoground dataset from huggingface. Download: [Winoground](https://huggingface.co/datasets/facebook/winoground)

Reference: [Winoground: Probing Vision and Language Models for Visio-Linguistic Compositionality(CVPR2022)](https://arxiv.org/abs/2204.03162)


# Winoground Compositional Labeling

winoground_compositional_dataset.txt: The visuolinguistic compositionality labeling on Winoground. 

These labels include ```no-tag```, ```ambiguously-correct```, ```visuallydifficult```, ```unusual-text```, ```unusual-image```, ```non-compositional```, ```complex-reasoning```, where ```no-tag``` represents visuolinguistic compositional text.



Reference: [Why is Winoground Hard? Investigating Failures in Visuolinguistic Compositionality(EMNLP2022)](https://aclanthology.org/2022.emnlp-main.143/)

# Winoground-T2I Templates and Modification Rules

template.txt: The templates and modification rules of seed sentence pairs from Winoground with the ```no-tag``` label.

The format is : original_winoground_id \t templeate_id \t	caption_0	\t caption_1 \t class \t template	\t modification_rule \t template_details(json) \t modification_examples(json)

Templates are initially extracted by ```gpt-3.5-turbo```. Subsequently, a verification process is conducted by human reviewers, which includes all templates and modification rules, along with their examples.
