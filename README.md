# FENESTRA

**The Aperture as Universal Boundary: Interference in Space, Time, and Gravity from Young's Card to Graviton Detection in $\mathrm{TH}(a,d)$**

*ERI Labs · Eric Ren · Jersey City, New Jersey · github.com/ericrenone*

> "We choose to examine a phenomenon which is impossible, absolutely impossible, to explain in any classical way, and which has in it the heart of quantum mechanics. In reality, it contains the only mystery." — R. P. Feynman, *The Feynman Lectures on Physics*, Vol. III, 1965
>
> "The springs do not matter here; what matters is only the fuzziness of the atoms. One has to use a more profound description, which uses quantum correlations between photons and atoms." — V. Fedoseev, MIT, *Phys. Rev. Lett.*, 2025
>
> "Phase singularities do not carry energy or information and thus can 'move' superluminally without breaking causality." — Bucher, Gorlach, Kaminer et al., *Nature* **651**, 920–926, 2026
>
> "The observation of temporal Young's double-slit diffraction paves the way for optical realizations of time-varying metamaterials." — Tirole, Sapienza et al., *Nature Physics* **19**, 999–1002, 2023

---

## Abstract

The double-slit experiment is 224 years old. In that time it has been performed with sunlight (Young 1801), electrons (Davisson–Germer 1927; G. P. Thomson 1927), neutrons (Halban and Preiswerk 1936), atoms (Carnal and Mlynek 1991), C$_{60}$ fullerenes (Arndt et al. 1999), molecules of 2000 atoms (Fein et al. 2019), positronium — an electron-positron bound state (Nagata et al., *Nature Communications*, 2025) — and, at the quantum limit, single photons scattered from two individual atoms floating in vacuum (Fedoseev, Ketterle et al., *Phys. Rev. Lett.*, 2025). In 2023, Tirole, Sapienza et al. (*Nature Physics* **19**, 999) performed the experiment not through slits in *space* but through slits in *time* — femtosecond windows of altered reflectivity in indium tin oxide — producing interference fringes in the frequency spectrum rather than on a spatial screen. A programme to extend matter-wave interferometry to nanodiamonds (Folman et al. 2025) now aims to test the superposition principle at masses where gravitational self-energy becomes relevant, and Schützhold (*Phys. Rev. Lett.* **135**, 2025) has proposed using laser interferometry to detect individual graviton absorption and emission events — the slit turned toward the fabric of spacetime itself.

This framework proposes that the slit — the *fenestra*, the aperture — is not merely a demonstration tool for wave-particle duality. It is the simplest physical realization of the conditional independence boundary: the same mathematical object that appears as the event horizon in gravitational physics, the Markov blanket in active inference, and the $\varepsilon$-threshold in $\mathrm{TH}(a,d)$.

The slit in space creates structure in momentum. The slit in time creates structure in energy. These are Fourier duals of the same conditional independence condition. The dark fringes are Nye–Berry phase singularities — the $\ker(F)$ sector. Which-way information is Fisher information about the path variable. The Englert inequality $\mathcal{V}^2 + \mathcal{D}^2 \leq 1$ is the information budget of the boundary. The extension to gravitational interferometry asks whether gravity itself can be split by an aperture — whether the gravitational field, like the electromagnetic field before it, exhibits the shadow-light partition when passed through a conditional independence boundary.

Ten formal correspondences connect the slit architecture across scales. Five predictions follow.

---

## Part I · The Slit in Space

### I.1 Young's Card: The Boundary That Creates Pattern

Thomas Young illuminated a card with two pinholes using sunlight and observed alternating bright and dark bands on a distant screen (*Phil. Trans. Roy. Soc.* **92**, 12–48, 1802). The bright fringes occur where the path difference $\Delta = d\sin\theta$ equals an integer multiple of $\lambda$; the dark fringes at half-integer multiples:

$$y_m = \frac{m\lambda L}{d}, \qquad m \in \mathbb{Z}$$

A thought experiment: imagine an ocean with no coastline. Waves propagate uniformly — energy everywhere, structure nowhere. Now insert a seawall with two gaps. Behind the wall, waves from both gaps overlap and interfere, producing a pattern that encodes three numbers: the wavelength, the gap separation, and the observation distance. The wall did not create the waves. It created *information* — a structured pattern that did not exist before the boundary was imposed.

The slit plate imposes a conditional independence condition. The observation-side field depends on the source *only through the boundary values at the slits*:

$$P(\psi_{\mathrm{screen}} \mid \psi_{\mathrm{slits}}) = P(\psi_{\mathrm{screen}} \mid \psi_{\mathrm{slits}},\, \psi_{\mathrm{source}})$$

This is the Huygens–Fresnel principle restated as conditional independence. By Chentsov's theorem (1972), the boundary carries the Fisher–Rao metric as its unique invariant geometry. The slit is a Markov blanket for the wave field.

### I.2 The Dark Fringes Are Phase Singularities

