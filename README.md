# Slalom Manual Control – Interactive Control Systems Lab

Interactive browser-based slalom skiing simulation for teaching manual control of dynamical systems.

🔗 **Launch the simulation:**  
https://BoBernhardsson.github.io/slalom-control-game/

---

## 🎯 Purpose

This tool is designed to help students *feel* the effect of different plant dynamics through manual control.

Instead of tuning controllers, the student directly applies the control input `u` and experiences how:

- Integrators drift
- Lag systems feel sluggish
- Second-order systems oscillate
- Time delay degrades performance
- Non-minimum phase zeros create counterintuitive motion

The goal is intuitive understanding of:

- Transfer functions
- Poles and zeros
- Stability and damping
- Control effort vs. performance
- Disturbance rejection

---

## 🧠 How It Works

The skier moves laterally according to a selected plant model:

\[
x(s) = G(s) \, u(s)
\]

Different selectable systems include:

- Integrator  
- Integrator + first-order lag  
- Integrator + second-order resonance  
- Integrator + time delay  
- Integrator + right-half-plane zero  

Wind acts as a piecewise-constant disturbance that changes randomly.

---

## 🎮 Controls

- **← / →** or **A / D** — steer  
- **Space** — reset steering input  
- **Slider** — direct control input  
- **Slope selector** — downhill speed / difficulty  
- **Wind selector** — disturbance intensity  

---

## 🧪 Teaching Use

This simulation is intended for:

- Control Systems (undergraduate or master level)
- Introduction to dynamical systems
- Intuition building before formal controller design

Possible exercises:

- Compare integrator vs. lag behavior  
- Observe oscillations for low damping  
- Investigate effect of delay  
- Explore non-minimum phase response  
- Study disturbance rejection under wind  

---

## 🛠 Technical Details

- Single-file HTML + JavaScript
- No external dependencies
- Runs entirely in the browser
- No installation required

---

## 📚 License

Educational use encouraged.  
Modify freely for teaching purposes.
