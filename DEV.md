# Dev Log

Problem:

- How to create a two bistable environments with different amplitudes for the pinky and ring finger column

Solutions:

- Sliding, bumps at the extremities to hold sliding part in place
    - lots of friction
    - wear out over time
    - hard to tolerance with fdm
- Sliding in general is hard to tolerance and wears out, and hard to make smooth
- I want smooth
- Compliant mechanism
- 
    
    ![Afbeelding1.png](https://github.com/at1047/clarent/blob/main/photos/Afbeelding1.png)
    
- Will have fatigue stress at the joints

![Untitled](https://github.com/at1047/clarent/blob/main/photos/Untitled.png)

- Use actual joints at the two ends, the whole moving part is a curve so can decide amplitude based on where the joint is attached on the curve

![Untitled](https://github.com/at1047/clarent/blob/main/photos/Untitled1.png)

![Untitled](https://github.com/at1047/clarent/blob/main/photos/Untitled2.png)

- Started to look for ways to implement the mechanism I chose. First layout based on Keebio Iris I’ve been using for multiple years now

![Untitled](https://github.com/at1047/clarent/blob/main/photos/Untitled3.png)

![Untitled](https://github.com/at1047/clarent/blob/main/photos/Untitled4.png)

- Added additional thumb key, designed base to be easily printable using fdm
    - Controller holder separated from main base because the overhangs would be extremely hard to print otherwise, all features on opposite side of main base

![Untitled](https://github.com/at1047/clarent/blob/main/photos/Untitled5.png)

- Added slight tilt to thumb keys for better ergonomics

![Untitled](https://github.com/at1047/clarent/blob/main/photos/Untitled6.png)

- Reduced base length so keyboard can be lower while tented, added chamfers and TPU feet holes
