# JADE Dataset

This repository contains the released dataset for our paper:

**Breaking Free from Ivory Tower: Evaluating and Enhancing Real-world Chinese Underground Adversarial Jargon Detection**

## Files

- `jargon.csv`: released adversarial jargon dataset.

The dataset contains the following columns:

- `adversarial_jargon`: the adversarially perturbed jargon observed in real-world data.
- `restored`: the corresponding canonical or restored jargon form.
- `transform_type`: the perturbation type applied to the jargon. This field is represented by an integer from 1 to 10.

The mapping between `transform_type` and perturbation types is shown below:

| `transform_type` | Perturbation Type |
| --- | --- |
| 1 | Homophone |
| 2 | Pinyin |
| 3 | English |
| 4 | Visual Substitution |
| 5 | Character Split |
| 6 | Synonym Substitution |
| 7 | Semantic Shift |
| 8 | Sequence Restructuring |
| 9 | Emoji |
| 10 | Symbol |

## Notes

The dataset has been manually reviewed before release to reduce the risk of disclosing personally identifiable information.

## Citation

If you use this dataset, please cite our paper.
