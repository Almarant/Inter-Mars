# Inter-Mars

Thermal structure and interior dynamics of Mars, from the Earth and Planetary Interiors module (XMS3GU050) at the University of Nantes, 2024.

The notebook builds a 1-D thermal model of the Martian crust and mantle:

- interior structure from Mars' radius and gravitational parameter
- mantle solidus and liquidus as a function of depth and pressure
- stagnant-lid convection with temperature-dependent viscosity: thermal boundary layer, surface heat flux and Urey number
- temperature profiles for a range of convective mantle temperatures, plotted against the solidus and liquidus

## Files

| File | Contents |
|---|---|
| [`Inter_Mars_code.ipynb`](Inter_Mars_code.ipynb) | Model and figures (renders directly on GitHub) |
| [`Inter_Mars_report.pdf`](Inter_Mars_report.pdf) | Write-up of method and results |

## Run it

```bash
pip install numpy matplotlib jupyter
jupyter notebook Inter_Mars_code.ipynb
```
