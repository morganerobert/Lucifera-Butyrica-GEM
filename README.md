# Lucifera-Butyrica-GEM

Genome-scale metabolic model reconstruction of Lucifera butyrica.

## Workflow

1. Genome annotation imported into KBase.
2. Draft GEM generated with ModelSEED.
3. GEM reconstructed with ModelSEED2 (OMEGGA).
4. Models exported as SBML.
5. Quality assessed using MEMOTE.

## Results

| Model | Reactions | Metabolites | Genes | MEMOTE |
|---------|---------|---------|---------|---------|
| ModelSEED | 285 | 411 | 69 | 93% |
| OMEGGA (MS2) | 364 | 443 | 5051 | 89% |

## Repository structure

- models/: SBML models
- memote/: MEMOTE reports
- notebooks/: Google Colab workflow
