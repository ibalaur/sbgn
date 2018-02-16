---
title: Learning SBGN
layout: default
permalink: /learning_sbgn
---

# Learning SBGN

<p>This is a brief introduction in the SBGN languages, and, in particular, we will focus on the Process Description language as the most used language of the SBGN standard. There are 3 languages in SBGN: Activity Flow (AF), Process Description (PD) and Entity Relation (ER).</p>

![Repersentations](/sbgn/images/learning/lenovere_representations.png)

In the figure the same biological system is shown in different representations depending on the concepts used to describe it (Le Novère, 2015, [doi:10.1038/nrg3885](https://dx.doi.org/10.1038/nrg3885)). Note the same set of four proteins on each of the diagrams. In Process Description ELK1 shown in three differents states, with ELK1 sumoylation (SUMO) and phosphorylation (P) processes.

## Process in SBGN PD

<p>It is be much simpler to understanding the Process Description language and read diagrams if we focus on the process glyph in each case:</p>
  
image process glyph

<p>Represented in PD, a biological process includes 1) incoming consumption link(s) to the process, 2) production link(s) from the process, and often 3) regulatory link(s) to the process, for example stimulation or inhibition.</p>

image catalysis

## SBGN PD dictionary

<p>Here are some illustrations of how biological concepts such as metabolic reaction or complex formation are reflected in the SBGN Process Description language (Junker et al., 2012, <a href="https://dx.doi.org/10.1016/j.tibtech.2012.08.003">doi:10.1016/j.tibtech.2012.08.003</a>).</p>

image | Metabolic reaction
image | Catalysis
image | Protein phosporylation
image | Complex formation
image | Complex dissociation
image | Transcription
image | Translation

## Start drawing online

<p>You can draw your first SBGN diagram online without installing any software.</p>

Launch Newt button

## Additional materials

After reading the SBGN paper (Le Novère et al, 2009, [doi:10.1038/nbt.1558](https://dx.doi.org/10.1038/nbt.1558)), please review [example diagrams](/examples) and additional tutorial materials that can be found in the [Education Resource](https://github.com/sbgn/educational-resources) repository.

## SBGN PD Reference Card

![SBGN PD Reference Card](/sbgn/images/learning/PD_L1V1.3.png)