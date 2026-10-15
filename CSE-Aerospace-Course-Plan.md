# CSE Aerospace Course - Course of Study

Curriculum v1.1, adopted October 15, 2026. This is an independent multiyear learning sequence, not an accredited degree or a promise of PhD equivalence.

## Purpose

Build mathematical reasoning and scientific computation from elementary ideas, with a growing specialization in general aerospace knowledge, CFD, compressible flow, hypersonics, high-temperature gas dynamics, aerothermodynamics, and aero-optics. Existing professional expertise provides context, not permission to skip prerequisites.

## Course operation

Use an ordered lesson sequence, not calendar-based difficulty escalation. Three new lessons, one consolidation, then one review/checkpoint in each five-lesson cycle. Early lessons take 15-30 minutes; later lessons normally 30-90. Reading time is separate. Each lesson has one primary objective, named prerequisites, a short explanation, a separate worked example, unsolved practice, interpretation, checks, and an optional stretch using taught methods.

Only use computational methods already introduced unless that method is the explicit lesson objective. Supplied physical relations must be labeled with assumptions. Supply small data inline. Avoid hiding new methods inside helper functions. Keep problem solutions and completed exercise code out of starters.

Maintain two independent statuses: assigned and user-completed. Generated artifacts never establish mastery. Checkpoints ask the learner to explain and apply concepts; do not invent scores or promote based on elapsed time. Continue the ordered sequence if no feedback arrives, include retrieval practice, and insert remediation when the user reports difficulty.

## Long-term progression

Year 1: introductory mathematics, computing and aerospace exposure. Year 2: undergraduate analytical depth in calculus, linear algebra, ODEs, mechanics, thermodynamics, fluids and probability. Year 3: numerical analysis and CFD from scalar models to Euler/Navier-Stokes. Year 4: advanced compressible flow, hypersonics, viscous interactions and heating. Year 5: thermochemistry, reacting/nonequilibrium flow, transport, radiation foundations, and optical propagation. Year 6+: literature reproduction, HPC, uncertainty and focused research. These are adjustable planning bands, not fixed deadlines.

## Year 1 - twelve four-week units

48 teaching weeks plus four flexible weeks for review, breaks, remediation and capstone completion. Each unit has approximately 20 lessons. Later units are previews supported by supplied models; full analytical mastery belongs to later years.

### Unit 1: Quantities and computation (weeks 1-4)

Content: Arithmetic, variables, units, functions, tables and graphs.

Outcome: Evaluate and explain a computation; distinguish a unit from a numerical value.

Aerospace connection: Speed, time, distance, and a fictional flight segment.

Entry: satisfactory practice of the preceding unit, with a diagnostic and targeted review before any unfamiliar prerequisite.

### Unit 2: Algebra and algorithms (weeks 5-8)

Content: Equations, inequalities, powers, logarithms; comparisons, loops and branching.

Outcome: Rearrange elementary equations and implement a transparent search.

Aerospace connection: Supplied atmosphere relations and operating limits.

Entry: satisfactory practice of the preceding unit, with a diagnostic and targeted review before any unfamiliar prerequisite.

### Unit 3: Vectors and geometry (weeks 9-12)

Content: Coordinates, trigonometry, vector components, dot products, matrices as transformations.

Outcome: Resolve and rotate a force; check magnitudes and coordinate conventions.

Aerospace connection: Lift, drag, velocity and flight angles.

Entry: satisfactory practice of the preceding unit, with a diagnostic and targeted review before any unfamiliar prerequisite.

### Unit 4: Change and local approximation (weeks 13-16)

Content: Slopes, limits, derivatives, finite differences, introductory Taylor approximation.

Outcome: Connect a derivative to a local linear model and a computational estimate.

Aerospace connection: Acceleration and temperature gradients.

Entry: satisfactory practice of the preceding unit, with a diagnostic and targeted review before any unfamiliar prerequisite.

### Unit 5: Accumulation and integration (weeks 17-20)

Content: Area, sums, integrals, rectangle and trapezoid rules.

Outcome: Compute an accumulated quantity and interpret units.

Aerospace connection: Impulse, heat load, optical path as a future application.

Entry: satisfactory practice of the preceding unit, with a diagnostic and targeted review before any unfamiliar prerequisite.

### Unit 6: Linear systems and reliability (weeks 21-24)

Content: Simultaneous equations, elimination, residuals, representation and conditioning.

Outcome: Solve a small balance and separate residual from sensitivity.

Aerospace connection: Two-component engineering balances.

Entry: satisfactory practice of the preceding unit, with a diagnostic and targeted review before any unfamiliar prerequisite.

### Unit 7: Dynamics and ODEs (weeks 25-28)

Content: Initial conditions, rates, forward Euler, analytical elementary solutions.

Outcome: Construct and integrate one scalar initial-value model.

Aerospace connection: Lumped thermal response and prescribed-force motion.

Entry: satisfactory practice of the preceding unit, with a diagnostic and targeted review before any unfamiliar prerequisite.

### Unit 8: Conservation and thermodynamics (weeks 29-32)

Content: Control volumes, mass and energy, ideal gas, dimensional groups.

Outcome: Account consistently for storage and fluxes in simple systems.

Aerospace connection: Tank filling, gas state, and steady-flow energy.

Entry: satisfactory practice of the preceding unit, with a diagnostic and targeted review before any unfamiliar prerequisite.

### Unit 9: Fluid and compressible-flow introduction (weeks 33-36)

Content: Pressure, viscosity, sound speed, Mach number, isentropic and shock relations.

Outcome: Use supplied relations with assumptions; solve elementary algebraic flow problems.

