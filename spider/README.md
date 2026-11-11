# spider

A spider that follows the mouse. Its legs are animated procedurally: no keyframes, every step is decided at runtime.

Open `index.html` in a browser.

## How it works

- Each foot stays planted until it drifts too far from a resting spot relative to the body, then steps to a new spot slightly ahead in the direction of travel.
- A leg can't lift while an adjacent leg is in the air, which produces an alternating gait.
- Legs are bent with two-segment inverse kinematics.
- The body sways toward planted feet and slows down when legs are overstretched.

## Controls

- **Mouse:** the spider follows the cursor.
- **Scroll:** resize the spider.
- **D:** toggle the debug view (step targets and step distance).
- **Options box (top right):** speed, per-pair leg settings (angle, length, stride, lift, tempo), variation, randomize/reset, and saving configurations locally.
