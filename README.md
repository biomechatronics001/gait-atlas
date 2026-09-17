# Cross-Dataset Gait Explorer: 120 Public Datasets

**Open the explorer: https://biomechatronics001.github.io/gait-atlas/**

One page, no install, no sign-in. It draws every curve released by the 120 public
datasets of the paper's field, healthy unassisted adults, on one gait-cycle clock.

## What you can do with it

Pick a measure, a joint and a movement, and every dataset that published that channel
is drawn at once, each in its own colour, with the pooled median and the
between-dataset band over the top. Click a curve, or a name in the list beside it, to
pin that dataset and read where it came from: its citation, its identifier, how many
participants, which leg, what its cycle origin was, and what it deposited but held back.

For level walking you can also filter by walking speed. A dataset that published
several speeds splits into one curve per speed rather than being averaged across them,
and any dataset that cannot be split says so instead of quietly pooling.

Angular velocity and joint power are drawn over 3 to 97 per cent of the cycle. They are
derivatives, and the derivative is undefined across the seam where one stride meets the
next.

## What it is not

It shows the released dataset-level curves, one mean and one between-dataset spread per
dataset, action and channel. It is not per-participant data and it is not raw data.

Each dataset is named by its number, as in `#104 Dorschky 2019`, so it can be traced
back to a single record.

## Provenance

Every count on the page is computed from the released data when the page is built, none
is typed. A verifier renders the page and checks each displayed number against the data
it claims to come from, in both light and dark themes, and refuses to publish a page
that disagrees.

The released tables, the pipeline that produces them and the manuscript live elsewhere
and will be linked here on publication.

## Citation

Zhou, J., Zhong, S., Zheng, B., Gao, W., Wang, S., Yuan, Y., Zhou, X., & Su, H.
(2026). *A Survey and Harmonization of 120 Public Datasets for Cross-Dataset
Analysis of Lower-Limb Kinematics, Kinetics, and Surface EMG*. Manuscript and
data release, version 2026-09-15.
https://biomechatronics001.github.io/gait-atlas/

The archival DOI will be added after it is assigned. If you use specific curves,
also cite their original dataset publications; select any dataset in the explorer
to open its source citation. The explorer's **Cite** button also provides BibTeX.
