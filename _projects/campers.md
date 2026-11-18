---
title: "CaMPers"
project_id: campers
order: 1
summary: "Measuring how handedness is organized across scales in vector fields."
logo: "/assets/images/campers_logo.svg"
image: "/assets/images/campers_overview.png"
image_alt: "CaMPers workflow from sampled vector fields to directed complexes and multiscale summaries"
papers:
  - title: "CaMPers: Chiral Multiparameter Persistence for Vector Fields on Riemannian Manifolds"
    authors: "Austin A. MBaye, Jose A. Perea"
    status: "Preprint"
    # url: ""
# resources:
#   - name: "GitHub"
#     url: ""
#   - name: "PyPI"
#     url: ""
#   - name: "Documentation"
#     url: ""
---
Chirality in vector fields is commonly characterized by local differential quantities such as vorticity;  Rips-persistent homology, on the other hand, describes multiscale topology from metric relationships. 
Neither perspective alone determines how same-handed vector interactions organize across spatial scales. 
We introduce \emph{Chiral Multiparameter Persistence} (CaMPers), a framework for quantifying this organization in vector fields sampled on Riemannian manifolds. 
For each parameter tuple $\mathbf{p} = (d,\tau,\phi,r)$, CaMPers constructs positive and negative directed flag complexes whose edges encode spatial proximity, forward alignment, angular consistency, and signed rotation. 
It therefore measures how same-handed, forward-compatible vector interactions assemble into directed topological structures as interaction distance increases. 
To obtain computable representations of the resulting multiparameter persistence modules, we integrate their Euler characteristics over the non-distance parameters, producing Euler characteristic curves and a chiral Euler dominance curve that average over a prescribed threshold range. 
We establish explicit interleaving bounds for the extended multiparameter modules under small field perturbations,
and  also exhibit fixed-threshold one-parameter restrictions with infinite interleaving distance under arbitrarily small perturbations.
The presented examples demonstrate that CaMPers distinguishes fields with equal net circulation and fields with identical pointwise vorticity and isometric geometry, but different directed flow organization. 
Applications to synthetic vortex sequences, simulated Kolmogorov flow, and real experimental actomyosin cortical flows from \textit{C.~elegans} illustrate its use for detecting chiral organization and its variability in time-resolved vector-field data. 
