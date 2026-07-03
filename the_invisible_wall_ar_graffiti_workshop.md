# The Invisible Wall
## Phone-Based AR Graffiti Workshop for Immersive Storytelling

### Working Title
**The Invisible Wall: Digital Graffiti and the Future of Immersive Storytelling**

### Core Idea
This workshop uses phone-based augmented reality to turn a physical space into a collaborative narrative environment. Each of the 25 participants receives a randomly assigned word or story fragment through a WebAR app. That word appears as floating digital graffiti in the AR environment.

The participants move through the room or surrounding area, placing, discovering, combining, and transforming their graffiti. Over time, individual words begin to connect into poetic phrases, group narratives, and finally one collective immersive story.

The main artistic question is:

**What happens when every wall, surface, and public space can become a living, collaborative story layer?**

---

## Concept Summary

Participants scan a QR code and open a WebAR experience on their phones. Each person is randomly assigned one of 25 predefined words.

The assigned word becomes a floating graffiti tag in AR. It may appear as spray paint, neon text, glitch typography, stencil lettering, or animated mural text.

Participants then explore the space. Their phones detect surfaces, visual textures, or environmental cues. These environmental readings influence the meaning, appearance, and behavior of the AR graffiti.

For example:

- A word placed on brick may become permanent, rough, or historical.
- A word placed on glass may become transparent, fragile, or reflective.
- A word placed near plants may grow vines or bloom.
- A word placed near metal may become industrial or mechanical.
- A word placed on a doorway may suggest transition, escape, or passage.
- A word placed beside another participant’s word may begin forming a sentence.

The story emerges through movement, placement, and collaboration.

---

## Example Word Set for 25 Participants

1. Threshold
2. Echo
3. Machine
4. Dream
5. Bloom
6. Collapse
7. Signal
8. Ghost
9. Seed
10. Memory
11. Noise
12. Gravity
13. Shelter
14. Shadow
15. Future
16. Water
17. Silence
18. Fragment
19. Home
20. Network
21. Breath
22. Fire
23. Mirror
24. Portal
25. Hope

These words are intentionally open-ended. They can feel poetic, technological, emotional, urban, or speculative depending on where they are placed.

---

## Narrative Device

The workshop works like a collaborative story engine.

Each participant starts with one word. The word is not just text; it is a character, a symbol, and a piece of a larger hidden story.

The app gives participants prompts based on what they do:

- “Find a wall where your word belongs.”
- “Place your word where it feels forbidden.”
- “Find someone whose word could continue yours.”
- “Create a sentence using three AR graffiti words.”
- “Move your word to a surface that changes its meaning.”
- “Join five words together to create a fragment of the final story.”

As people interact, the story begins forming through chains of words.

Example group chain:

**Machine → Dream → Portal → Memory → Home**

This becomes:

> A machine dreamed of a portal that remembered home.

Another chain:

**Collapse → Seed → Water → Future → Hope**

This becomes:

> After collapse, a seed carried hope into the future.

At the end, all group chains are collected and turned into one final collective AR poem or story.

---

## The Role of Graffiti

Graffiti gives the project cultural and visual weight. It connects immersive storytelling to public space, identity, protest, authorship, and urban memory.

The workshop can frame AR graffiti as a future form of street art:

- It can exist without permanently marking a wall.
- It can be animated, spatial, and interactive.
- It can respond to the environment.
- It can be collaborative instead of individual.
- It can be hidden, revealed, or rewritten.
- It raises questions about ownership of digital public space.

Key discussion question:

**If physical graffiti asks “Who has the right to mark the city?”, then AR graffiti asks “Who has the right to write on reality?”**

---

## Environment-Based Storytelling

The app can use browser-based computer vision or simpler environment detection to influence the story.

### Practical Detection Options

For a reliable workshop prototype, the system should not depend on complex object recognition unless time allows. The most achievable options are:

1. **World tracking / SLAM**
   - Lets participants place graffiti in physical space.
   - Works through the phone browser.
   - Best for anchoring text and 3D objects to walls or room positions.

2. **Surface placement**
   - Participants tap the screen to place graffiti on detected surfaces.
   - Good for a simple, stable version.

3. **Image targets**
   - Predefined posters, stickers, or printed markers around the space can trigger different story rules.
   - Very reliable for workshops.
   - Each marker can represent a narrative zone: Memory, Machine, Nature, Future, Collapse, etc.

4. **Texture or color analysis**
   - The camera feed can be sampled to infer visual qualities like dark/light, green areas, high contrast, brick-like texture, or reflective surfaces.
   - This can create the feeling that the environment is shaping the story.

