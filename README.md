## Hi, I'm Satwik

Aerospace Engineering student at VIT Bhopal building engineering software at the intersection of **aerospace, simulation, and software development**.

I'm developing individual aerospace tools now, with a long-term goal of integrating them into a **web-accessible Aerospace Engineering Suite**. Each tool is being built and validated independently before integration.

**Python · TypeScript · MATLAB · Java** — React · Numerical modelling · Simulation · Automated testing

### Aerospace Engineering Suite — in development

A growing collection of computational tools for aerospace analysis. The projects are currently independent; the unified suite is a long-term direction, not an integrated product yet.

**[Flight Performance Simulator](https://github.com/satwiksharma01/flight-performance-sim)**

Aircraft performance analysis in the browser: drag and power curves, climb, ceilings, glide, flight envelopes, turn performance, takeoff and landing, range, cruise, aircraft comparison, and sensitivity analysis.

The TypeScript physics core is cross-checked against an independent Python implementation and published references, including Cessna 172S POH data. Known discrepancies are documented rather than hidden.

[Launch the simulator](https://satwiksharma01.github.io/flight-performance-sim/) · [Review validation results](https://satwiksharma01.github.io/flight-performance-sim/validation.html) · [Engineering decisions](https://github.com/satwiksharma01/flight-performance-sim#design-notes)

**[Orbital Manoeuvre Decision Support Tool](https://github.com/satwiksharma01/orbital-manoeuvre-decision-support)**

A decision-support tool that sizes, optimises, filters, and ranks orbital transfer options against mission constraints and priorities. It compares Hohmann, plane-change, bi-elliptic, one-tangent, and Edelbaum low-thrust transfers.

The tool includes MATLAB/Simulink models, a Python cross-check, an interactive web planner, and verification against textbook benchmarks and NASA GMAT R2026a.

[Launch the web planner](https://satwiksharma01.github.io/orbital-manoeuvre-decision-support/web/) · [Review the engineering and verification](https://github.com/satwiksharma01/orbital-manoeuvre-decision-support)

### Other work

**[Frameflow](https://github.com/satwiksharma01/frameflow)** — AI-assisted video editing that keeps the timeline editable in Shotcut, with deterministic editing logic and project history.

**[Expense Tracker](https://github.com/satwiksharma01/expense-tracker)** — Java 17 command-line finance manager with budgets, recurring payments, CSV import/export, and monthly reports.

**[Finance Video Engine](https://github.com/satwiksharma01/motion-graphic-video-generator)** — Render structured finance scripts as vertical videos using React and Remotion.

### How I build

- Separate engineering models and decision logic from the interface.
- Validate calculations with tests, independent implementations, and published references where available.
- Document assumptions, known limitations, and trade-offs so results can be inspected and reproduced.

### Open-source contributions

Recent merged contributions to [OpenScreen](https://github.com/getopenscreen/openscreen):

- [Preserve audio timing during transcription extraction](https://github.com/getopenscreen/openscreen/pull/1076)
- [Preserve recorded cursor visibility in agent observations](https://github.com/getopenscreen/openscreen/pull/1075)
- [Add standard AppImage update metadata](https://github.com/getopenscreen/openscreen/pull/1072)
- [Remove the libfuse2 dependency from AppImages](https://github.com/getopenscreen/openscreen/pull/1070)

I use AI assistance in my development workflow; the linked pull requests describe the changes and validation.

<sub>Currently focused on aerospace simulation, numerical methods, and engineering software.</sub>
