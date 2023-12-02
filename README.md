# Colours: Clarified

No compromises colour data library for Rust.

## Goals:

- Support for: 
  - [] RGB 
  - [] (CIE) XYZ
  - [] HSL
  - [] HSV
  - [] sRGB
  and more, with fast, correct conversion from any to any.

- `no_std` support (with a default `std` feature to gate any functionality requiring `std`)

- Minimal dependencies

- Safe (`#![forbid(unsafe_code)]`)

- Implement basic colour operations:
  - [] Darken/Lighten
  - [] Alpha Blending
  - [] Average
  - [] Distance (within a space)
  - [] (De)saturate
  - [] Hue Rotation
  
