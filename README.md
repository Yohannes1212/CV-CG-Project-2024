# Motion Capture Project

## Project Overview
This project involves animating and compositing motion capture actor performances using OptiTrack and camera motion tracking. We aimed to create realistic animations by recording 3D performances, retargeting them to animated characters, and compositing them into lifelike environments. Additionally, we utilized camera motion tracking to blend animated characters into moving video footage.

## Technologies and Tools Used

### Hardware
- **OptiTrack Motion Capture System**: Used for precise 3D motion tracking.
  - 8 infrared cameras with 360 fps.
  - Retroreflective markers and a velcro suit for tracking.
  - Controlled environment with blackout curtains to minimize interference.

### Software
- **Motive Software**: For real-time 3D motion data processing.
- **Blender**: Used for:
  - Retargeting motion capture data using the Rokoko plugin.
  - Aligning perspective with the fSpy tool.
  - Camera motion tracking for compositing animation with live video footage.
- **fSpy**: To align camera perspective.
- **Mixamo**: For 3D character models.

## Methodology

### Motion Capture Process
1. **Setup**:
   - Calibrated the OptiTrack system.
   - Prepared the environment by eliminating reflective interference.
   - Placed 41 markers on the actor's suit using the Motive software template.
2. **Recording**:
   - Recorded multiple takes of the actor performing movements.
   - Exported motion capture data in `.bvh` and `.fbx` formats.

### Retargeting Animation
- Imported motion capture data and 3D character models into Blender.
- Addressed challenges like clipping and slipping due to proportion differences between the actor and character model.

### Perspective and Lighting
- Used fSpy to match Blender’s camera perspective with background images.
- Manually adjusted light sources in Blender to replicate real-world lighting.

### Camera Motion Tracking
- Recorded moving footage behind the Povo 0 building.
- Used Blender’s motion tracking workspace to:
  - Track features in video frames.
  - Estimate camera motion and align it with the 3D scene.
- Adjusted scene scale and orientation for accurate compositing.

## Results
We produced three videos showcasing different compositing techniques:
1. **Static Background (Disney’s Coco)**:
   - Demonstrated basic compositing with a CGI background.
2. **Lab Environment**:
   - Used a motion capture lab photo as a background.
3. **Moving Camera Video**:
   - Composited animation over a video with camera motion tracking.

### Observations
- **Strengths**:
  - Realistic motion capture for complex movements like handstands.
  - Effective integration of characters into varied environments.
- **Limitations**:
  - Proportion mismatches caused clipping and slipping.
  - Limited realism in hand movements due to insufficient markers.
  - Camera motion tracking was constrained by smartphone camera quality.

## Video Links
- [Static Background - Coco](https://drive.google.com/open?id=1oXqrIyWFxud3ANy0RwxZl7gLI2DL3CoF)
- [Lab Animation](https://drive.google.com/open?id=1jHLMiKImHm36xN7NJFEOsI4GYL9qZzbX)
- [Hand Walk with Motion Tracking](https://drive.google.com/open?id=1Sx3i5IR66V3tTN4D8HekCtMqTNtvnp5c)

## Conclusion
This project successfully demonstrated the use of motion capture and camera tracking techniques to create realistic animated performances. While there are limitations, particularly in hand tracking and compositing accuracy, the results showcase the potential of integrating motion capture technology with animation and real-world footage.

For further details or to collaborate, feel free to contact us!

