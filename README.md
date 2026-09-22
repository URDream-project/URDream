



















# URDream: Agentic Single Image Generation of Simulation-Ready Articulated Assets

⭐ Star this repository to follow upcoming updates, including the technical report and code release. We welcome feedback, discussions, and contributions from the community!

## 🎬 Demo Videos

### Part 1

https://github.com/user-attachments/assets/9a9d83ba-62b6-4544-8fd2-375003c0a12d

### Part 2

https://github.com/user-attachments/assets/a786a318-4b98-40e8-b6fc-b37932c7dcc3

### Part 3

https://github.com/user-attachments/assets/dcd5cca3-9e22-4e3b-b891-a6ec886bc9c6


## 🚀 Introduction
**URDream** is an agentic framework for generating simulation-ready articulated 3D assets from a single image. It adaptively selects generative, parametric, or hybrid modeling according to the geometry and functional requirements of each object and its parts. An agent Harness coordinates appearance and mechanism reviews, kinematic checks, and dynamics tests, using diagnostic feedback to guide targeted repairs before delivering simulator-compatible URDF assets. Validated modeling and repair experience is retained and reused to support decisions in subsequent tasks.

## 🌟 Features

- **Adaptive Modeling**: ***URDream*** adaptively selects **generative, parametric, or hybrid modeling** based on the characteristics of each object and its parts, balancing visual fidelity, structural accuracy, and interactivity.
- **Closed-Loop Validation and Repair**: Validates joint configurations, mass, center of mass, inertia, and collision geometry through **static checks, kinematic checks, and dynamics tests**, forming a **generation–validation–diagnosis–repair** loop to produce simulation-ready assets.
- **Experience-Driven Self-Evolution**: Extracts **validated modeling and repair experience** for retrieval and reuse in subsequent tasks, supporting modeling decisions and issue resolution.


## 📋 TODO

- [x] Publish the technical blog.
- [ ] Publish the technical report before November 2026.
- [ ] Release the code before November 2026.

## 📚 Citation
``` 
@article{2026urdream,
     title = {{URDream}: Agentic Single Image Generation of Simulation-Ready Articulated Assets},
     journal = {Technical Blog},
     year = {2026}
}
``` 
