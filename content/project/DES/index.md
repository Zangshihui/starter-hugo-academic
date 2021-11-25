---
title: Measure cosmic tides with DES Y1 data
summary: We performed 2-shear-term and 5-shear-term tidal reconstruction in red shift space with six independent catalogs produced by N-body simulation and soft mass cut. The cross correlation coefficient, propagator and noise power are used to quantify the results of two tidal reconstruction algorithms in red shift space.
tags:
- DES
date: "2021-11-22T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Photo by rawpixel on Unsplash
  focal_point: Smart

links:

url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example
---

 Previous study has investigated the formalism and implementation of tidal reconstruction in real space, and it did not take peculiar velocity of halos into account. The RSD effect induced by peculiar velocity will affect cosmic tidal reconstruction, but its effects on two reconstruction algorithm are different for that they utilize different shear terms. 2-shear-term tidal reconstruction is less affected by RSD effect since it only involves derivatives on tangential plane of observation , while 5-shear-term tidal reconstruction is expected to be more impacted by RSD effect since it involves direct observation along line-of-sight.

 The project discusses tidal reconstruction in redshift space by using cross correlation coefficient, propagator and noise power to quantify tidal reconstruction with redshift-space distortion. We compare both 2-shear-term tidal reconstruction and 5-shear-term tidal reconstruction to show their robustness in redshift space.

Since the RSD effect brings about anisotropy in 5-shear-term tidal reconstruction. The RSD effect is a second-order effect in 2-shear-term tidal reconstruction for that two shear terms are not sensitive to errors along line-of-sight. Although 5-shear-term tidal reconstruction is likely to suffer from the RSD effect, this algorithm still performs slightly better than 2-shear-term tidal reconstruction in redshift-space, recovering more modes.

We also acquire large-scale linear bias from tidal reconstruction in redshift-space. The bias is constant in each bin with good approximation, which can be well fitted into a quadratic polynomial. However, more detailed studies are required to explain the relation behind anisotropic bias and peculiar velocity.