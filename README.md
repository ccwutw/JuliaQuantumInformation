# Julia Quantum Computing Projects

A curated list of [Julia](https://julialang.org/) packages, projects, and organizations focused on quantum information science, quantum computing, and related fields like condensed matter physics.

## Contributing

To add a project to this list:
- Submit a [pull request](https://github.com/jlapeyre/JuliaQuantumInformation)
- Or open an issue if you don't have time for a pull request

## Package Naming Conventions

- Packages typically end in `.jl` to distinguish them from non-Julia packages
- Development activity dates are shown after package names
- Package descriptions from original sources are shown in *italics*

## Organizations & Projects

### BBN Technologies
*[BBN-Q](https://github.com/BBN-Q) - Quantum Computing Research Division*

#### Core Quantum Packages
- [Cliffords.jl](https://github.com/BBN-Q/Cliffords.jl) (12/2020) - *Efficient calculation of Clifford circuits*
- [QuantumTomography.jl](https://github.com/BBN-Q/QuantumTomography.jl) (12/2020) - *Quantum state and process tomography*
- [QuantumInfo.jl](https://github.com/BBN-Q/QuantumInfo.jl) (12/2020) - *Library for quantum information calculations*
- [QSimulator.jl](https://github.com/BBN-Q/QSimulator.jl) (11/2019) - *Unitary and Lindbladian evolution*

#### Specialized Tools
- [RandomQuantum.jl](https://github.com/BBN-Q/RandomQuantum.jl) (12/2019) - *Random quantum state and process generation*
- [SchattenNorms.jl](https://github.com/BBN-Q/SchattenNorms.jl) (12/2020) - *Schatten norms and completely bounded norms*
- [MESolve.jl](https://github.com/BBN-Q/MESolve.jl) (03/2021) - *Master Equation Solver*
- [PAPA.jl](https://github.com/BBN-Q/PAPA.jl) (12/2019) - *PAirwise Perturbative Ansatz*

#### Hardware Interface
- [QGL.jl](https://github.com/BBN-Q/QGL.jl) (04/2018) - *Performance-oriented Quantum Gate Language compiler*
- [Qlab.jl](https://github.com/BBN-Q/Qlab.jl) (12/2020) - *Generic lab tools*
- [Instruments.jl](https://github.com/BBN-Q/Instruments.jl) (12/2020) - *Instrument Control*

### QuantumBFS
*A collaborative group of quantum developers centered around Bao Fu Si (Temple)*

- [Yao.jl](https://github.com/QuantumBFS/Yao.jl) (06/2021) - *Extensible, Efficient Quantum Algorithm Design*
  - Features approximately 20 integrated packages
  - Website: [yaoquantum.org](http://yaoquantum.org/)

### Tensor Network Tools

#### Jutho Haegeman's Tensor Framework
- [TensorOperations.jl](https://github.com/Jutho/TensorOperations.jl) (07/2021) - *Tensor contractions and operations*
- [TensorKit.jl](https://github.com/Jutho/TensorKit.jl) (07/2021) - *Large-scale tensor computations with category theory*
- [WignerSymbols.jl](https://github.com/Jutho/WignerSymbols.jl) (07/2021) - *Wigner symbol computations*
- [LinearMaps.jl](https://github.com/Jutho/LinearMaps.jl) (07/2021) - *Efficient linear transformations*

#### ITensor Organization
- [ITensors.jl](https://github.com/ITensor/ITensors.jl) (06/2021) - *Efficient tensor network calculations*
- [NDTensors.jl](https://github.com/ITensor/NDTensors.jl) (05/2021) - *N-dimensional sparse tensors*
- [PEPS.jl](https://github.com/ITensor/PEPS.jl) (06/2020) - *Projected entangled pair states*

## Specialized Areas

### Quantum Control & Simulation
- [JuliaQuantumControl](https://github.com/JuliaQuantumControl) (11/2021) - *Open-loop quantum optimal control methods*
- [PastaQ.jl](https://github.com/GTorlai/PastaQ.jl) (06/2021) - *Quantum computer simulation using ML and tensor networks*
- [QuantumClifford.jl](https://github.com/Krastanov/QuantumClifford.jl) (06/2021) - *Clifford circuit simulation*

### Quantum Optics
- [QuantumOptics.jl](https://github.com/qojulia/QuantumOptics.jl) (06/2021) - *Framework for quantum system simulation*
- [Schrodinger.jl](https://github.com/jebej/Schrodinger.jl) (05/2021) - *Fast quantum mechanical system simulation*

### Quantum Chemistry
- [DFTK.jl](https://github.com/JuliaMolSim/DFTK.jl/) (06/2021) - *Density-functional toolkit*
- [QuantumLab.jl](https://github.com/vonDonnerstein/QuantumLab.jl) (06/2021) - *Quantum Chemistry/Physics workbench*
- [Atoms.jl](https://github.com/JuliaAtoms/Atoms.jl) (06/2021) - *Atomic orbital representations*

## Additional Resources

### Related Lists
- [JuliaPhysics Documentation](https://juliaphysics.github.io/latest/index.html)
- [Tutorial For Physicists](https://rogerluo.me/TutorialForPhysicists.jl/latest/toolchain/index.html)

### Deprecated Packages
*These packages are no longer maintained. Please use their recommended replacements:*

- TensorToolbox.jl → TensorOperations.jl
- NCon.jl → TensorOperations.jl
- JuliaQuantum (inactive since 12/2016)