5. **Manual environmental choice**
   - As a fallback, the app can ask: “What kind of surface are you pointing at?”
   - Options: wall, glass, plant, metal, door, screen, floor, sky.
   - This is less magical but very reliable.

### Best Workshop Approach

Use a hybrid model:

- Use WebAR for spatial placement.
- Use image targets or surface categories for narrative triggers.
- Use optional CV texture detection as an experimental layer.
- Keep a manual fallback so the workshop never breaks.

---

## Suggested Workshop Flow

### Phase 1 — Introduction: The City as a Page
Duration: 15–20 minutes

Introduce the idea of graffiti as public storytelling and AR as the next layer of public space.

Topics:
- Graffiti as identity, protest, memory, and message.
- AR as invisible architecture.
- Phone-based AR as accessible immersive media.
- The future of digital storytelling in public environments.

Prompt participants with:

**What would you write on the city if the city could answer back?**

### Phase 2 — Word Assignment
Duration: 5 minutes

Participants scan a QR code and open the WebAR app.

Each participant receives one random word from the set of 25. The word appears as floating graffiti in their AR camera view.

The app briefly tells them:

> This is your word. Find where it belongs.

### Phase 3 — Placement
Duration: 15–20 minutes

Participants walk through the space and place their word somewhere meaningful.

They can choose a surface, corner, object, or architectural feature.

When they place the word, the app asks a short question:

- Why does your word belong here?
- What is this wall hiding?
- What would this place remember?
- What future is trying to appear here?

The participant types a short answer or records a short voice note.

This answer becomes attached to the AR graffiti.

### Phase 4 — Environmental Transformation
Duration: 15 minutes

The app changes each graffiti word based on the environment.

Examples:
- On brick: the word becomes cracked, aged, and historical.
- On glass: the word becomes reflective and unstable.
- On plants: the word grows organic tendrils.
- On metal: the word becomes mechanical and glitching.
- Near a doorway: the word becomes a portal-like threshold.
- Near a screen: the word becomes AI-generated or corrupted.

This can be done through actual detection, image targets, or participant-selected surface categories.

### Phase 5 — Pairing and Merging
Duration: 20 minutes

Participants find another person whose word can connect to theirs.

When two participants meet, they scan each other’s QR code or enter a short pairing code.

Their two words combine into a phrase.

Examples:
- Ghost + Signal = “ghost signal”
- Mirror + Memory = “mirror memory”
- Fire + Network = “fire network”
- Breath + Machine = “breathing machine”

The app asks them to write one sentence using both words.

### Phase 6 — Group Story Chains
Duration: 25–30 minutes

Participants form groups of five.

Each group arranges its five words into a sequence.

The group creates a short speculative sentence or paragraph from the chain.

Example:

**Shadow → Door → Signal → Machine → Hope**

Possible story:

> A shadow crossed the door, carrying a signal from a machine that had learned hope.

Each group places its combined sentence as a larger AR graffiti mural.

### Phase 7 — Collective Final Story
Duration: 20 minutes

All group sentences are submitted to a shared page or facilitator dashboard.

An AI text generator, or a facilitator manually, combines them into one final collective story.

The final story appears as a large AR graffiti wall, poem, or floating narrative cloud.

Possible final format:

- A collective AR poem.
- A spoken-word performance.
- A large animated mural.
- A room-scale constellation of words.
- A QR-linked archive of the workshop.

### Phase 8 — Reflection and Future Discussion
Duration: 20–30 minutes

Discussion questions:

- What felt like storytelling: the word, the place, the technology, or the people?
- Did the AR graffiti change how you saw the physical space?
- Who should be allowed to write digital layers onto public places?
- Could AR graffiti become a new form of public art?
- What is realistic today?
- What might be possible in 5–10 years?
- What should never be built?
- What happens when cities remember us?
- What happens when AI starts writing with us in physical space?

---

## Technical Implementation Plan

### Version 1: Reliable Workshop Prototype

This is the recommended version for a real workshop.

Core features:
- QR code launch.
- Random word assignment.
- Phone-based AR placement.
- Floating graffiti text.
- Surface or zone selection.
- Pairing through QR code or short code.
- Group sentence submission.
- Final collective story display.

Recommended stack:
- 8th Wall open-source WebAR stack or similar browser-based AR framework.
- Three.js for 3D graffiti text.
- Simple JavaScript state management.
- Firebase, Supabase, or a lightweight Node backend for participant data.
- OpenAI API or local facilitator input for final story generation.
- QR codes for onboarding and participant pairing.