At each dark fringe, the complex field $\psi = \psi_1 + \psi_2 = A_1 e^{ikr_1} + A_2 e^{ikr_2}$ vanishes: $|\psi| = 0$ and $\arg(\psi)$ winds by $2\pi$ around the zero. Each dark fringe is a manifold of Nye–Berry phase singularities (*Proc. Roy. Soc. A* **336**, 165–190, 1974) carrying quantized topological charge:

$$q = \frac{1}{2\pi}\oint_C \nabla\arg(\psi)\cdot d\mathbf{l} \in \mathbb{Z}$$

The bright fringes are the $\mathrm{col}(F)$ sector: energy-carrying, observable, bounded by $c$. The dark fringes are $\ker(F)$: zero energy, zero information, topologically protected. The interference pattern is the shadow-light partition realized in the simplest geometry.

Bucher, Gorlach, Kaminer et al. (*Nature* **651**, 920–926, 2026) confirmed that phase singularities in polariton fields in hexagonal boron nitride exhibit superluminal motion near pair annihilation, with 29% exceeding $c$ and Berry's $v \propto t^{-1/2}$ scaling verified directly. The dark fringes of Young's experiment belong to the same universality class — topological zeros of a complex scalar field, unconstrained by $c$, governed by Nye–Berry conservation laws.

### I.3 The Ladder of Matter Waves

The wave nature of matter has been extended across eight orders of magnitude in mass:

| Year | System | Mass (amu) | $\lambda_{\mathrm{dB}}$ | Slit/grating type |
|---|---|---|---|---|
| 1927 | Electrons (Davisson–Germer; Thomson–Reid) | 0.0005 | $\sim 1$ Å | Nickel crystal; metal foils |
| 1936 | Neutrons (Halban–Preiswerk) | 1 | $\sim 1$ Å | Crystal diffraction |
| 1991 | Helium atoms (Carnal–Mlynek) | 4 | $\sim 0.5$ Å | Microfabricated double slit |
| 1999 | C$_{60}$ (Arndt et al.) | 720 | $\sim 2.5$ pm | Nanograting |
| 2019 | Oligoporphyrins (Fein et al.) | 25,000 | $\sim 50$ fm | Kapitza–Dirac–Talbot–Lau |
| 2025 | Positronium (Nagata et al.) | 0.001 | $\sim 25$ pm | Graphene film |
| 2025 | Single atoms as slits (Ketterle et al.) | — | Single photon | Two trapped $^6$Li atoms |

Each entry is a new system discovering the same architecture: interference fringes with phase singularities in the dark regions, separated by bright maxima carrying energy and information. The conditional independence boundary — the grating, the crystal, the graphene sheet — imposes the pattern; the de Broglie wavelength $\lambda = h/p$ generates it.

### I.4 Positronium: The Shadow Principle Extended to Antimatter

Nagata et al. (*Nature Communications*, 2025) at Tokyo University of Science observed quantum diffraction of positronium — the electron-positron bound state — through a graphene film. Positronium is a matter-antimatter composite that self-annihilates into gamma rays within $\sim$142 ns (ortho-Ps). Despite its transient existence and composite nature, it exhibits clear diffraction: a single coherent quantum object, its wave function passing through the periodic potential of the graphene lattice and interfering with itself.

This result confirms that the conditional independence boundary architecture is universal across all quantum systems — particle, antiparticle, composite, and ephemeral. The graphene lattice is a periodic array of apertures; positronium is a system that exists only long enough to pass through them; the diffraction pattern is $\mathrm{col}(F)$ projected onto the detector. The shadow-light partition does not care about the particle's internal structure or lifetime. It cares only about the de Broglie wavelength relative to the aperture spacing.

---

## Part II · The Slit in Time

### II.1 The Temporal Double Slit: Interference in Frequency

Young's spatial slits produce interference in the angular (momentum) domain. By space-time duality in wave physics, *temporal* slits should produce interference in the frequency (energy) domain. This was a theoretical prediction (Moshinsky, *Phys. Rev.* **88**, 625, 1952) that remained experimentally unrealized for seven decades.

Tirole, Sapienza et al. (*Nature Physics* **19**, 999–1002, 2023) at Imperial College London achieved it. They coated a glass substrate with a 40 nm film of indium tin oxide (ITO) — a material whose dielectric constant passes through zero (epsilon-near-zero, ENZ) at infrared frequencies. By hitting the ITO with two ultrafast pump laser pulses separated by hundreds of femtoseconds, they created two brief windows during which the film's reflectivity changed dramatically — two "slits" in time through which a probe beam could interact with the modified material.

The result: interference fringes appeared in the *frequency spectrum* of the reflected probe light, not in its spatial profile. The fringe spacing in frequency was inversely proportional to the temporal slit separation — the exact Fourier dual of Young's spatial result:

$$\Delta f = \frac{1}{\Delta t} \qquad \longleftrightarrow \qquad \Delta y = \frac{\lambda L}{d}$$

