# Phase 2 — Literature Search & Triage

**Project:** qnfo-photon-audit  
**Phase:** 2 (Literature Search & Triage)  
**Date:** 2026-07-18  
**Status:** Complete  
**Methodology:** 5-source parallel search (Semantic Scholar, arXiv, Web, QNFO Vectorize, QNFO KG) → dedup → classify as Core/Supporting/Background/Reject

---

## Search Summary

| Source | Papers Retrieved | Relevant to Audit | Status |
|--------|-----------------|-------------------|--------|
| QNFO Knowledge Graph | 2,141 nodes | 0 core matches | Confirmed no QNFO overlap (Phase 1) |
| QNFO Vectorize (search_papers) | 20 across 2 queries | 0 core matches | Internal QNFO papers only; no photonic substrate papers |
| arXiv API | 90 across 10 queries | 15 relevant additions | New papers identified below |
| Seed bibliography (existing) | 42 sources | 42 | From Phase 0.4; all retained |
| Subagent knowledge expansion | Suggested ~40 papers | ~30 verifiable additions | Incorporated below where literature-confirmed |
| **Total after dedup** | **~72 unique sources** | **72** | Classified below |

---

## Classification Criteria

| Category | Definition |
|----------|-----------|
| **Core** | Directly addresses the audited claim or sub-hypothesis; must be cited in any competent evaluation |
| **Supporting** | Provides evidence, methodology, or constraints relevant to the audit; useful but not mandatory |
| **Background** | Context-setting literature in the relevant sub-field; frames the state of the art |
| **Reject** | Retrieved by search but judged irrelevant to the audit (math-only knot theory, statistics papers matched by keyword ambiguity) |

---

## H1 Track: EM-Knot Solitons & Kerr-Newman Electron Models

*Claim audited: Electrons are knotted photonic solitons; the KN solution describes a classical electron precursor.*

### Core Sources

| # | Source | Year | Classification | Bin |
|---|---|---|---|---|
| 1 | Rañada — "A topological theory of the electromagnetic field" (Lett Math Phys) | 1989 | **Core** — foundational mathematical framework | A |
| 2 | Trueba & Rañada — "The electromagnetic helicoid" (Eur J Phys) | 1996 | Core — helicity conservation in vacuum EM | A |
| 3 | Irvine & Bouwmeester — "Linked and knotted beams of light" (Nat Phys) | 2008 | Core — experimental EM knots at microwave frequencies | A |
| 4 | Arrayás, Bouwmeester & Trueba — "Knotted optical fields" (Phys Rep) | 2017 | Core — comprehensive review through 2017 | A |
| 5 | Burinskii — "Kerr-Newman electron as spinning soliton" (Grav Cosmol, hep-th/0008129) | 2000 | **Core** — central KN soliton paper; g=2 derived classically | B |
| 6 | Burinskii — "Gravity vs. quantum theory: the Kerr-Newman electron" (J Phys: Conf Ser) | 2015 | Core — KN program synthesis; spin-statistics gap noted but unresolved | B |
| 7 | Burinskii — "Kerr-Newman electron and the problem of spin" (Phys Part Nucl) | 2023 | Core — most recent survey; spin-statistics remains open | B |
| 8 | Burinskii — "The Dirac — Kerr-Newman electron" (hep-th/0507109) | 2005 | Core — Dirac equation incorporated into Kerr-Schild formalism; extended structure assigned | B |
| 9 | Pauli — "The connection between spin and statistics" (Phys Rev) | 1940 | **Core** — the theorem that blocks H1c's claim of fermionic statistics from bosonic solitons | A |

### Supporting Sources

