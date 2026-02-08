# XR Interaction Lab - Gaze-Based Interaction Study

## Project Overview
This Unity XR project explores gaze-based interaction techniques and sensory feedback mechanisms in virtual reality environments.

---

## Key Concepts and Questions

### 1. What is Gaze-Based Interaction?

**Gaze-based interaction** is a hands-free input method in XR (Extended Reality) where users interact with virtual objects by looking at them. The system tracks where the user's eyes or head are pointing and uses this as the primary input mechanism.

**Key Features:**
- **Eye/Head Tracking**: Uses the direction of the user's gaze to determine target objects
- **Hands-Free Control**: Eliminates the need for controllers or hand gestures
- **Natural Interaction**: Leverages the natural human tendency to look at objects of interest
- **Accessibility**: Particularly useful for users with limited mobility or in situations where hands are occupied

**Common Applications:**
- Menu selection in VR interfaces
- Object highlighting and selection
- Navigation and wayfinding
- Accessibility features for users with motor impairments

---

### 2. Why is Dwell Time Useful?

**Dwell time** is the duration a user must maintain their gaze on an object before an action is triggered. It serves several critical purposes:

**Benefits:**
- **Prevents Accidental Activation**: Reduces false positives from brief glances or eye movements
- **Intentional Selection**: Ensures the user deliberately wants to interact with the object
- **Visual Feedback**: Provides time for progress indicators (e.g., circular timer) to confirm selection
- **User Control**: Gives users time to cancel an action by looking away
- **Reduces Fatigue**: Prevents constant triggering from natural eye movements

**Typical Implementation:**
- **Short Dwell (0.5-1s)**: Quick selections, menu navigation
- **Medium Dwell (1-2s)**: Standard object interactions
- **Long Dwell (2-3s)**: Critical actions requiring confirmation

**Example**: When looking at a button, a circular progress indicator fills over 1.5 seconds. If the user maintains gaze, the button activates; if they look away, the timer resets.

---

### 3. How Does Sensory Feedback Improve Realism?

**Sensory feedback** (also called multimodal feedback) engages multiple senses to create a more immersive and realistic XR experience.

**Types of Sensory Feedback:**

#### Visual Feedback
- **Color changes**: Highlighting objects when gazed upon
- **Animations**: Objects responding to interaction
- **Particle effects**: Visual cues for successful interactions
- **Glow/Outline effects**: Indicating interactive elements

#### Auditory Feedback
- **Spatial audio**: 3D sound that matches object positions
- **Confirmation sounds**: Audio cues for successful selections
- **Ambient sounds**: Environmental audio for presence
- **Haptic-audio synchronization**: Sound matching physical sensations

#### Haptic Feedback
- **Vibration patterns**: Controller rumble on interaction
- **Force feedback**: Resistance when touching virtual objects
- **Texture simulation**: Different vibration patterns for surfaces

**Why It Improves Realism:**
1. **Confirms Actions**: Users know their interactions succeeded
2. **Spatial Awareness**: Helps users understand object positions and properties
3. **Engagement**: Multiple senses create stronger presence
4. **Natural Mapping**: Mimics real-world cause-and-effect relationships
5. **Error Prevention**: Immediate feedback prevents mistakes

**Example**: When selecting a cube:
- **Visual**: Cube glows and changes color
- **Audio**: Pleasant "click" sound plays
- **Haptic**: Controller vibrates briefly
- **Result**: User feels confident the selection registered

---

### 4. Which Cube Felt Most Immersive and Why?

Based on typical XR interaction experiments, the **most immersive cube** usually exhibits the following characteristics:

#### Characteristics of the Most Immersive Cube:

**Multimodal Feedback Integration:**
- ✅ **Visual**: Smooth color transitions, glow effects, and responsive animations
- ✅ **Audio**: Spatial 3D sound that changes based on interaction state
- ✅ **Haptic**: Subtle vibration patterns that match visual/audio feedback

**Interaction Design:**
- **Appropriate Dwell Time**: Not too short (accidental) or too long (frustrating)
- **Clear Visual Progress**: Circular timer or fill indicator showing dwell progress
- **Immediate Response**: Instant visual acknowledgment when gaze enters the object
- **Smooth Transitions**: No jarring changes that break immersion

**Why It Feels Most Immersive:**

1. **Coherent Feedback Loop**: All sensory channels work together harmoniously
2. **Natural Timing**: Dwell time matches user expectations (1-2 seconds)
3. **Predictable Behavior**: User can anticipate what will happen
4. **Satisfying Interaction**: Combination of feedback creates a "rewarding" feeling
5. **Presence Enhancement**: Multiple senses convince the brain the interaction is "real"

**Comparison Example:**

| Cube Type | Visual | Audio | Haptic | Immersion Level |
|-----------|--------|-------|--------|-----------------|
| Cube A | ✅ Color change only | ❌ None | ❌ None | Low |
| Cube B | ✅ Glow + Animation | ✅ Click sound | ❌ None | Medium |
| Cube C | ✅ Glow + Animation + Particles | ✅ 3D Spatial Audio | ✅ Vibration Pattern | **High** |

**Conclusion**: The cube with **synchronized multimodal feedback** (visual + audio + haptic) creates the most immersive experience because it engages multiple senses simultaneously, creating a stronger sense of presence and making the virtual interaction feel more tangible and real.

---

## Project Structure

```
XR_InteractionLab/
├── Assets/              # Unity assets and scripts
├── Packages/            # Unity package dependencies
├── ProjectSettings/     # Unity project configuration
├── .gitignore          # Git ignore rules for Unity
└── README.md           # This file
```

---

## Technologies Used
- **Unity** - Game engine and XR development platform
- **XR Interaction Toolkit** - Unity's framework for VR/AR interactions
- **Gaze Tracking** - Eye/head tracking for interaction
- **Spatial Audio** - 3D audio positioning
- **Haptic Feedback** - Controller vibration systems

---

## Learning Outcomes
Through this lab, you will understand:
- How gaze-based interaction works in XR environments
- The importance of dwell time in preventing accidental selections
- How multimodal sensory feedback enhances immersion
- The relationship between feedback quality and user experience

---

## Repository
This project is hosted at: [GitHub Repository](https://github.com/InteractiveMediaGD/se4051-trends-in-digital-media-lab-01-IsharaKumarage)

---

*SE4051 - Trends in Digital Media Lab 01*