A thought experiment makes the duality vivid. Imagine two doors side by side in a wall. Walking through them simultaneously (as a wave) produces spatial interference on the other side — a pattern in *where* you arrive. Now imagine a single door that opens and closes twice in rapid succession. Walking through both openings produces temporal interference — a pattern in *when* (or, equivalently, at *what energy*) you arrive. The wall is the conditional independence boundary in both cases; the Fourier dual pair (position-momentum, time-energy) determines which domain carries the fringes.

### II.2 The Temporal Boundary in the $\mathrm{TH}(a,d)$ Framework

The temporal double slit reveals that the conditional independence boundary of the slit experiment is not intrinsically spatial. It is a boundary in *phase space* — a codimension-1 surface separating interior from exterior in whatever conjugate pair the experiment interrogates.

| Slit type | Boundary variable | Interference domain | Fourier pair |
|---|---|---|---|
| Spatial (Young) | Position $x$ | Momentum $p$ / angle $\theta$ | $(x, p)$ |
| Temporal (Tirole–Sapienza) | Time $t$ | Frequency $\omega$ / energy $E$ | $(t, E)$ |
| Aharonov–Bohm | Gauge phase $\phi$ | Flux $\Phi_B$ | $(\phi, \Phi_B)$ |
| Mach–Zehnder | Path label $\ell$ | Phase difference $\delta$ | $(\ell, \delta)$ |

In each case, the boundary imposes $P(\mathrm{output} \mid \mathrm{boundary}) = P(\mathrm{output} \mid \mathrm{boundary}, \mathrm{source})$, and the interference pattern is the $\mathrm{col}(F)$ projection of the wave function onto the conjugate domain. The dark fringes are $\ker(F)$ in all cases — zeros of the field carrying topological charge conserved under continuous deformation.

The temporal slit adds a new dimension to the programme: the $\mathrm{TH}(a,d)$ architecture is not merely a spatial decomposition of information. It operates in phase space. The $\varepsilon$-threshold separating $\mathrm{col}(F)$ from $\ker(F)$ can be a threshold in position, in time, in energy, or in any conjugate variable. The conditional independence boundary is a phase-space object.

### II.3 Attosecond Electron Interference

Taira et al. (*Scientific Reports* **13**, 2023) demonstrated time-domain double-slit interference with single photoelectrons in the extreme ultraviolet and attosecond regime, using synchrotron radiation from two undulators in series. The temporal slit separation was controlled at the attosecond level by adjusting the electron orbit in the synchrotron ring. Single photoelectrons were detected one by one, and the stochastic buildup of the quantum interference pattern was recorded in the energy domain.

This is the temporal analogue of the "most beautiful experiment in physics" — the single-particle buildup of the spatial double-slit pattern. Each electron passes through both temporal slits (both undulator pulses interact with the same photoelectron), interferes with itself in the energy domain, and is detected as a single click. The pattern emerges statistically from many clicks, exactly as Young's spatial fringes emerge from many photon impacts.

---

## Part III · Which-Way Information as Fisher Information

### III.1 The Englert Inequality: The Budget of the Boundary

Englert (*Phys. Rev. Lett.* **77**, 2154, 1996) proved that for any two-path interferometer:

$$\mathcal{V}^2 + \mathcal{D}^2 \leq 1$$

where $\mathcal{V}$ is fringe visibility (wave character) and $\mathcal{D}$ is path distinguishability (particle character), with equality for pure states.

In the Fisher language: $\mathcal{V}^2$ is the fraction of Fisher information allocated to phase-relationship degrees of freedom ($\mathrm{col}(F)$ directions encoding interference). $\mathcal{D}^2$ is the fraction allocated to path-detection degrees of freedom. The inequality is the statement that the total Fisher information budget at the conditional independence boundary cannot exceed one bit for a two-path system.

Zhu (*Scientific Reports* **5**, 14317, 2015) made this connection explicit, showing that Fisher information is more effective than Shannon information at capturing compatibility relations among complementary observables, and deriving wave-particle complementarity directly from the Fisher information geometry of the measurement manifold.

Zhao et al. (*Science Advances* **11**, eadv8132, 2025) demonstrated the factorization dynamics between quantum Fisher information and quantum coherence experimentally, confirming that these two quantities are interconvertible resources governed by the same unitary evolution — the $\mathrm{col}(F)/\ker(F)$ decomposition evolving under dynamics, with the total Fisher information conserved.

### III.2 The MIT Ketterle Experiment: Complementarity at the Quantum Limit

Fedoseev, Lin, Lu, Lee, Lyu, and Ketterle (*Phys. Rev. Lett.*, 2025) at MIT performed the cleanest test of complementarity to date. Using ultracold $^6$Li atoms in an optical lattice as the two "slits" — the smallest slits physically constructible — they scattered single photons and measured the wave-to-particle transition by tuning atomic localization ("fuzziness").