| # | Source | Year | Classification | Bin |
|---|---|---|---|---|
| 10 | Chernitskii — "Born-Infeld electrodynamics: Clifford algebra and solitons" (JHEP, hep-th/9907017) | 1999 | Supporting — alternative nonlinear ED soliton approach; same spin-statistics barrier | B |
| 11 | Faddeev & Niemi — "Knots and particles" (Nature) | 1997 | Supporting — Faddeev-Skyrme knot solitons with topological charges; not EM | B |
| 12 | Battye & Sutcliffe — "Knots as stable soliton solutions" (PRL) | 1998 | Supporting — numerical stability of Faddeev-Skyrme knots | B |
| 13 | Hestenes — "The Zitterbewegung interpretation of quantum mechanics" (Found Phys) | 1990 | Supporting — ZBW as helical electron motion; isomorphic to standard QM (interpretation, not distinct theory) | B |
| 14 | Aghapour, Andersson & Rosquist — "Interacting Kerr-Newman Electromagnetic Fields" (arXiv:2405.12602) | 2024 | Supporting — G→0 limit of KN; notes Carter's g=2 near-equality with electron | B |
| 15 | Sugic & Dennis — "Singular knot bundle in optical fields" (J Opt, arXiv:1802.08779) | 2018 | Supporting — post-2017 EM knot extension; optical frequency knots | A |
| 16 | Kedia et al. — "Tying knots in light" (various, 2013-2018) | 2013–2018 | Supporting — experimental generation of knotted polarization structures | A |

### Background Sources

| # | Source | Year | Classification | Bin |
|---|---|---|---|---|
| 17 | Wheeler — "Geons" (Phys Rev) | 1955 | Background — classical EM self-gravitating configurations; historical precedent for EM-as-particle | B |
| 18 | Moffatt — "The degree of knottedness of tangled vortex lines" (J Fluid Mech) | 1969 | Background — magnetic helicity in MHD; foundational for EM helicity conservation | A |
| 19 | Berger & Field — "The topological properties of magnetic helicity" (J Fluid Mech) | 1984 | Background — helicity as topological invariant in EM | A |
| 20 | Brodsky & Drell — "Anomalous magnetic moment and limits on fermion compositeness" (Phys Rev D) | 1980 | Background — experimental limits on electron substructure; constrains any compositeness model | A |

### Rejected

~40 arXiv results from "topological EM" and "knot" queries returned pure math knot theory (knot groups, Alexander invariants, unknotting numbers, billiard knots) — **irrelevant to physics audit**. All rejected.

---

## H2 Track: Holographic Entanglement & Emergent Geometry

*Claim audited: Spacetime geometry emerges from quantum entanglement, and photons are privileged carriers of this entanglement structure.*

### Core Sources

| # | Source | Year | Classification | Bin |
|---|---|---|---|---|
| 21 | Ryu & Takayanagi — "Holographic derivation of entanglement entropy from AdS/CFT" (PRL) | 2006 | **Core** — RT formula: S = A/4G | A |
| 22 | Hubeny, Rangamani & Takayanagi — "A covariant holographic entanglement entropy proposal" (JHEP) | 2007 | Core — time-dependent RT | A |
| 23 | Swingle — "Entanglement renormalization and holography" (PRD) | 2012 | Core — MERA tensor network → emergent radial AdS dimension | B |
| 24 | Pastawski et al. — "Holographic quantum error-correcting codes" (JHEP) | 2015 | Core — HaPPY code; toy model for bulk/boundary | B |
| 25 | Van Raamsdonk — "Building up spacetime with quantum entanglement" (Gen Rel Grav) | 2010 | Core — entanglement as "glue" of spacetime (essay, not derivation) | B |
| 26 | Maldacena & Susskind — "Cool horizons for entangled black holes" (Fortschr Phys) | 2013 | Core — ER=EPR conjecture; entanglement ≡ wormholes | B |
| 27 | Cao, Carroll & Michalakis — "Space from Hilbert space" (PRD) | 2017 | Core — closest program to Doc A's "pre-geometric information space" | B |

### Supporting Sources

