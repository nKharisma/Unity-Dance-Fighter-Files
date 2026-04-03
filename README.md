# Unity-Dance-Fighter-Files

## Combo Finite State Machine

Written by me: SeNiah McField

This repository highlights the core Combat Finite State Machine and Combo System I developed for a collaborative Unity 2D fighter project at the University of Central Florida called Dance Fighter. While the system began with a foundational tutorial for basic state transitions, I heavily refactored the architecture to move away from rigid, hard-coded inputs. I transitioned the logic into an event-driven framework that separates player input from the combat states, allowing for a much cleaner and more scalable foundation.

To improve the overall game feel, I replaced basic click-tracking with a robust Buffering System. This allows the engine to intelligently capture and sequence different attack types during active animation windows, rewarding intentional timing rather than button mashing. By moving toward a modular structure, I ensured that the combat lifecycle is performant and easy to iterate upon. This project represents a significant milestone in my growth as a gameplay programmer, as I re-engineered our old combo system into this new one.