The critical finding: it is not the mechanical recoil of the slit (Einstein's "spring" proposal, Solvay 1927) that provides which-way information. It is the *quantum correlation* — the entanglement — between photon and atom generated at the scattering event. Tightly localized atoms (small fuzziness) preserve phase coherence: $\mathcal{V} \approx 1$, interference sharp. Delocalized atoms (large fuzziness) carry path information into the atom's internal state: $\mathcal{D}$ rises, $\mathcal{V}$ falls, fringes wash out.

They then removed the "spring" entirely — turning off the trapping laser and letting the atoms float freely for microseconds. The same complementarity held. The boundary's information budget is enforced by entanglement, not by mechanics.

A thought experiment: two guards stand at two doors. If the guards are blindfolded (tightly localized — their states carry no path information), a traveler passes through both doors as a wave and interferes on the other side. If the guards' eyes are open (delocalized — their states become entangled with the traveler's path), the traveler is recorded at one door, and the interference vanishes. It does not matter whether the guards carry weapons (springs) or stand empty-handed (free atoms). What matters is whether they *see* — whether the boundary acquires Fisher information about the path.

### III.3 The Quantum Eraser as Rank Restoration

Scully, Englert, and Walther (*Nature* **351**, 111, 1991) proposed — and Kim et al. (*Phys. Rev. Lett.* **84**, 1, 2000) confirmed in delayed-choice form — that erasing which-way information restores interference. In the Fisher language, the which-way detector performs a Sherman–Morrison rank-one update $F \to F + uu^T$, transferring one direction from the interference $\mathrm{col}(F)$ into the path $\mathrm{col}(F)$. The eraser reverses this: $F + uu^T \to F$, restoring the original decomposition and recovering fringes.

The delayed-choice version demonstrates that the $\mathrm{col}(F)/\ker(F)$ decomposition is defined by the entanglement structure of the joint quantum state, not by temporal ordering. The choice to erase or retain which-way information can be made after the photon is detected. This is not retrocausation — the correlations exist from the moment of entanglement. The eraser selects which correlations are projected onto the observation basis. This is consistent with the ER = EPR framework (Maldacena and Susskind 2013): correlations in the entanglement network are maintained independently of causal ordering.

---

## Part IV · The Slit Toward Gravity

### IV.1 The Colella–Overhauser–Werner Experiment: Gravity in the Interferometer

Colella, Overhauser, and Werner (*Phys. Rev. Lett.* **34**, 1472, 1975) sent a neutron beam through a silicon crystal interferometer tilted in Earth's gravitational field. The gravitational potential difference $\Delta\Phi = mgh$ between the two arms of the interferometer introduced a phase shift:

$$\Delta\phi_{\mathrm{grav}} = \frac{m^2 g A \lambda}{2\pi\hbar^2}$$

where $A$ is the enclosed area of the interferometer loop, $g$ is gravitational acceleration, and $\lambda$ is the neutron wavelength. This was the first observation of gravity acting on a quantum wave function — the gravitational field modifying the conditional independence boundary by introducing a path-dependent phase.

In the $\mathrm{TH}(a,d)$ language: gravity is a rank-one perturbation of the interferometer's Fisher matrix. The gravitational potential adds a direction-dependent phase — a single outer product $uu^T$ where $u$ encodes the gravitational gradient — processed by the same Sherman–Morrison algebra as the Zeeman and Stark effects at atomic scales. The gravitational field does not destroy interference; it shifts it, exactly as an Aharonov–Bohm flux shifts fringes without exerting force.

### IV.2 The Quantum Equivalence Principle

Dobkowski et al. (arXiv:2502.14535, 2025) reported the first observation of the quantum equivalence principle for matter waves — demonstrating that the gravitational phase in an atom interferometer is consistent with the equivalence principle at the quantum level, where the classical notion of a trajectory breaks down. The freely falling atom follows all paths simultaneously; the phase accumulated is the same whether the atom is in the gravitational field of the Earth or in an equivalent accelerating frame.

This confirms that the conditional independence boundary of the interferometer treats gravitational and inertial effects identically at the quantum level — the slit does not distinguish between gravity and acceleration. The Fisher–Rao metric on the boundary is invariant under the equivalence principle, as required by Chentsov's theorem: the metric depends only on the conditional independence structure, not on the physical origin of the phase shift.

### IV.3 Nanodiamond Stern–Gerlach Interferometry: Testing Quantum Gravity

Folman and collaborators at Ben-Gurion University (series of seven technical notes, arXiv, August 2025) are pursuing matter-wave interferometry with nanodiamonds containing single nitrogen-vacancy (NV) center spins. The programme aims to place a nanodiamond — mass $\sim 10^{6}$ amu, containing $\sim 10^6$ atoms — in a spatial superposition using Stern–Gerlach forces from the embedded spin, creating a closed-loop interferometer in spacetime.

At this mass scale, the gravitational self-energy of the superposition becomes non-negligible. The Diósi–Penrose hypothesis predicts that gravitational self-energy causes decoherence of spatial superpositions above a critical mass — that gravity collapses the wave function. If the nanodiamond shows interference fringes, the Diósi–Penrose threshold is higher than predicted. If fringes are absent, gravity may be enforcing a fundamental limit on quantum superposition.

