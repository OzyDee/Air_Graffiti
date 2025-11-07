I acknowledge the use of ChatGPT in this assessment.
The resulting output was used for brainstorming ideas and receiving help to guide my work.
I confirm that the extent of the use of AI in this assessment is limited to the conditions specified above.




# Air Graffiti — Journal Entry 1

**Project:** Air Graffiti  
**Date:** 01/09/2025

## Concept Overview

This week, I kicked off my project idea for Air Graffiti. The core concept is a web-based graffiti simulation that turns a smartphone into a virtual spray can. By using the phone’s motion sensors, I can track how the device is tilted and moved, allowing the user to “spray” digital paint onto a canvas.

## Key Features Planned

- **Motion-Controlled Painting:** The phone’s orientation (tilt up, down, left, right) will control the position and flow of the digital spray, mimicking the feel of using a real can of paint.
- **Photo-Wall Mode:** Users can take a photo of a real wall and then paint over it digitally. This will help them visualize how their graffiti would look in a real-world context.
- **Graffiti Styles:** I’ll include different colours, spray patterns, drips, and textures to keep it authentic to graffiti culture.
- **Save Functionality:** After creating their art, users can save the final image.

## Goals for Next Steps

- Prototype the motion-to-paint mapping and test it on a basic canvas.
- Implement a simple interface to switch between a blank canvas and a photo background.

# Air Graffiti — Journal Entry 2

## Progress This Week

This week I made solid progress by integrating the device camera into the app. Users can now capture a photo directly from their phone and use that photo as a canvas background. I also set up a basic interface that allows switching between a blank canvas and the newly captured photo.

## Achievements

- **Camera Functionality:** I can now take a picture within the app and use it as the background. This is a big step toward the Photo-Wall mode I envisioned.
- **Basic UI:** I’ve got a simple interface that lets users switch between a standard blank canvas and the photo they’ve taken.

## Challenges

- **Motion Sensor Issues:** While the camera is working well, I'm still facing some connectivity challenges with the motion sensors. I'm able to get the camera feed reliably, but the sensor data for motion control is still inconsistent. I’ll continue troubleshooting that.

## Next Steps

- Resolve the motion sensor connectivity so that the phone’s tilt and movement can control the spray.  
- Refine the painting tools and brush styles now that we have a working background feature.


# Air Graffiti — Journal Entry 3

## Progress This Week

In my third week, I’ve brought almost all the pieces together. The camera and UI are working smoothly, and I've integrated the painting tools so that users can spray paint on either a blank canvas or a photo background. I’ve refined the look and feel of the brushes and the colour options. 

## Achievements

- **Full Integration:** The main features are now connected and functioning. I can paint with different colours and styles on top of the captured photo or a blank background.
- **UI Polish:** I’ve made the interface cleaner and more intuitive, with buttons to switch modes, pick colours, and save the final artwork.

## Challenges

- **Motion Sensor Connectivity on iPhone:** I'm still experiencing issues with the motion sensors, especially on iPhone (i think). Both Chrome and Safari are having trouble consistently accessing the orientation data. It might be a permissions or browser setting issue, so I’ll keep investigating that.

## Next Steps

- Troubleshoot iPhone motion sensor connectivity further and ensure consistent access in both Chrome and Safari.
- Finalise and test the save functionality so users can easily download their finished graffiti images.

## Air Graffiti - Journal Entry 6 — Advanced Spray and Drip Effects

I focused on improving the realism of the spray patterns.
I experimented with different “nibs” to simulate how a real spray can behaves — starting with solid, spray, and fan patterns. I developed a drip effect that reacts to paint flow, allowing heavier sprays to form trails that run down the surface.
Getting this balance right took time; I wanted drips to look random but still respond naturally to spray density. By adjusting flow rate and spread, the drips started to behave in a believable way. This feature became one of the most distinctive parts of the project.

## Air Graffiti - Journal Entry 7 — Custom Nibs and Cap Presets

After refining the spray physics, I added the option to select different spray caps.
Each cap type — Ultra Skinny, Skinny, Medium, Fat, and Super Fat — controls both the line width and flow output, similar to how aerosol caps work in real life.
I then created a Custom Nib mode so users can manually adjust size, flow, drip, and fan strength. This gave the painter a realistic range of control while keeping the interface simple.
I also cleaned up the menu so that size and flow sliders only appear when using the custom cap, preventing unnecessary clutter.

## Air Graffiti - Journal Entry 8 — UI Optimisation for Mobile and Tablets

I reworked the interface to make it functional on phones and iPads.
I found that the control sliders and buttons were taking up too much screen space when painting, so I added collapsible panels and replaced text labels with icons. The colour picker was converted into a circular swatch button that opens the native colour selector when tapped — improving performance on iOS Safari.
These changes made the app more practical for touch-based use and much cleaner visually. It now scales and adapts automatically to different device sizes.

## Air Graffiti - Journal Entry 9 — AR and Motion Tracking Experiments

My main goal was to get the painting to appear in real-world space instead of a flat canvas.
I built a new version using Three.js and tested both WebXR and 8th Wall for surface detection. The idea was to allow the phone to track walls or flat planes so that the spray would stick to them as the user moved.
I managed to get this working on Android through WebXR, but Safari on iPhone doesn’t support AR hit-tests natively. I began setting up 8th Wall (which supports iOS), but couldn’t complete the configuration in time for full integration.
Even so, these tests confirmed that the concept is achievable with the right SDK.

## Air Graffiti - Journal Entry 10 — Final Testing and Reflection

I focused on polish and reliability.
I refined the fan strength control so that spray width grows gradually from the centre of the nib, improved the feathering for softer edges, and stabilised the colour picker for mobile devices. I also tested a background colour selector so both Free-Air and Photo-Wall modes use the same visual style.
While I couldn’t fully implement the 8th Wall AR system, I did build a partial working simulation of what the feature would do. The finished version will successfully represents how motion, paint flow, and fan dynamics interact in a digital graffiti environment.
If I had more time, I’d finalise the AR wall tracking and link the GPS location to each artwork.