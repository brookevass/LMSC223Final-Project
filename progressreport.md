# Progress Report for oFxOSC Final Project (LMSC 223)
## In PD:

### **Changes to Pitch, Loudness, GarageBand, and Tempo:**
**Tempo:**
  - Set the tempo to `500`, creating a faster backtrack sound to complement the instrumental tracks added in GarageBand.
  **Tracks Added:**
  - Included a "pulsating wave" track that harmonized well with the current pitch and loudness settings. I think it added a good rhythmic quality to the overall sound, those were my dance instincts kicking in :)
**Pitch:**
  - Set pitch values in the `50–60` range, made a lower tone that balances with the pulsating wave.
**Loudness:**
  - Loudness numbers range from `70–80`, I found it made a clear and strong sound without overwhelming the mix.

### **Observations:**
- I experimented with adding more instrumental tracks and sound elements 
- I found that the higher tempo and pulsating wave track created a nice rhythm 
- when I adjusted pitch and loudness it led to a nice sounding rhythm with a constant tempo

## Plan for OSC
1. **Connect Pd and OSC:**
   - listen to the tempo, pitch, and loudness values from PD and try to replicate it with a image in OSC to what I feel resembles this wave sound 
2. **make sure Graphics are beyond the template:**
   - I will take what we did with the single ball and change it by using shapeslike waves and rotating circles that react to changes in pitch, loudness, and tempo.
3. **Implementation:**
   - Use the `draw` to generate multiple objects or visual effects:
     - **Pitch:** Control the size or height of objects.
     - **Loudness:** Adjust brightness and number of visuals 
     - **Tempo:** in line w the speed of objects
   - also add color schemes

## Next Steps
1. **Finalize PD Sound:**
   - perfect pitch and loudness 
   - Test different tempo settings to find best fit with visuals

2. **figure out PD-to-OSC:**
   - Test OSC messages - need to look more into this addition reasources on this would be helpful

3. **Visual Design in OSC:**
   - play around and change function templates 

## End Goal
- I see myself being able to create a audiovisual where the sound designed in PD cooralates with the visual display in OSC.
- Move beyond the basic ball example by designing complex, graphics that move to the sound
