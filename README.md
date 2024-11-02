# Spin 1/2 Elastic Solid Simulation

This project simulates the behavior of a **spin-1/2 particle** in an elastic solid. Using quaternions, the simulation demonstrates the rotational properties that require a full 720-degree rotation to return to the original state, a phenomenon often illustrated with the **Belt Trick**. This project visualizes the non-trivial topology associated with spinors in quantum mechanics.

## Table of Contents
- [Overview](#overview)
- [Controls](#controls)
- [UI Elements](#ui-elements)
- [Mathematical Concepts](#mathematical-concepts)
- [References](#references)

## Overview

This simulation provides a visualization of the **spin-1/2** system, where a particle exhibits unique rotational properties. By choosing between **Spin 1/2** and **Belt Trick** modes, users can explore how a 720-degree rotation is required to return a spinor to its original configuration. This concept is essential in understanding quantum mechanics and the behavior of particles with half-integer spin.

## Controls

The GUI provides various controls to customize the simulation experience:
- **Mode**: Selects between "Spin 1/2" and "Belt Trick" modes.
- **Kernel Function**: Selects the type of kernel function applied ("Original" or "Ring").
- **Max Winding**: Sets the maximum rotation angle for the kernel (in degrees).
- **Rotation Speed**: Controls the rotation speed of the system.
- **Auto Rotate**: Toggles automatic phase increment for continuous rotation.
- **Phase**: Manual control over the phase angle.
- **Number of Markers**: Sets the number of markers in the simulation.
- **Decay Power**: Adjusts the decay rate of the kernel function with distance.
- **Shell Radius**: Specifies the radius for the ring-shaped kernel function.
- **Number of Layers**: Sets the number of grid layers (planes) in the simulation.

## UI Elements

The visualization includes several interactive elements:
- **Central Sphere**: Represents the origin or the spinor itself.
- **Grid Layers**: Planes composed of grids that undergo transformations to visualize spinor rotation.
- **Arrows**: Represent vector fields, visualizing rotation and orientation.
- **Markers**: Points that trace paths to show rotation effects over time.
- **Belt (in Belt Trick mode)**: A series of cubes forming a belt to demonstrate the 720-degree rotation property.

## Mathematical Concepts

This simulation incorporates several mathematical concepts:
- **Quaternions**: Used to represent 3D rotations. For more details, see [Quaternion on Wikipedia](https://en.wikipedia.org/wiki/Quaternion).
- **Belt Trick**: Illustrates that a 360-degree rotation does not return a spinor to its original state, but a 720-degree rotation does. Learn more at [Plate Trick on Wikipedia](https://en.wikipedia.org/wiki/Plate_trick).
- **Spinors**: Mathematical objects in quantum mechanics that describe the state of particles with half-integer spin. Read about spinors on [Wikipedia](https://en.wikipedia.org/wiki/Spinor).
- **Kernel Functions**: Spatially varying functions applied to control rotation based on distance from the origin.

## References

- [Quaternion](https://en.wikipedia.org/wiki/Quaternion)
- [Plate Trick (Belt Trick)](https://en.wikipedia.org/wiki/Plate_trick)
- [Spinor](https://en.wikipedia.org/wiki/Spinor)

## License

This project is licensed under the MIT License.