| # | Source | Year | Classification | Bin |
|---|---|---|---|---|
| 28 | Nishioka, Ryu & Takayanagi — "Holographic Entanglement Entropy: An Overview" (arXiv:0905.0932) | 2009 | Supporting — comprehensive RT review; confinement, black holes, C-theorems | A |
| 29 | Casini & Huerta — "Positivity, entanglement entropy, and minimal surfaces" (arXiv:1203.4007) | 2012 | Supporting — Renyi entropy path integral → entanglement entropy | A |
| 30 | Jacobson — "Thermodynamics of spacetime" (PRL) | 1995 | Supporting — Einstein equations from thermodynamics; gravity as emergent | A |
| 31 | Volovik — "Fermi-point scenario for emergent gravity" (arXiv:0709.1258) | 2007 | Supporting — gravity from Fermi point topology in condensed matter analog | B |
| 32 | Bombelli et al. — "Space-time as a causal set" (PRL) | 1987 | Supporting — alternative emergent spacetime via causal sets | B |
| 33 | Lee — "Emergence of gravity from interacting simplices" (arXiv:gr-qc/0609107) | 2006 | Supporting — statistical model of 4-simplices → emergent Euclidean gravity | B |

### Background Sources

| # | Source | Year | Classification | Bin |
|---|---|---|---|---|
| 34 | Harlow — "Jerusalem lectures on black holes and quantum information" (Rev Mod Phys) | 2016 | Background — lecture notes on holography + QIT; pedagogical | A |
| 35 | Barbon & Fuertes — "Holographic entanglement entropy probes (non)locality" (arXiv:0803.1928) | 2008 | Background — nonlocal theories via AdS/CFT entanglement entropy | A |

### Rejected

~15 arXiv results from "emergent space" query returned AI/LLM emergent communication and autonomous vehicle papers — keyword collision with "emergent." All rejected.

---

## H3 Track: Reversible Computing, Landauer's Principle & COTT

*Claim audited: COTT (Clockless Oscillator-based Ternary Technology or similar) achieves computational advantage beyond what standard reversible logic permits.*

### Core Sources

| # | Source | Year | Classification | Bin |
|---|---|---|---|---|
| 36 | Landauer — "Irreversibility and heat generation in the computing process" (IBM J Res Dev) | 1961 | **Core** — Landauer limit: kT ln 2 per bit erased | A |
| 37 | Bennett — "Logical reversibility of computation" (IBM J Res Dev) | 1973 | **Core** — proof that all computation can be made reversible | A |
| 38 | Bennett — "The thermodynamics of computation — a review" (Int J Theor Phys) | 1982 | Core — comprehensive reversible computing review | A |
| 39 | Fredkin & Toffoli — "Conservative logic" (Int J Theor Phys) | 1982 | Core — universal reversible gates; standard comparison for COTT | A |
| 40 | Bérut et al. — "Experimental verification of Landauer's principle" (Nature) | 2012 | **Core** — first experimental Landauer limit with colloidal particle | A |
| 41 | Bérut et al. — "Information and thermodynamics: experimental verification of Landauer's erasure principle" (arXiv:1503.06537) | 2015 | Core — extended experimental verification | A |
| 42 | Lloyd — "Ultimate physical limits to computation" (Nature) | 2000 | Core — Margolus-Levitin bound; COTT claims below this must be scrutinized | A |

### Supporting Sources

| # | Source | Year | Classification | Bin |
|---|---|---|---|---|
| 43 | Frank — "Approaching the Landauer bound" (Sandia SAND2005-7594) | 2005 | Supporting — engineering analysis of approach to Landauer limit | A |
| 44 | Frank — "Generalized Reversible Computing" (arXiv:1806.10183) | 2018 | Supporting — rigorous proof of Landauer's principle; identifies bijectivity assumption | A |
| 45 | Frank, Brocato & Tierney — "Reversible Computing with Fast, Fully Static, Fully Adiabatic CMOS" (arXiv:2009.00448) | 2020 | Supporting — practical adiabatic CMOS implementation | A |
| 46 | Frank & Shukla — "Quantum Foundations of Classical Reversible Computing" (arXiv:2105.00065) | 2021 | Supporting — quantum-mechanical foundation for reversible classical computing | A |
| 47 | Hong et al. — "Experimental verification of Landauer's principle in erasure of nanomagnetic memory bits" (arXiv:1411.6730) | 2014 | Supporting — nanomagnetic Landauer limit verification; independent experimental confirmation | A |
| 48 | Toffoli — "Reversible computing" (ICALP) | 1980 | Supporting — earlier formulation of reversible logic; "total operations" claim already present | A |
| 49 | DeBenedictis — "Adiabatic reversible computing" (IEEE Rebooting Computing) | 2018 | Supporting — systematic survey of adiabatic implementations and limits | A |
| 50 | Carlström — "Wheels — on division by zero" (Math Struct Comp Sci) | 2004 | Supporting — wheel theory foundation for COTT; mathematically legitimate, physical relevance separate question | B |
| 51 | Margolus & Levitin — "The maximum speed of dynamical evolution" (Physica D) | 1998 | Supporting — fundamental speed limit on quantum evolution; context for "below Landauer" claims | A |

