---
layout: page
title: Research Overview
permalink: /research/
hide_footer: false
show_sidebar: false
---

# The Grand Challenge

<img src="/img/rsch_oct.png" align="right" width="400px"/>

Our research is motivated by the desire to expand the last frontier of aerospace engineering, represented by **hypersonic vehicles** and high-speed **VTOL aircraft**. The development of these advanced aerospace systems has been constrained by their inherent **complex multi-physics nature** and the **strong coupling among their subsystems**, including but not limited to

+ Aerodynamics/fluid dynamics, Thermodynamics, ...
+ Structural dynamics, Material response, ...
+ Flight dynamics and control, Guidance and navigation, ...
+ Propulsion system, ...
+ etc...

While there are relatively mature solutions for each single disciplinary/subsystem involved in multi-physics problems, these problems cannot be completely understood and solved without integrating the **M**ulti-**D**isciplinary tools for **A**nalyzing, **O**ptimizing, and **C**ontrolling (MDAOC) of future unconventional aircraft.  For example,

+ How does **fluid-thermal-structural interaction** (FTSI) impact the **autonomous flight** of hypersonic vehicles?  Conversely, for better autonomy how to design the vehicle for desired FTSI response?
+ How does the **unsteady aerodynamics and environmental turbulence** impact the **maneuverability and agility** of quad-rotor drones?  Conversely, how does that inform the drone design?
+ Basically, is it possible to perform a **full-stack optimization** of an engineering system, that bridges the "inner optimization" of its subsystems (e.g., aero-structural opt. of wings) and the "outer optimization" of the control and autonomy (e.g., trajectory opt. and controller design)?  This should **release the full potential** of an engineering system.

<br clear="right"/>

# Impossible Trinity of Modeling

<img src="/img/post_2109.png" align="right" width="600px"/>

The crux of integrated MDAOC is the modeling of complex multi-physics dynamics.  And this is a **"holy grail"** problem:  Is it possible to find **one** mathematical model that is
+ **Accurate to reproduce the dynamics**, that
  - Works over the entire range of operating conditions
  - Captures nonlinearities such as bifurcations and limit cycles
+ **Computationally efficient to evaluate**, that
  - Supports automatic differentiation for large-scale optimization
  - Suits for deployment on hardware and real-time computing
+ **Supports infinite-dimensional parameters**, e.g,
  - Geometrical shapes and material properties, as distributed parameters, for optimization
  - Control inputs and system states, as time-varying parameters, for autonomy

Usually, it is impossible to have all three bullets at the same time, just like the [impossible trinity](https://en.wikipedia.org/wiki/Impossible_trinity).

However, **this is what the APUS Lab aims to tackle.**

<br clear="right"/>


# Our Methodology

<img src="/img/home_sum.png" align="right" width="500"/>

In APUS Lab, we use a **closed-loop and integrated set of methods** to tackle the Grand Challenge:

#### High-Fidelity Multi-Physics
We use simulation, with experimental validation, to resolve **unknown physics**.
+ [High-Speed Fluid-Thermal-Structural Interaction on Complex Geometry](/rsch_csr/)
+ [Fluid-Thermal-Structural Interaction With High-Temperature Effects](/rsch_ht_ftsi/)
+ [Computational Framework for Hypersonic Aerothermoelasticity](/rsch_hypate/)

#### Scientific Data Analysis
We extract out **physical knowledge** from the sheer volume of multi-physics simulation data.
+ [Operator-Theoretic Analysis for Spatiotemporal Dynamics](/rsch_std/)
+ [Design of Aeroelastically Scaled Model in a Compressed Air Wind Tunnel Facility](/news_st23/#aeroelastic-scaling)
+ [Refined Hypersonic Aerothermoelastic Scaling Laws](/rsch_ate_scl/)

#### Reduced-Order Modeling
We develop ROMs for **efficient, accurate, and robust prediction** of system dynamics with the new knowledge
+ [Physics-Infused Reduced-Order Modeling](/rsch_pirom/)
+ [Geometric Deep Learning for Dynamics on Graphs](/rsch_dgn/)
+ [Fluid-Thermal-Structural Interaction Using Multi-Fidelity Multi-Variate Surrogate](/rsch_ht_ftsi/)
+ [Reduced-Order Modeling of Hypersonic Aerothermodynamics](/rsch_rom_scl/)

#### Control and Autonomy
We integrate ROMs and control & autonomy to achieve the **full-stack design optimization** of an engineering system.
+ Rapid Aeroservoelastic Design of Morphing Unmanned Aerial Vehicles (Details coming soon)
+ [Enhanced Control for eVTOL Vehicles Using Higher-Fidelity Aerodynamic Model](/news_st23/#landing-of-evtol)
+ [Control Co-Design of Hypersonic Vehicles](/rsch_hyp_ccd/)

<br clear="right"/>
