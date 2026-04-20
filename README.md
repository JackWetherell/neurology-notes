# Neurology Notes

Personal study notes on the neurological foundations of the mind, written up as a single LaTeX document: **_From Potentials and Chemicals to the Mind_**.

The long-term aim of these notes is to build a working understanding of the mind from both neurological and psychological standpoints, starting from the physical substrate (ions, membranes, neurons, glia) and working upward toward cognition, behaviour, and personality.

## Source Material

The notes follow the structure of **Ninja Nerd's Neurology lecture series** on YouTube:

- Playlist: [Ninja Nerd, Neurology](https://www.youtube.com/watch?v=ADAOsuaOSCk&list=PLTF9h-T1TcJgx3OFachdjHPMX6VE4VDS1)

Ninja Nerd provides the scaffolding and the ordering of topics; the written notes are my own reworking of that material, written in a lecture-note style and supplemented where useful with additional explanation, clinical context, and connections to psychology.

## Contents

The document currently covers the basics of neurology:

1. **Nervous System Structure**, CNS and PNS anatomy, cerebrum, cerebellum, brainstem, cranial nerves, ventricles, spinal cord, and the autonomic nervous system.
2. **Neuron Structure**, soma, dendrites, axon, internal machinery, axonal transport, synaptic vesicles, SNARE proteins, and neurotransmitters.
3. **Neuron Firing**, resting potential, the Nernst equation, graded potentials, the action potential, synaptic release, reuptake, and refractory periods.
4. **Glial Cells**, astrocytes, oligodendrocytes, Schwann cells, myelin, ependymal cells, microglia, and their roles in health and disease.
5. **The Frontal Lobe**, primary motor cortex, premotor and supplementary motor areas, frontal eye field, Broca's area, and the prefrontal cortex.
6. **The Parietal Lobe**, primary somatosensory cortex, somatosensory association cortex, and the posterior parietal cortex.

Further sections will be added as the lecture series progresses.

## Files

- `neurology.tex`, the source document.
- `neurology.pdf`, the compiled PDF (rebuilt from the source).
- `neurology.aux`, `neurology.log`, `neurology.out`, `neurology.toc`, `neurology.synctex.gz`, LaTeX build artifacts.

## Building

The document is a standard `article`-class LaTeX file and can be built with any modern TeX distribution:

```
pdflatex neurology.tex
pdflatex neurology.tex
```

Two passes are needed to resolve the table of contents and cross-references.

## Status

Work in progress. Expect the document to grow and be revised as the lectures are worked through.