Why this version works:
- It is achievable.
- It does not rely on fragile real-time object detection.
- It still feels magical.
- It is accessible from participants’ phones.
- It creates a strong workshop outcome.

### Version 2: Enhanced CV Prototype

Add environmental recognition.

Features:
- Detect or classify surface categories.
- Use camera texture analysis.
- Trigger different visual styles based on detected material.
- Let environment influence story prompts.

Possible CV methods:
- Browser-based TensorFlow.js model.
- Lightweight image classification.
- Color and texture sampling.
- Predefined image targets.
- Manual fallback buttons.

Recommended surface categories:
- Brick / concrete
- Glass
- Metal
- Plant / organic
- Screen / digital
- Door / threshold
- Poster / sign
- Shadow / darkness
- Open space / sky

### Version 3: Advanced Collaborative AR

Add multi-user shared placement.

Features:
- Shared anchors.
- Real-time multiplayer word positions.
- Live merging of graffiti pieces.
- Persistent AR story map.
- Audio layers.
- AI-generated visual mutations.

Possible tools:
- WebRTC
- WebSockets
- Firebase Realtime Database
- Supabase Realtime
- Niantic Lightship / 8th Wall world tracking
- VPS or geospatial anchors if outdoors

This is more ambitious and should be treated as a future direction rather than the required workshop version.

---

## App Architecture

### Main Components

1. **Landing Page**
   - Explains the workshop.
   - Requests camera permission.
   - Starts AR session.

2. **Participant Assignment**
   - Randomly assigns one word.
   - Stores participant ID, word, and session ID.

3. **AR Graffiti Renderer**
   - Displays word as 3D text or textured plane.
   - Allows placement in physical space.
   - Supports animation and visual style changes.

4. **Environment Interaction**
   - Detects or asks for surface type.
   - Applies corresponding visual transformation and story prompt.

5. **Pairing System**
   - Allows two participants to combine words.
   - Can use QR scan, short numeric code, or shared session list.

6. **Group Story Builder**
   - Lets five participants arrange words.
   - Lets group submit a final sentence or paragraph.

7. **Facilitator Dashboard**
   - Shows all participants.
   - Shows assigned words.
   - Shows placed graffiti entries.
   - Shows pairings and group chains.
   - Allows final story generation.

8. **Final AR Mural**
   - Displays all words and the generated collective story.
   - Can become the documentation artifact.

---

## Data Model

### Participant
```json
{
  "id": "participant_01",
  "word": "Memory",
  "placed": true,
  "surface": "glass",
  "reflection": "This window feels like it remembers everyone who passed by.",
  "position": {
    "x": 0,
    "y": 1.5,
    "z": -2
  }
}
```

### Pair
```json
{
  "participants": ["participant_01", "participant_14"],
  "words": ["Memory", "Shadow"],
  "phrase": "shadow memory",
  "sentence": "A shadow memory appeared where the wall refused to speak."
}
```

### Group Chain
```json
{
  "group_id": "group_03",
  "words": ["Collapse", "Seed", "Water", "Future", "Hope"],
  "sentence": "After collapse, a seed carried water into a future still learning hope."
}
```

### Final Story
```json
{
  "title": "The Invisible Wall",
  "text": "Generated collective story goes here.",
  "created_from_groups": ["group_01", "group_02", "group_03", "group_04", "group_05"]
}
```

---

## Visual Design Direction

The experience should feel like street art mixed with speculative technology.

Possible visual styles:
- Neon graffiti
- Spray paint particles
- Glitch typography
- Animated stencil text
- Holographic paint
- Dripping digital ink
- Words made of light
- Floating tags that pulse when near other words
- Murals that grow when stories connect

Each environmental surface can have a style rule:

- Brick: rough spray texture
- Glass: transparent reflection
- Metal: chrome/glitch
- Plant: organic growth
- Screen: pixelated AI distortion
- Door: portal ring
- Shadow: low-opacity ghost text
- Concrete: bold stencil style

---

## Sound Design

Optional sound layers can make the experience more immersive.

Ideas:
- Spray can sound when placing a word.
- Subtle ambient tone per surface.
- Glitch sound when a word transforms.
- Whispered voice when two words merge.
- Final collective story read aloud by AI voice or participants.

---

## Implementation Steps

### Step 1 — Define the workshop rules
Finalize:
- Word list.
- Number of participants.
- Group size.
- Duration.
- Indoor or outdoor location.
- Whether the final story is AI-generated or facilitator-generated.

### Step 2 — Choose the technical stack
Recommended:
- WebAR framework for phone-based AR.
- Three.js for text and effects.
- Firebase or Supabase for shared data.
- Simple admin dashboard.
- Optional OpenAI API for final story generation.