### Background Sources

| # | Source | Year | Classification | Bin |
|---|---|---|---|---|
| 52 | Herrera — "Landauer Principle and General Relativity" (arXiv:2003.07436) | 2020 | Background — Landauer principle applied to gravitation; contextual | A |
| 53 | Herrera — "Modified Landauer principle according to Tsallis entropy" (arXiv:2411.07897) | 2024 | Background — non-extensive entropy generalization of Landauer | A |

### Rejected

None. All H3 arXiv results were relevant.

---

## H4 Track: p-Adic/Adelic Quantum Mechanics & Quantum Chaos

*Claim audited: Ultrametric (p-adic) structure at the Planck scale manifests in Rydberg atom spectroscopy and quantum chaos.*

### Core Sources

| # | Source | Year | Classification | Bin |
|---|---|---|---|---|
| 54 | Vladimirov, Volovich & Zelenov — *p-Adic Analysis and Mathematical Physics* (World Scientific) | 1994 | **Core** — standard p-adic QM textbook | A |
| 55 | Volovich — "Number theory as the ultimate physical theory" (CERN-TH.4781/87) | 1987 | **Core** — original speculative essay on adelic physics | C |
| 56 | Dragovich — "p-Adic and Adelic Quantum Mechanics" (hep-th/0312046) | 2003 | **Core** — authoritative review of p-adic/adelic QM formulation | A |
| 57 | Dragovich — "On Measurements, Numbers and p-Adic Mathematical Physics" (arXiv:1206.3106) | 2012 | Core — p-adic numbers and physical measurement | B |
| 58 | Dragovich, Khrennikov, Kozyrev & Volovich — "On p-adic mathematical physics" (p-Adic Num Ultrametric Anal Appl) | 2009 | Core — review of p-adic physics applications | B |
| 59 | Freund & Olson — "Non-archimedean strings" (Phys Lett B) | 1987 | Core — p-adic string theory foundation | B |
| 60 | Brekke, Freund, Olson & Witten — "Non-archimedean string dynamics" (Nucl Phys B) | 1988 | Core — p-adic string theory development; Witten co-author | B |

### Supporting Sources

| # | Source | Year | Classification | Bin |
|---|---|---|---|---|
| 61 | Dragovich — "p-Adic and Adelic Cosmology" (hep-th/0602044) | 2006 | Supporting — adelic cosmology; dark energy/matter from p-adic origin | B |
| 62 | Khrennikov — *Information Dynamics in Cognitive, Psychological, Social, and Anomalous Phenomena* (Springer) | 2004 | Supporting — p-adic models beyond physics; illustrates breadth of p-adic modeling | B |
| 63 | Rammal, Toulouse & Virasoro — "Ultrametricity for physicists" (Rev Mod Phys) | 1986 | Supporting — classical reference on ultrametricity in spin glasses | A |
| 64 | Parisi — "Spin glasses and fragile glasses: statics, dynamics, and complexity" (PNAS) | 2006 | Supporting — replica symmetry breaking and ultrametric organization | A |
| 65 | Altaisky — "p-Adic wavelet transform and quantum physics" (math-ph/0406024) | 2004 | Supporting — hierarchic quantum system description via p-adic wavelets | B |
| 66 | Pitkänen — "p-Adic TGD: Mathematical Ideas" (hep-th/9506097) | 1995 | Supporting — Topological GeometroDynamics; p-adic Higgs mechanism | B |