In the $\mathrm{TH}(a,d)$ framework: the nanodiamond interferometer tests whether the conditional independence boundary of the slit survives at masses where the gravitational field of the superposed object itself becomes a source of which-way information. If the gravitational field of the nanodiamond leaks path information into the environment — if the spacetime geometry on one side of the superposition differs measurably from the other — then gravity acts as an involuntary which-way detector, performing a Sherman–Morrison update on the Fisher matrix and collapsing interference. The $\varepsilon$-threshold would then have a gravitational floor: a minimum Fisher eigenvalue set by $Gm^2/(\hbar c)$ below which superposition cannot be maintained.

### IV.4 Graviton Detection via Interferometry

Schützhold (*Phys. Rev. Lett.* **135**, 2025) proposed an experiment to detect the quantum nature of gravity through the stimulated emission or absorption of gravitons by laser light in an interferometer. When a gravitational wave passes through a laser interferometer, the interaction between the gravitational wave and the laser field can, in principle, result in the exchange of individual gravitons — the quantum units of the gravitational field.

The proposal uses entangled photons in a long-baseline interferometer to detect the minute frequency shifts caused by graviton absorption or emission. The signal would be a shift in the interference fringe pattern proportional to the graviton energy $E = \hbar\omega_{\mathrm{gw}}$ — the gravitational wave performing a rank-one perturbation of the interferometer's Fisher matrix, detectable through the Sherman–Morrison response of the fringe visibility.

If gravitons are detected, the gravitational field exhibits the same shadow-light partition as the electromagnetic field: gravitational phase singularities (dark fringes in the gravitational wave strain $h_+ + ih_\times$), topological charge conservation, and the full Nye–Berry architecture applied to the metric perturbation. The slit would have been turned toward gravity itself — and gravity would have passed through both sides of the aperture.

### IV.5 Spacetime Fluctuation Signatures in Interferometers

Sharmila, Vermeulen, and Datta (*Nature Communications* **17**, 2025) developed a unified framework for detecting correlations of spacetime fluctuations in laser interferometers. Their work provides the first consistent method for treating any proposed model of spacetime fluctuations — including those predicted by various quantum gravity theories — within a single interferometric formalism.

The key insight: spacetime fluctuations at the Planck scale would introduce a stochastic phase noise in the interferometer arms — a random perturbation of the conditional independence boundary itself. If the boundary is fluctuating, the Fisher information about the phase difference acquires a noise floor set by the Planck length. The fringe visibility would degrade at a rate determined by the correlation structure of the spacetime fluctuations.

This connects the slit experiment to the deepest structure of the $\mathrm{TH}(a,d)$ programme: the $\varepsilon$-threshold ($\varepsilon = 2^{-16}$ in the CHORD Q16.16 arithmetic) is an engineering parameter, but the *physical* threshold below which Fisher information is inaccessible may be set by quantum gravity. If spacetime fluctuations impose a minimum phase noise in any interferometer, then the $\ker(F)$ sector has a physical floor — a gravitational $\varepsilon$ that no measurement can penetrate.

---

## Part V · The Mach–Zehnder Interferometer: The Slit Abstracted

### V.1 Architecture

The Mach–Zehnder interferometer (Mach 1892; Zehnder 1891) replaces the continuous slit geometry with discrete beam splitters. A photon enters at BS1, takes one of two paths, and recombines at BS2 before detection. It is the double-slit experiment with its geometry laid bare.

### V.2 The Beam Splitter as Rank-One Event

A 50:50 beam splitter transforms $|1\rangle \to \frac{1}{\sqrt{2}}(|U\rangle + |L\rangle)$: a rank-one modification of the Fisher matrix, moving the which-path direction between $\mathrm{col}(F)$ and $\ker(F)$ depending on the measurement basis. Inserting a which-way detector in one arm is a Sherman–Morrison update:

$$F_{\mathrm{detected}} = F_{\mathrm{interferometer}} + uu^T$$

The algebraic operation is identical to a KAM torus breakdown removing one invariant direction, a Nye–Berry pair annihilation removing one topological charge, a Zeeman perturbation splitting one spectral line, and — at gravitational scale — a binary black hole merger annihilating two event horizons.

### V.3 A Thought Experiment: The Forking Path

Imagine a letter sent through a postal system with two routes — north and south. If no one records which route it takes, the letter arrives with "interference" — its arrival time is the superposition of both route durations, producing a probability pattern that depends on the difference between the two routes. If a clerk stamps the letter at one junction, the route is known, and the arrival time is sharp — no interference. The clerk's stamp is the which-way detector: a Sherman–Morrison perturbation that transfers Fisher information from the phase sector to the path sector.

Now imagine the stamp can be erased before the letter arrives. The interference returns. The information was always in the correlation between the letter and the clerk's ledger; erasing the ledger restores the phase coherence. This is the quantum eraser in postal form.

---

## Part VI · The Bohr–Einstein Debate as Fisher Complementarity

In 1927, Einstein proposed that if the slit plate were mounted on a spring, the photon's recoil would reveal which slit it traversed — providing path information without disturbing the interference pattern. Bohr countered: measuring the recoil with precision $\Delta p < h/d$ introduces position uncertainty $\Delta x > d/2$ in the slit plate, washing out the fringes. The complementarity is absolute.

