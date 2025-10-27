# Hex Rover Visualization — The Martian (2015)

This project recreates the ASCII-to-hex rover communication scene from *The Martian*.

Students:
1. Convert ASCII to hexadecimal.
2. Map each hex digit to a circle position.
3. Rotate a robot visualization to face each digit.
4. Display and log current angle and delta per step.

---

## Repository Structure

- **src/** – Your implementation.
- **docs/** – Reference material and task description.
  - index.html
- **data/** – Optional sample inputs.

---

## Development Tasks

1. **Input conversion**
   - Convert user text to hex digits.

2. **Rotation logic**
   - Map each hex digit to an angle (22.5° increments).
   - Compute `Δθ` from current heading to next target.
   - Animate rotation (CSS, Canvas, or SVG).

3. **Logging**
   - For each step, display:
     - Digit
     - Target angle
     - Current angle
     - Δθ

4. **Controls**
   - Implement *Play*, *Step*, and *Reset*.

---

## Follow-Up Extensions (Optional)

- **Variant A:** Add a “checker” robot verifying correct angles.
- **Variant B:** Use a REST endpoint to receive rotations and decode message.
