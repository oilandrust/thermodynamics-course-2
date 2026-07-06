# Heat Engines and Carnot Cycle

A **heat engine** converts thermal energy into work by operating between a hot reservoir ($T_H$) and a cold reservoir ($T_C$).

## Thermal efficiency

$$
\eta = \frac{W_\text{net}}{Q_H} = 1 - \frac{Q_C}{Q_H}
$$

where $Q_H$ is heat absorbed from the hot reservoir and $Q_C$ is heat rejected to the cold reservoir.

![Schematic of a heat engine](attachments/heat-engine.svg)
## Carnot cycle

The **Carnot cycle** consists of two isotherms and two adiabats. It is the most efficient cycle between two given temperatures.

![Carnot cycle on a T–s diagram](attachments/carnot-cycle.svg)

For a reversible Carnot engine:

$$
\eta_\text{Carnot} = 1 - \frac{T_C}{T_H}
$$

> Temperatures must be expressed on an absolute scale (kelvin).

## Proof sketch (entropy)

Because the cycle is reversible, $\Delta S_\text{cycle} = 0$. Heat transfer at the isotherms gives:

$$
\frac{Q_H}{T_H} = \frac{Q_C}{T_C}
$$

Substitute into the efficiency definition to recover $\eta_\text{Carnot}$. Details rely on [[Second Law and Entropy|entropy]] as a state function.

## Real engines

Real devices (Otto, Diesel, Rankine) fall short of Carnot efficiency because of irreversibilities: friction, finite $\Delta T$ during heat transfer, and rapid combustion.

## Prerequisites

- [[First Law of Thermodynamics]] — energy balance on the working fluid
- [[Ideal Gas Law]] — common model for the working fluid in examples
- [[Second Law and Entropy]] — why $\eta < 1$

Return to [[Thermodynamics Course]].