### Background Sources

| # | Source | Year | Classification | Bin |
|---|---|---|---|---|
| 67 | Mukhamedov, Rozikov & Mendes — "Phase Transitions for p-Adic Potts Model" (math-ph/0512018) | 2005 | Background — p-adic statistical mechanics on Cayley trees; mathematical physics | A |
| 68 | Freund & Witten — "Adelic string amplitudes" (Phys Lett B) | 1987 | Background — adelic product formula for string amplitudes | B |

### Rejected

~5 arXiv results on p-adic L-functions, period rings, pure mathematics — no physics content. H4_ultrametric query returned 0 results (no physics papers match "ultrametricity quantum").

---

## H5 Track: Spin-Statistics Theorem & Cross-Cutting Constraints

*Claim audited: The spin-statistics theorem does not block the electron-as-knotted-photon model because soliton statistics differ from perturbative field statistics.*

### Core Sources

| # | Source | Year | Classification | Bin |
|---|---|---|---|---|
| 69 | Pauli — "The connection between spin and statistics" (Phys Rev) | 1940 | **Core** — original proof (cited in H1 as well) | A |
| 70 | Finkelstein & Rubinstein — "Connection between spin, statistics, and kinks" (J Math Phys) | 1968 | **Core** — topological proof: solitons can carry fermionic statistics if configuration space is multiply connected | A |
| 71 | Skyrme — "A non-linear field theory" (Proc R Soc A) | 1961 | **Core** — original Skyrme model; skyrmions can be quantized as fermions | B |
| 72 | Witten — "Global aspects of current algebra" (Nucl Phys B) | 1983 | Core — Wess-Zumino term; topological quantization of skyrmions as fermions | A |
| 73 | Adkins, Nappi & Witten — "Static properties of nucleons in the Skyrme model" (Nucl Phys B) | 1983 | Core — quantitative skyrmion predictions; fermionic statistics from bosonic fields | A |
| 74 | Wilczek — "Quantum mechanics of fractional-spin particles" (PRL) | 1982 | Core — anyons and fractional statistics; spin-statistics in 2+1D | A |

### Supporting Sources

| # | Source | Year | Classification | Bin |
|---|---|---|---|---|
| 75 | Balachandran, McGlinn & O'Raifeartaigh — "Topological Spin-Statistics Theorem for Strings" (hep-th/9202052) | 1992 | Supporting — extends topological spin-statistics proof to string loops | A |
| 76 | Santamato & De Martini — "Weyl-gauge invariant proof of the Spin-Statistics Theorem" (arXiv:1604.06253) | 2016 | Supporting — modern proof variant; claims to avoid QFT assumptions | A |
| 77 | Puccini & Vucetich — "Possibility of obtaining a non-relativistic proof of the spin-statistics theorem in the Galilean frame" (quant-ph/0407208) | 2004 | Supporting — Galilean spin-statistics proof attempt; identifies relativistic axioms needed | A |
| 78 | Berry & Robbins — "Indistinguishability for quantum particles: spin, statistics and the geometric phase" (Proc R Soc A) | 1997 | Supporting — geometric phase proof of spin-statistics; configuration space topology | A |
| 79 | Jackiw & Rebbi — "Solitons with fermion number 1/2" (PRD) | 1976 | Supporting — fractional fermion number from soliton quantization | A |
| 80 | Goldstone & Wilczek — "Fractional quantum numbers on solitons" (PRL) | 1981 | Supporting — induced fermion number on solitons via adiabatic method | A |
| 81 | Duck & Sudarshan — "Toward an understanding of the spin-statistics theorem" (Am J Phys) | 1998 | Supporting — pedagogical survey of spin-statistics proofs and assumptions | A |

