# ParticleSystem

Ongoing project of rendering particles with a compute shader<br>

Result is similar to this<br>
<img src="https://github.com/ThomasSchemmer/Particles/blob/master/Assets/result.gif" alt="ParticleResult" width="200"/>

Tested with up to 500mio particles, which creates a simple band. Laggy, but doable<br>
Currently implementing the G-PICS Framework from this paper<br>
https://ieeexplore.ieee.org/document/9086127<br>
which is a QuadTree distributed and optimized for the GPU