For 98 years, this debate was settled philosophically but not experimentally — until Ketterle's 2025 experiment. Using single atoms as slits and removing the spring entirely, the MIT team showed: the complementarity is enforced by *entanglement*, not by mechanical disturbance. The atom's "fuzziness" — its position uncertainty — controls how much which-way information leaks into the photon-atom entanglement. The spring is irrelevant. The Fisher information budget at the boundary is what matters.

$\mathcal{V}^2 + \mathcal{D}^2 \leq 1$ is the $\mathrm{col}(F)/\ker(F)$ complementarity theorem. Einstein's proposal to simultaneously extract both $\mathcal{V}$ and $\mathcal{D}$ violates this bound. Bohr's response — correctly — identifies the mechanism: any coupling that provides path information necessarily entangles the photon with the slit, transferring Fisher information from the interference sector to the path sector. The total budget is conserved; the allocation shifts.

---

## Part VII · The Aharonov–Bohm Phase: Topology at the Boundary

Aharonov and Bohm (*Phys. Rev.* **115**, 485, 1959) predicted that an electron passing around a solenoid — through a region where the electromagnetic field is exactly zero but the vector potential $\mathbf{A}$ is nonzero — acquires a phase:

$$\Delta\phi = \frac{e}{\hbar}\oint \mathbf{A}\cdot d\mathbf{l} = \frac{e\Phi_B}{\hbar}$$

Observable as a shift of interference fringes, even though no force acts on the electron.

The Aharonov–Bohm effect is a topological phase winding on the conditional independence boundary. The solenoid creates a $\ker(F)$ region — the magnetic field is screened inside; the electron never encounters it. But the topology of the boundary (the multiply connected path around the solenoid) encodes a winding number that shifts the entire fringe pattern. This is the gauge-theoretic instance of Nye–Berry topological charge: $(e/h)\oint \mathbf{A}\cdot d\mathbf{l}$ plays the role of the optical winding number $(2\pi)^{-1}\oint \nabla\arg(\psi)\cdot d\mathbf{l}$.

Both shift the shadow-light partition without exerting force. Both are conserved topological invariants on the conditional independence boundary.

---

## Part VIII · Ten Formal Correspondences

**1 — The Slit IS a Markov Blanket.** The Huygens–Fresnel principle is the conditional independence condition. By Chentsov (1972), the boundary carries Fisher–Rao geometry.

**2 — Bright Fringes ARE $\mathrm{col}(F)$.** Directions where Fisher information about the phase difference $\delta = k(r_1 - r_2)$ is maximal.

**3 — Dark Fringes ARE Nye–Berry Phase Singularities.** At each dark fringe, $|\psi| = 0$ and $\arg(\psi)$ winds by $2\pi$. These are $\ker(F)$ in its most literal form — rank-zero points of the local Fisher matrix.

**4 — The Beam Splitter IS a Sherman–Morrison Update.** Each beam splitter performs a rank-one modification. The full Mach–Zehnder is two sequential rank-one events.

**5 — Which-Way Detection IS Fisher Information Transfer.** The Englert inequality $\mathcal{V}^2 + \mathcal{D}^2 \leq 1$ is the information budget constraint. Confirmed by Ketterle (2025) to be enforced by entanglement, not mechanical disturbance.

**6 — The Quantum Eraser IS Rank Restoration.** Erasing which-way information reverses the Sherman–Morrison update. The delayed-choice variant shows the decomposition is defined by entanglement structure, not temporal ordering.

**7 — The Temporal Double Slit IS the Fourier Dual Boundary.** Spatial slits produce momentum-domain interference; temporal slits produce energy-domain interference. Both are conditional independence boundaries in conjugate phase-space variables.

**8 — The Aharonov–Bohm Phase IS Topological Winding on the Boundary.** A gauge-theoretic winding number that shifts fringes without exerting force — the electromagnetic instance of Nye–Berry charge.

**9 — The Gravitational Phase (COW) IS a Rank-One Fisher Perturbation.** The gravitational potential adds a path-dependent phase to the interferometer — a single outer product $uu^T$ processed by Sherman–Morrison, the gravitational analogue of the Zeeman effect.

**10 — Closing One Slit IS the $d = 0$ Degeneration.** When one slit is blocked, interference vanishes, the pattern degenerates to a single diffraction envelope, and $G_{\mathrm{coord}} = 0$. This is the double-slit analogue of the $\mathrm{TH}(a,d)$ factorization at $d = 0$: three decoupled lines, no group law, no coordination.

---

## Part IX · Predictions

### P1 — Gravitational Decoherence Threshold in Nanodiamond Interferometry

If gravity acts as an involuntary which-way detector above a critical mass, the fringe visibility in the Folman nanodiamond interferometer should decrease as $\mathcal{V}(m) \sim \exp(-m^2/m_P^2 \cdot t/t_{\mathrm{coh}})$ where $m_P$ is the Planck mass and $t_{\mathrm{coh}}$ is the coherence time. The $\mathrm{TH}(a,d)$ framework predicts that this decoherence is a Sherman–Morrison update by the gravitational self-energy: the spacetime geometry on each side of the superposition carries which-path Fisher information, collapsing interference. **Testable with the Folman programme within 5–10 years.**