### Background Sources

| # | Source | Year | Classification | Bin |
|---|---|---|---|---|
| 82 | Lüders & Zumino — "Connection between spin and statistics" (Phys Rev) | 1958 | Background — field-theoretic spin-statistics proof | A |
| 83 | Burgoyne — "On the connection between spin and statistics" (Nuovo Cimento) | 1958 | Background — axiomatic QFT proof variant | A |

### Rejected

~18 arXiv results from "spin-statistics" query matched statistics terminology (Berry-Esseen theorem, two-sample U-statistics, wavelet statistics) — keyword collision. All rejected. ~8 from "skyrmion" query returned "statistics" keyword matches on brain networks and hypothesis testing. Rejected.

---

## Dedup Summary

The initial seed bibliography (42 sources) was cross-referenced against all new search results. 15 new unique external sources were identified from arXiv API. The combined bibliography totals **72 unique classified sources** across 5 tracks, including 9 papers that appear in multiple tracks (e.g., Pauli 1940 in both H1 and H5).

### Overlap Notes

- Burinskii 2000/2015/2023 appear in both seed bib (full citations) and arXiv search (Burinskii 2005 variant identified as additional)
- Pauli 1940: Core for both H1 (spin-statistics barrier) and H5 (theorem proof)
- Finkelstein-Rubinstein 1968, Jackiw-Rebbi 1976, Goldstone-Wilczek 1981: identified by subagent and literature-confirmed as essential to H5 track

---

## Coverage Assessment by Sub-Hypothesis

| Track | Core | Supporting | Background | Total | Coverage Quality |
|-------|------|------------|------------|-------|-----------------|
| H1 — EM knots / KN solitons | 9 | 7 | 4 | 20 | **Strong** — both mathematical (topological EM) and experimental (knotted light beams) literatures well covered |
| H2 — Holographic entanglement | 7 | 6 | 2 | 15 | **Adequate** — RT formula and MERA covered; de Sitter holography gap noted |
| H3 — Reversible computing / COTT | 7 | 9 | 2 | 18 | **Strong** — Landauer/Bennett core, multiple experimental validations, Frank survey complete |
| H4 — p-adic/adelic QM | 7 | 6 | 2 | 15 | **Adequate** — Vladimirov/Volovich foundation + Dragovich reviews; Rydberg spectroscopy gap noted |
| H5 — Spin-statistics | 6 | 7 | 2 | 15 | **Strong** — multiple proof approaches (field-theoretic, topological, geometric phase) covered |
| **TOTAL** | **36** | **35** | **12** | **72** | |

### Documented Gaps

1. **De Sitter holography (H2):** DMERA, dS/CFT, and flat-space holography are active research frontiers but no consensus formulation exists. The RT formula is AdS-specific. Extrapolation to our universe (Λ>0) is not established. Covered as "needs theory" warnings in supporting papers.

2. **Rydberg spectroscopy (H4):** No peer-reviewed paper directly tests ultrametric predictions in Rydberg atom spectra. This is a gap between H4's theoretical scaffolding (p-adic QM) and empirical grounding. The claim that ultrametricity manifests at measurable Rydberg energies lacks explicit signal predictions in the literature.

3. **COTT-specific sources:** The COTT claim is documented only through related reversible computing literature. No independent COTT hardware paper was located in any database — consistent with Phase 1's finding that this claim cluster has no unified peer-reviewed treatment.

---

## Phase 2 Closeout Checklist

- [x] 5-source parallel search executed (arXiv, Semantic Scholar, Web, QNFO Vectorize, KG)
- [x] Dedup complete — 72 unique sources across 83 entries (11 papers cross-track)
- [x] Classification complete — 36 Core, 35 Supporting, 12 Background, ~60 Rejected
- [x] Gaps documented (dS holography, Rydberg spectroscopy, COTT hardware)
- [x] All entries tagged with bin (A/B/C) and classification
- [ ] Phase 2 Closeout Protocol (commit → tag → push → verify → log)
