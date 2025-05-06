# four-stage-audio-amplifier

a 4-stage audio amplifier designed for the *electronics workshop 2* course at iiit hyderabad.  

## key features  
- **stages**: preamp (differential), gain (ce), bandpass filter, power amp (class-ab)  
- **specifications**:  
  - gain ≥500 (preamp + gain stages)  
  - 20hz–20khz bandwidth  
  - 1.5w output @ 10Ω load  
- **tools used**: ltspice, digital storage oscilloscope, pspice for ti

## repository structure  
```
four-stage-audio-amplifier/
├── simulations/              # ltspice simulation files
│   ├── spice-files/              # ltspice schematics
│   │   ├── pre-amp.asc
│   │   ├── gain-stage.asc
│   │   ├── power-amp.asc
│   │   └── full-circuit.asc
│   └── spice-library-files/      # ltspice libraries            
│       ├── TIP31C.LIB
│       ├── TIP32C.LIB
│       └── UA741.301
│
├── datasheets/               # component datasheets
│   ├── bc546.pdf            
│   ├── tip31c.pdf           
│   └── tip32c.pdf           
│
├── documents/                # project documentation
│   ├── project-details.pdf       # specifications and requirements
│   └── project-report.pdf        # full project report
│
├── hardware/                 # hardware implementation
│   ├── assembled-circuit/        # photos of circuit stages
│   │   ├── pre-amp.png
│   │   ├── gain-stage.png
│   │   ├── filter.png
│   │   ├── power-amp.png
│   │   ├── full-circuit.png
│   │   ├── mic.png
│   │   └── voltage-divider.png
│   │
│   ├── oscilloscope-outputs/ # measurement results
│   │   ├── pre-amp.png
│   │   ├── gain-stage.png
│   │   ├── filter.png
│   │   ├── fra-lower.png
│   │   ├── power-amp.png
│   │   ├── fra-upper.png
│   │   └── final-output.png
│   │
│   └── bill-of-materials.md
│
├── references/               # research and reference materials
│   ├── AudioAmpDesign.pdf     
│   └── unbalanced-amp.pdf     
│
└── readme.md                
```
## demonstration videos
- [frequency response analysis](https://youtu.be/Lo99qeKNm6Q)
- [full circuit test with 10Ω load](https://youtu.be/EKdBo0fZbkk)

**contributors**: priyanshi jain, ritama sanyal  

for details, see [project-report.pdf](documents/project-report.pdf).

