# Dev Log

- How to create a bistable environments with different amplitudes for the pinky and ring finger column
  
## Problems with existing solutions

### Do nothing

- Column stagger good for regular typing, but the stagger is offset when home row is moved to WASD when gaming
- Thumb/space placement is also moved when using WASD
- Only control key on bottom left, missing a control for additional inputs (can’t move to thumb cluster, control key often use in conjunction with space key)

### Remapping game

- Original thumb space key is tap-dance for command/mod key. The short press key for Tap-dance is read on the falling edge, which is not good enough for gaming
- A lot of games to remap
- Not enough keys on the right of WASD for additional key-binds
- Additional keys on the left, but pinky and ring finger is less dexterous than pointer finger

### Gaming layer

- Removes an entire column from the keyboard, can’t type normally
- Needs pressing of a button, sometimes forget to switch layers even with visual cue (RGB)

## Designing the Bi-stable Column Stagger

### Ideas
- Use sacrificial layers for bridging
- Add thin sand-able spacers to adjust tolerances after printing
- Use gears??
- Sliding, bumps at the extremities to hold sliding part in place
    - lots of friction
    - wear out over time
    - hard to tolerance with fdm
- Sliding in general is hard to tolerance and wears out, and hard to make smooth
- Remove sliding mechanism, use pairs of compliant mechanism free-floating

### Final Sliding Mechanism 

- Utilizes a compliant mechanism
- Design stress points to be along a curve, not a point
- Multipart to avoid living hinges (stress on a single point)
- Nylok nuts to allow for revolute joint (Only angular axis of freedom) without overtightening

## Key Layout

- Left Side
    - Extra Shift key next to Control for games
    - More horizontally angled Space Bar to allow for home-row Shift
- Right side
    - Extra Enter key to avoid tap-dance requirement of Shift and Enter (Didn't do, instead learnt to use thumb key for shift)


    
![Afbeelding1.png](https://github.com/at1047/clarent/blob/main/photos/Afbeelding1.png)
    
- Will have fatigue stress at the joints

![Untitled](https://github.com/at1047/clarent/blob/main/photos/Untitled.png)

- Use actual joints at the two ends, the whole moving part is a curve so can decide amplitude based on where the joint is attached on the curve

![Untitled](https://github.com/at1047/clarent/blob/main/photos/Untitled%201.png)

![Untitled](https://github.com/at1047/clarent/blob/main/photos/Untitled%202.png)

- Started to look for ways to implement the mechanism I chose. First layout based on Keebio Iris I’ve been using for multiple years now

![Untitled](https://github.com/at1047/clarent/blob/main/photos/Untitled%203.png)

![Untitled](https://github.com/at1047/clarent/blob/main/photos/Untitled%204.png)

- Added additional thumb key, designed base to be easily printable using fdm
    - Controller holder separated from main base because the overhangs would be extremely hard to print otherwise, all features on opposite side of main base

![Untitled](https://github.com/at1047/clarent/blob/main/photos/Untitled%205.png)

- Added slight tilt to thumb keys for better ergonomics

![Untitled](https://github.com/at1047/clarent/blob/main/photos/Untitled%206.png)

- Reduced base length so keyboard can be lower while tented, added chamfers and TPU feet holes
