---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---
## Scattering in complex materials
![scattering of light waves](/images/complex_scattering.jpg "Scattering by heterogeneous birefringent material"){: style="max-width: 50%; float: right"}
Optical microscopy is an essential tool in the life sciences. Light can be used to investigate a specimen with minimal impact on its natural development. However, most biological tissues are highly heterogeneous materials that scatter light anistropically. This severely limits the reach of optical microscopes. As part of this project, we develop new tools to study light-waves in biological tissue. Such knowledge is used to develop micropy methods that are resillient to scattering and/or actively compensate for it. Recent innovations in numerical methods have brought calculations on the microscopy-scale within reach. The latest algorithm is made [publicly available as the MacroMax library](https://github.com/tttom/MacroMax), and we anticipate to soon solve scattering problems that are an order of magnitude larger.

## Planar light-sheet microscopy with curved laser beams
Light-sheet microscopy illuminates the specimen with a plane of light that is orthogonal to the detection objective. This significantly improves contrast and allows for rapid optical section with minimal sample exposure. However, the diffraction of the illumination leads to a trade-off between axial resolution and the field-of-view. Non-diffracting laser beams as the Airy beam can avoid this trade-off to maximize both resolution and field-of-view.
[![neurons in detail](/images/planar_airy_lightsheet_brain_tissue.jpg "Hippocampal tissue, imaged using the two-photon planar Airy light-sheet on the Aurora™ microscope.")](https://doi.org/10.1364/BOE.395547)
The Airy beam is perhaps best known for its curved trajectory. Ordinarly, a light-sheet created by an Airy beam is correspondingly curved. While this leads to optimal resolution for single-photon excitation, the curvature is impractical when two-photon excitation is used to image deeper into tissue. To address this issue, we created a [planar Airy light-sheet](https://doi.org/10.1364/BOE.395547) from the propagation-invariant, yet curved, Airy beam. The technique we developed is now commercially available as part of [M Squared Life's](https://www.m2lasers.com/) [Aurora™ system](https://www.m2lasers.com/microscopy-aurora.html).

## Funding
This project and [Tom Vettenburg](https://sites.dundee.ac.uk/vettenburg/) are supported by [UKRI](https://www.ukri.org) [Future Leaders Fellowship](https://www.ukri.org/our-work/developing-people-and-skills/future-leaders-fellowships/) grant MR/S034900/1.