Aerospace connection: Nozzles and normal shocks; no Euler solver yet.

Entry: satisfactory practice of the preceding unit, with a diagnostic and targeted review before any unfamiliar prerequisite.

### Unit 10: Fields and elementary PDEs (weeks 37-40)

Content: Fields, boundary conditions, gradients, diffusion and transport concepts.

Outcome: Implement a small 1D conduction discretization after deriving its balance.

Aerospace connection: Wall conduction and temperature distributions.

Entry: satisfactory practice of the preceding unit, with a diagnostic and targeted review before any unfamiliar prerequisite.

### Unit 11: High-speed thermal physics (weeks 41-44)

Content: Energy scales, stagnation concepts, property tables, variable heat capacity.

Outcome: Compare a calorically perfect model with a supplied variable-property model.

Aerospace connection: Hypersonic heating, dissociation and nonequilibrium as conceptual previews.

Entry: satisfactory practice of the preceding unit, with a diagnostic and targeted review before any unfamiliar prerequisite.

### Unit 12: Optics, probability and synthesis (weeks 45-48)

Content: Refractive index, line integration, sample mean and variance, basic uncertainty.

Outcome: Compute optical path from a supplied density field and describe uncertainty.

Aerospace connection: Aero-optics and a small integrated capstone.

Entry: satisfactory practice of the preceding unit, with a diagnostic and targeted review before any unfamiliar prerequisite.

## Orientation block - precedes the eight-week sequence

1. Notebook workflow and reproducibility

2. Mathematical statements and comparisons

3. Quantities, symbols and units

4. Review: describe a simple computational question

The four orientation lessons are an introductory block. The established five-lesson cycles resume at Lesson 5; weeks below describe learning blocks, not fixed calendar weeks.

## First eight weeks after orientation - ordered lesson plan

### Week 1

5. Expressions and order of operations

6. Units and dimensional consistency

7. Variables and named quantities

8. Consolidation: speed-time-distance

9. Review: explain and check a calculation

### Week 2

10. Functions as input-output rules

11. Tables of function values

12. Graphs, axes and slope

13. Consolidation: tabulate and plot a function

14. Review: quantities, functions and graphs

### Week 3

15. Ratios and proportionality

16. Percent changes and reference values

17. Scientific notation and powers of ten

18. Consolidation: compare two flight segments

19. Review: scaling and meaningful comparisons

### Week 4

20. Input domains and physical constraints

21. Python comparisons and Boolean values

22. Simple conditional decisions

23. Consolidation: a unit-aware flight calculator

24. Unit 1 checkpoint and remediation

### Week 5

25. Equality and solving one-step equations

26. Inverse operations and two-step equations

27. Rearranging formulas with units

28. Consolidation: solve for time or speed

29. Review: substitute solutions back

### Week 6

30. Inequalities and intervals

31. Absolute value and distance

32. Loops as repeated evaluation

33. Consolidation: search a finite table

34. Review: what a search establishes

### Week 7

35. Integer powers and exponential functions

36. Logarithms as inverse functions

37. A supplied exponential atmosphere relation

38. Consolidation: interpret a scale height

39. Review: assumptions and domains

### Week 8

40. Numerical representation and rounding

41. Error relative to a declared reference

42. Bounded search for an intersection

43. Consolidation: compare algebraic and searched results

44. Unit 2 checkpoint and remediation

## Recurring knowledge threads

General aerospace: disciplines, aircraft/spacecraft systems, force/moment conventions, flight regimes, propulsion families, experiments and modeling assumptions. Introduce concepts in short sidebars without requiring untaught calculations.

Thermal thread: quantities -> heat load -> lumped ODE -> conduction -> conjugate transfer -> high-speed heating. Compressible thread: gas state -> sound speed/Mach -> nozzle/shock relations -> characteristics -> Euler -> reacting flow. Optical thread: refractive index -> line integral -> wavefront statistics -> ray deflection -> unsteady CFD density -> propagation.

## Deliverable contract

Every assigned lesson must deliver BOTH a complete clickable-reference PDF and a separate downloadable template-based YYYYMMDD-short-title.ipynb. State lesson ID, exact filename, objective, prerequisites and estimated duration in the response. The notebook uses the public template raw metadata and alternating explanation/implementation structure. Validate notebook JSON and code syntax, clear outputs, render/inspect PDFs, and persist both files.

A short current-source engineering brief remains supplementary and never drives the exercise ahead of its prerequisites. Give 1-3 meaningful verified developments with dates and technical context; if none are new, say so instead of recycling. Select an accessible reading at the lesson level; advanced research papers are optional horizon reading, with full citation and a specific learning focus. Do not require advanced papers to complete an elementary lesson.

## Rebuild and continuity

Thirteen dated assignments from September 29 through October 15 are rebuilt as Lessons 1-13. October 5 is now Lesson 5; previous v1.0 IDs shift by four. Original advanced files are preserved as an optional archive and are no longer the active sequence. Rebuilt dates are historical labels; replacement PDFs explicitly identify the October 15 rebuild and do not fabricate historical news. The next scheduled assignment is Lesson 14: Review - quantities, functions and graphs.

## Open references

OpenStax Algebra and Trigonometry 2e: https://openstax.org/details/books/algebra-and-trigonometry-2e
OpenStax Calculus Volume 1: https://openstax.org/details/books/calculus-volume-1
Python introductory tutorial: https://docs.python.org/3/tutorial/introduction.html
NASA Glenn Beginner's Guide to Aeronautics: https://www.grc.nasa.gov/www/k-12/airplane/
Notebook template: https://github.com/josh-fowler-hub/daily-learning/blob/main/problem-template.ipynb
