# Esau Engineering

Open-source engineering software for the browser: CAD, simulation, and tools for 3D printing.

Our work rests on **remus**, an exact B-Rep geometry kernel written in Rust and compiled to WebAssembly. The apps built on it run locally in your browser. They need no installs or license servers, and your data stays on your machine.

## Projects

| Project | What it does | Stack |
| --- | --- | --- |
| [**OpenZCAD**](https://github.com/esaueng/OpenZCAD) | Parametric CAD in the browser: exact B-Rep solids, replayable feature history, direct editing on the model, STEP import and export. Runs locally, with optional cloud projects and live collaboration. | TypeScript · WASM |
| [**remus**](https://github.com/esaueng/remus) | Exact B-Rep solid modeling kernel for Rust and WebAssembly. Booleans keep analytic surfaces intact. Also does blends, sweeps, healing, and STEP exchange. | Rust · WASM |
| [**OpenFEA**](https://github.com/esaueng/OpenFEA) | Browser-based CAD and finite element analysis that runs locally, with static, dynamic, modal, and thermal studies. | TypeScript |
| [**OpenLattice3D**](https://github.com/esaueng/OpenLattice3D) | Turns STL meshes into 3D-printable lattice structures. | TypeScript |
| [**glimpse**](https://github.com/esaueng/glimpse) | Private analytics for our apps, built on Cloudflare Workers and D1. | TypeScript |
| [**isitjunk**](https://github.com/esaueng/isitjunk) | Forward a suspicious email and get an AI-powered assessment of whether it's junk. | TypeScript |

## How we build

- **Correct geometry first.** Solids are exact B-Reps, and models round-trip through STEP so your work isn't locked in.
- **Local-first.** Your models live on your machine, and the cloud is optional.
- **Open source.** Most projects are Apache-2.0. Issues and pull requests are welcome.

## Contact

📫 [info@esaueng.com](mailto:info@esaueng.com)