### P2 — Temporal Phase Singularities in the Tirole–Sapienza Geometry

The dark fringes of the temporal double-slit experiment (frequency-domain destructive interference) should contain phase singularities in the time-frequency plane with the same Nye–Berry topology as spatial dark fringes. The singularity density as a function of temporal slit separation should match Berry's random wave prediction. **Testable with current ITO temporal slit technology.**

### P3 — Superluminal Dark-Fringe Motion Under Slit Modulation

If the spatial slit separation $d$ is modulated in time, the dark fringes move across the screen. Near the moment when two dark fringes of opposite topological charge merge, Berry's $v \propto t^{-1/2}$ velocity divergence should be observable — connecting Young's experiment directly to the Bucher–Kaminer superluminal dark-point result. **Testable with kHz slit modulation and high-speed cameras.**

### P4 — Fisher Information Scaling at the Ketterle Boundary

The quantum Fisher information about the photon's phase in the MIT experiment should scale as $\mathcal{F}_Q(\phi) \propto \exp(-\sigma_x^2/\sigma_0^2)$ where $\sigma_x$ is the atomic fuzziness. This Gaussian decay is a direct prediction of the conditional independence boundary framework. **Testable with existing MIT data.**

### P5 — Graviton Signature in Interferometric Fringe Shift

If Schützhold's proposal is realized, the absorption or emission of a single graviton should produce a frequency shift in the interferometer fringe pattern of order $\Delta\omega \sim \omega_{\mathrm{gw}} \cdot (E_{\mathrm{laser}}/E_{\mathrm{Planck}})$, detectable with entangled photon pairs. This would be the first observation of a gravitational conditional independence boundary at the quantum level — the graviton passing through both arms of the interferometer and interfering with itself. **Requires next-generation gravitational wave detectors.**

---

## Part X · The Aperture as Origin

Every conditional independence boundary in the $\mathrm{TH}(a,d)$ programme is an aperture — a fenestra through which information is projected. Young's card with two pinholes is the simplest fenestra. The event horizon of a black hole is the most extreme. Between them lies the full hierarchy of physics:

| Fenestra | What passes through | Interference domain | $\ker(F)$ |
|---|---|---|---|
| Young's double slit | Photons | Spatial fringes | Dark fringes (phase singularities) |
| Crystal lattice (Davisson–Germer) | Electrons | Bragg spots | Dark regions between spots |
| Temporal slit (Tirole–Sapienza) | Photons | Frequency fringes | Spectral zeros |
| Mach–Zehnder beam splitters | Photons | Port intensities | Destructive interference port |
| COW neutron interferometer | Neutrons | Gravitational phase shift | — |
| Nanodiamond SGI (Folman) | Nanodiamonds | Spatial fringes (predicted) | Gravitational decoherence |
| Event horizon | Hawking radiation | Thermal spectrum | Interior (causally screened) |
| Cosmological horizon | CMB photons | Power spectrum | Beyond-horizon modes |

The fenestra creates structure. Without it, the field is uniform — energy everywhere, information nowhere. With it, the field acquires pattern: bright fringes carrying energy and information in $\mathrm{col}(F)$, dark fringes carrying topological charge in $\ker(F)$. The pattern encodes the geometry of the aperture through the Fisher–Rao metric on its boundary. The Englert inequality bounds the total information. The Sherman–Morrison formula governs rank-one transitions.

Two slits are needed for interference. Two strands are needed for the double helix of $\mathrm{TH}(a,d)$. Two entangled systems are needed for an ER bridge. One slit — one strand — one system — produces diffraction but not interference, structure but not coordination, energy but not information. The coupling between the two paths, like the coupling parameter $d$ in $\mathrm{TH}(a,d)$, is what creates the group law, the pattern, the physics.

---

## References

Aharonov, Y. and Bohm, D. "Significance of Electromagnetic Potentials in the Quantum Theory." *Phys. Rev.* **115**, 485–491, 1959.

Arndt, M. et al. "Wave-Particle Duality of C$_{60}$ Molecules." *Nature* **401**, 680–682, 1999.

Berry, M. V. "Disruption of Wavefronts: Statistics of Dislocations in Incoherent Gaussian Random Waves." *J. Phys. A* **11**, 27–37, 1978.

Bucher, T., Gorlach, A., et al. "Superluminal Correlations in Ensembles of Optical Phase Singularities." *Nature* **651**, 920–926, 2026.

Carnal, O. and Mlynek, J. "Young's Double Slit Experiment with Atoms: A Simple Atom Interferometer." *Phys. Rev. Lett.* **66**, 2689–2692, 1991.

Chentsov, N. N. *Statistical Decision Rules and Optimal Inference*. Nauka, 1972. (AMS Translations, Vol. 53, 1982.)

