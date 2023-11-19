# Project Overview: Curium 5

![Banner Image](https://raw.githubusercontent.com/Curium-Five/.github/main/profile/media/banner.png)

The Curium 5 project is designed around the development of 6U CubeSats, using components primarily sourced from commercial manufacturers. We utilize a launch opportunity from the [DLR microlauncher competition 2022](https://www.dlr.de/en/latest/news/2022/02/20220620_go-ahead-for-second-round-of-microlauncher-payload-competition) to validate the design.

Lastly, deploying commercial hardware of consumer and industrial quality can demonstrate the feasibility and cost-effectiveness of these components for space missions. We are also considering involving external stakeholders in payload development. A collaboration with the German Aerospace Center and the University of Vienna will facilitate the integration of a novel, laser-based quantum computer, marking its inaugural deployment in space.

<div style="display: flex; justify-content: space-evenly;">
   <figure>
  <figure>
    <img src="https://github.com/Curium-Five/.github/assets/4999364/a55bb013-2740-49e6-a685-60fcc72acb61" alt="Dispenser Image" width="400">
  </figure>
     <figcaption>First integrated prototype</figcaption>
  </figure>
</div>

## Project Goals

The Curium 5 CubeSat mission goals are of educational nature. The key objectives include:

- Acquiring experience in designing and producing CubeSat buses with commertial of the shelf (automotive) parts.
- Using some hardware and software based on previous missions.

# Research


In cooperation with HPI [operating system and middleware chair](https://osm.hpi.de) the project will include research for a master thesis.
In cooperation with University of Viennas [walther group](https://walther.quantum.at) and [DLR remote sensing institute](https://www.dlr.de/eoc/en/desktopdefault.aspx/tabid-5279/8913_read-16239/) a experiment will be developed as satellite payload and is part of a PHD. 

## Technical Specifications


### Structure:
- Size: 6U CubeSat
- Weight: <8 Kg

### Electrical Power System (EPS)
- Solar cells: Monocrystalline Si cells
- Power: minimum 2-5 W average for payload, higher burst loads >50W possible
- Energy storage: Lithium Ion MJ1 cells

### Attitude Determination & Control (ADCS)
- Magnetorquer
- possibly reaction wheels

### Communication (Comm)
- Amateur & commercial radio bands for uplink and downlink, with a data transfer rate of up to 50 kbps
- Usage of ground station network SatNOGS
- Antenna: simple monopole antennas with orthogonal radiation patterns to achieve quasi-isotropic radiation properties.

### Data Handling (OBC)
- Computer: rad tolerant STM32H7 based 

### Launch & Lifetime
- Launch vehicle: Designed along Vega C guidelines
- Launch dates: Planned June 2024
- Estimated lifespan: >3 months