### Step 3 — Build the landing page
Create:
- QR code entry.
- Workshop title.
- Camera permission flow.
- Start button.
- Session ID support.

### Step 4 — Build random word assignment
Create:
- 25-word array.
- Unique assignment logic so no word repeats.
- Participant ID.
- Storage in database.

### Step 5 — Create AR graffiti object
Build:
- 3D text or textured graffiti plane.
- Tap-to-place behavior.
- Animation loop.
- Basic style variations.

### Step 6 — Add surface/story prompt
Create:
- Surface selection menu or CV detection.
- Style transformation based on selected/detected surface.
- Prompt text connected to that surface.

### Step 7 — Add participant reflection
Allow each participant to:
- Type one sentence.
- Record optional audio.
- Save their response to the session database.

### Step 8 — Add pairing mechanic
Implement:
- QR code or short code pairing.
- Combined phrase generation.
- Two-person sentence prompt.

### Step 9 — Add group chain mechanic
Allow groups of five to:
- Select five words.
- Drag or reorder the chain.
- Submit one group sentence.

### Step 10 — Build facilitator dashboard
Show:
- All participants.
- Assigned words.
- Placed/unplaced status.
- Surface types.
- Pairings.
- Group chains.
- Final story button.

### Step 11 — Generate final story
Use:
- Group sentences.
- Participant reflections.
- The workshop title.
- A short prompt for AI generation.

Example AI prompt:

> Create a poetic speculative story from these five group sentences. The story should feel like AR graffiti coming alive across a city wall. It should include themes of memory, public space, technology, and collective authorship. Keep it under 300 words.

### Step 12 — Display final AR mural
Create:
- Final story as large floating text.
- All participant words orbiting or forming a wall.
- Optional audio narration.
- Screenshot/video capture moment.

### Step 13 — Document the outcome
Collect:
- Screenshots.
- Final generated story.
- Word chains.
- Participant reflections.
- Photos of people using the app.
- Short written summary for deliverable/report.

---

## Workshop Abstract Draft
### 150–300 Words

**The Invisible Wall: Digital Graffiti and the Future of Immersive Storytelling**

This workshop explores phone-based augmented reality as a future form of public storytelling. Using a browser-based AR application, each participant receives a randomly assigned word that appears as floating digital graffiti in the physical environment. Participants then move through the space, placing their word onto walls, surfaces, thresholds, and architectural details. Each placement transforms the word visually and narratively, suggesting that the surrounding environment is not just a backdrop but an active storytelling partner.

Through a sequence of collaborative exercises, participants connect their AR graffiti with others, forming phrases, poetic fragments, and short speculative narratives. Small groups combine their words into larger story chains, which are then gathered into one collective AR mural or final immersive poem.

The workshop asks what happens when graffiti becomes spatial, animated, temporary, and networked. Who has the right to write on digital public space? Can augmented reality become a tool for community memory, protest, imagination, and collective authorship? What kinds of immersive storytelling are realistic with today’s phones, and what might become possible when persistent AR and AI are embedded into everyday environments?

By the end, participants will have created a shared augmented story that exists between the physical site, the phone screen, and the collective imagination of the group.

---

## Short Email Reply Draft

Hi Jo,

I would like to propose a phone-based augmented reality workshop called **The Invisible Wall: Digital Graffiti and the Future of Immersive Storytelling**.

In the workshop, each of the 25 participants receives a randomly assigned word through a WebAR app. The word appears as floating digital graffiti in the physical environment. Participants then place their word onto walls, surfaces, thresholds, or objects, where it transforms visually and narratively depending on the environment. The words are later combined in pairs and small groups to create poetic story chains, eventually forming one collective AR mural or immersive narrative.

The workshop uses digital graffiti as a way to discuss public space, authorship, memory, and the future of immersive storytelling. It asks what happens when every wall can hold invisible stories, and when AR allows people to write temporary, animated, collaborative layers onto reality.

Technically, the workshop can be built with a browser-based AR app, using phone-based spatial placement, simple environmental prompts, and optional computer vision or image-target triggers. The focus is both practical and speculative: what is possible today with accessible tools, what may be possible in the near future, and what ethical or creative limits we should consider.

Best,
Kris

---

## Key Takeaway

The strongest version of this idea is not just an AR tech demo. It is a participatory storytelling system.

Each participant receives a word.  
Each word becomes graffiti.  
Each graffiti mark becomes a fragment.  
Each fragment connects to others.  
The room becomes a page.  
The group becomes the author.  
The final story exists only because everyone moved through the space together.