Colella, R., Overhauser, A. W., and Werner, S. A. "Observation of Gravitationally Induced Quantum Interference." *Phys. Rev. Lett.* **34**, 1472–1474, 1975.

Davisson, C. J. and Germer, L. H. "Diffraction of Electrons by a Crystal of Nickel." *Phys. Rev.* **30**, 705–740, 1927.

de Broglie, L. "Recherches sur la théorie des Quanta." *Ann. Phys.* **10**(3), 22–128, 1925.

Dobkowski, O. et al. "Observation of the Quantum Equivalence Principle for Matter Waves." arXiv:2502.14535, 2025.

Englert, B.-G. "Fringe Visibility and Which-Way Information: An Inequality." *Phys. Rev. Lett.* **77**, 2154–2157, 1996.

Fedoseev, V., Lin, H., Lu, Y.-K., Lee, Y. K., Lyu, J., and Ketterle, W. "Coherent and Incoherent Light Scattering by Single-Atom Wave Packets." *Phys. Rev. Lett.*, 2025.

Fein, Y. Y. et al. "Quantum Superposition of Molecules Beyond 25 kDa." *Nature Physics* **15**, 1242–1245, 2019.

Feynman, R. P., Leighton, R. B., and Sands, M. *The Feynman Lectures on Physics*, Vol. III. Addison-Wesley, 1965.

Folman, R. et al. "Quantum Control of Nitrogen-Vacancy Spin in Diamonds: Towards Matter-Wave Interferometry with Massive Objects." arXiv:2508.15504, 2025.

Kim, Y.-H. et al. "A Delayed 'Choice' Quantum Eraser." *Phys. Rev. Lett.* **84**, 1–5, 2000.

Maldacena, J. and Susskind, L. "Cool Horizons for Entangled Black Holes." *Fortschritte der Physik* **61**, 781–811, 2013.

Moshinsky, M. "Diffraction in Time." *Phys. Rev.* **88**, 625–631, 1952.

Nagata, Y. et al. "Observation of Positronium Diffraction." *Nature Communications*, 2025.

Nye, J. F. and Berry, M. V. "Dislocations in Wave Trains." *Proc. Roy. Soc. Lond. A* **336**, 165–190, 1974.

Schützhold, R. "Stimulated Emission or Absorption of Gravitons by Light." *Phys. Rev. Lett.* **135**, 2025.

Scully, M. O., Englert, B.-G., and Walther, H. "Quantum Optical Tests of Complementarity." *Nature* **351**, 111–116, 1991.

Sharmila, B., Vermeulen, S. M., and Datta, A. "Signatures of Correlation of Spacetime Fluctuations in Laser Interferometers." *Nature Communications* **17**, 2025.

Taira, Y. et al. "Time Domain Double Slit Interference of Electron Produced by XUV Synchrotron Radiation." *Scientific Reports* **13**, 2023.

Thomson, G. P. and Reid, A. "Diffraction of Cathode Rays by a Thin Film." *Nature* **119**, 890, 1927.

Tirole, R., Vezzoli, S., Galiffi, E., Robertson, I., Maurice, D., Tilmann, B., Maier, S. A., Pendry, J. B., and Sapienza, R. "Double-Slit Time Diffraction at Optical Frequencies." *Nature Physics* **19**, 999–1002, 2023.

Woodbury, M. A. "Inverting Modified Matrices." Memorandum Report 42, Statistical Research Group, Princeton University, 1950.

Young, T. "The Bakerian Lecture: On the Theory of Light and Colours." *Phil. Trans. Roy. Soc.* **92**, 12–48, 1802.

Zhao, X. et al. "Factorization Dynamics Between Quantum Fisher Information and Quantum Coherence." *Science Advances* **11**, eadv8132, 2025.

Zhu, H. "Information Complementarity: A New Paradigm for Decoding Quantum Incompatibility." *Scientific Reports* **5**, 14317, 2015.

---

*ERI Labs · Eric Ren · Jersey City, New Jersey · github.com/ericrenone · April 2026*

Young cut two holes in a card and saw waves. Davisson and Germer bounced electrons off nickel and saw waves. Thomson sent electrons through foil and saw waves. Carnal and Mlynek sent helium atoms through fabricated slits and saw waves. Arndt sent buckyballs and saw waves. Nagata sent positronium — matter and antimatter bound together, existing for 142 nanoseconds — and saw waves. Ketterle built the smallest slits in nature — two individual atoms — and saw the complementarity that Bohr promised and Einstein doubted. Tirole and Sapienza cut slits not in space but in time — femtosecond windows — and saw waves in the frequency spectrum. Folman is preparing to send nanodiamonds and ask whether gravity prevents the wave. Schützhold has proposed sending light and asking whether gravity itself is a wave.

Every aperture is a conditional independence boundary. Every boundary carries the Fisher–Rao metric. Every dark fringe is a phase singularity. Every which-way detector is a Sherman–Morrison update. Every eraser is a rank restoration. Every closed slit is a $d = 0$ degeneration.

The fenestra was always the same fenestra — from Young's card to the event horizon. What changes is what passes through, and what we learn when it does.
