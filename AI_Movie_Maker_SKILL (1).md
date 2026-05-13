---
name: ai-cinematic-movie-maker
description: Transform any story idea into a full cinematic AI-generated movie using Claude (script), Image 2.0 (storyboards), and Seedance (video generation). Use this skill whenever the user wants to create an AI movie, film, short video, cinematic reel, or animated story. Includes proven scene prompt templates with timecodes, camera language, realism rules, and negatives for every scene. Trigger when user mentions movie, film, Seedance, cinematic, storyboard, scene prompts, or AI video generation.
version: 1.0.0
author: "@growithkaran_"
trigger: Use when the user wants to create an AI movie, cinematic video, or scene prompts for Seedance. Also trigger for any story-to-video workflow using Claude + Image 2.0 + Seedance.
---

# AI Cinematic Movie Maker
**Skill for Claude — Developed by @growithkaran_**

---

## Overview

This skill transforms any story idea into a full cinematic AI-generated movie using a three-tool pipeline:

1. **Claude** — writes the full script and scene-by-scene Seedance prompts
2. **Image 2.0** — generates character storyboard frames from the script
3. **Seedance** — animates storyboard frames into real cinematic video clips

This exact workflow and prompt structure produced a 1-minute 13-second Action Romance film with ultra-realistic cinematic quality.

---

## How to Use This Skill

When the user gives Claude a story idea, Claude will:

1. Write the full narrative script
2. Break it into scenes (each 10–15 seconds)
3. Generate a Seedance prompt for every scene using the exact structure below
4. Specify character lock details for Image 2.0 storyboard generation

**Always follow the Scene Prompt Structure exactly. Do not skip any section.**

---

## Core Principles

### The Three Non-Negotiables
- **Ultra-realistic cinematic only** — no 3D, no cartoon, no VFX look
- **Timecoded sequences** — every scene must have second-by-second breakdown
- **Geography lock** — camera position and character placement must be consistent across all scenes

### Tone & Style
- Grounded Bollywood mass cinematic
- Handheld realism with selective slow-motion
- Practical lighting only — no artificial glow or stylized effects
- TRUE 16:9 widescreen format at all times

---

## Scene Prompt Structure

Every scene prompt must follow this exact structure. Never remove a section.

```
Scene [NUMBER] — [LOCATION] — [SCENE TITLE] ([DURATION]s)

STYLE & LOOK
─────────────────────────────────────────────────────
STYLE:     [Cinematic style description]
COLOR:     [Lighting palette and contrast direction]
LENS:      [Focal length, depth of field, grain]

CHARACTER LOCK (include in every scene)
─────────────────────────────────────────────────────
[Character 1 description — hair, clothing, build, expression energy]
[Character 2 description — hair, clothing, build, expression energy]
Note: Supply both character reference images to Seedance with every prompt.

ENVIRONMENT
─────────────────────────────────────────────────────
[Location details, spatial geography, lighting setup, atmosphere]

TIMECODED SEQUENCE
─────────────────────────────────────────────────────
[Start time] – [End time] · BEAT TITLE
CAMERA:    [Shot type, angle, movement]
ACTION:    [What happens in the frame]
DETAIL:    [Micro-moments, physics, expression, sound implied]
IMPORTANT: [Critical notes for this beat]

[Repeat for every beat in the scene]

CAMERA LANGUAGE
─────────────────────────────────────────────────────
• Start: [Camera energy at scene open]
• Mid:   [Camera energy during scene]
• End:   [Camera energy at scene close]

REALISM RULES
─────────────────────────────────────────────────────
• [Rule 1]
• [Rule 2]
• [Rule 3]
[Add as many as needed]

CONTINUITY RULES (for scenes 2 onwards)
─────────────────────────────────────────────────────
• [What must carry over from the previous scene]
• [Hair, sweat, breath, momentum, clothing state]
• [No resets — motion must feel continuous]

NEGATIVES — DO NOT INCLUDE
─────────────────────────────────────────────────────
• [What to exclude 1]
• [What to exclude 2]
• [What to exclude 3]
[Add as many as needed]
```

---

## Proven Scene Library

The following 6 scenes are the exact prompts that produced the @growithkaran_ Action Romance movie. Use these as templates for any action-romance story.

---

### Scene 1 — Bar — Threat & First Escape (15s)

```
STYLE & LOOK
─────────────────────────────────────────────────────
STYLE:  Ultra-realistic cinematic, TRUE 16:9 widescreen, grounded lighting,
        handheld realism. No 3D, no cartoon, no VFX look.
COLOR:  Warm amber bar lighting vs deep shadow contrast.
        Shift toward cold blue in the final beat.
LENS:   35mm → 50mm close tension shots.
        Shallow depth of field, subtle grain.

ENVIRONMENT
─────────────────────────────────────────────────────
Luxury bar interior. Chandelier, leather seating, warm amber glow.
Girl already at the bar holding a drink when scene opens.
Background: ambient crowd, one drunk guy still dancing — oblivious throughout.

TIMECODED SEQUENCE
─────────────────────────────────────────────────────
0:00 – 0:02 · QUICK ESTABLISH — NO DRAG
CAMERA:    Wide shot → fast push-in.
ACTION:    Luxury bar interior establishing. Girl at bar, drink in hand.
DETAIL:    Do not linger — immediate movement toward her from frame edges.
IMPORTANT: No slow opening. Energy must start moving immediately.

0:02 – 0:04 · THREAT ARRIVES FAST
CAMERA:    Over-shoulder framing.
ACTION:    3–4 goons enter frame behind her.
DETAIL:    Aggressive body language, scanning room. One locks eyes instantly.
CUT:       Sharp cut out of this beat.

0:04 – 0:05 · REALIZATION
CAMERA:    Tight close-up on her face.
ACTION:    Micro expression shift — calm → alert. Very subtle.
DETAIL:    Eyes flick slightly. Breathing tightens. From here — no more calm.

0:05 – 0:08 · INVASION OF SPACE
CAMERA:    Handheld medium shot — tight, uncomfortable framing.
ACTION:    Goons close in fast.
DETAIL:    One leans too close. One blocks the exit. One circles slightly.
MICRO:     She places the glass down hard.
SOUND:     Music drops → low tension hum begins.
VISUAL:    Background — drunk guy still dancing, oblivious.

0:08 – 0:11 · BREAK + CHAOS
CAMERA:    Sudden snap to fast handheld tracking.
ACTION:    She shoves past one goon and runs.
PHYSICS:   Chair scrapes loudly. Glass rattles. One goon stumbles into furniture.
DETAIL:    Jacket swings violently. Hair whipping with speed.
BACKGROUND: People react late — turning heads, moving aside.

0:11 – 0:13 · CHASE PRESSURE
CAMERA:    Tracking behind her — tight, shaky.
ACTION:    She sprints toward the exit.
DETAIL:    Footsteps heavy. Breath quick and shallow. Goons visible behind, closing.
LIGHT:     Warm tones fading rapidly.

0:13 – 0:15 · DARK EXIT + HOOK END
CAMERA:    Front-facing as she reaches the doorway → slight slow-motion (last 0.7s).
ACTION:    She stops for a half-beat and looks back.
DETAIL:    Goons enter frame behind her as silhouettes.
LIGHT:     Cold blue corridor vs warm bar behind.
FINAL:     She disappears into darkness mid-motion.
           End on empty doorway with echoing footsteps.

CAMERA LANGUAGE
─────────────────────────────────────────────────────
• Start: controlled push
• Mid:   unstable handheld
• End:   aggressive shake + slight motion blur

REALISM RULES
─────────────────────────────────────────────────────
• No exaggerated fight choreography
• All movement grounded and urgent
• Extras react naturally — not staged
• Fabric and hair respond to motion realistically
• Lighting must transition physically — not via stylized fade

NEGATIVES — DO NOT INCLUDE
─────────────────────────────────────────────────────
• No slow pacing in the beginning
• No overdramatic acting
• No stylized nightclub look
• No cinematic slow-mo except the final 0.7s beat
• No artificial lighting effects
• No action-hero choreography
```

---

### Scene 2 — Corridor — Capture (10s)

```
STYLE & LOOK
─────────────────────────────────────────────────────
STYLE:   Ultra-realistic cinematic, TRUE 16:9 widescreen, grounded lighting,
         handheld realism. No 3D, no cartoon, no artificial VFX.
LIGHTING: Cold blue corridor lighting with fading warm bar spill behind.
          High contrast, practical sources only.
LENS:    35mm for movement → 50mm for impact and face.

ENVIRONMENT
─────────────────────────────────────────────────────
Narrow corridor directly connected to bar from Scene 1.
Doors streak past. Lights flicker subtly. Tight space.

CONTINUITY RULES
─────────────────────────────────────────────────────
• Same running momentum from Scene 1 — no pause, no reset
• Hair already in motion, breathing already heavy
• Warm tones from bar fading as cold blue takes over
• No delay in goon reaction — they are already close

TIMECODED SEQUENCE
─────────────────────────────────────────────────────
0:00 – 0:02 · CONTINUOUS ENTRY — NO RESET
CAMERA:    Handheld tracking from behind.
ACTION:    She bursts into the corridor mid-run, continuing from bar.
DETAIL:    Same motion, no pause. Hair already in motion. Breathing heavy.
LIGHT:     Warm fades → cold blue dominates immediately.

0:02 – 0:04 · FAST CORRIDOR RUN
CAMERA:    Side tracking + slight handheld shake.
ACTION:    She runs through the narrow hallway.
DETAIL:    Hand brushes wall for balance. Footsteps echo sharply. Slight stumble
           with immediate recovery. Doors streak past.

0:04 – 0:06 · PRESSURE CLOSES IN
CAMERA:    Front tracking — camera moving backward as she runs toward it.
ACTION:    She runs toward camera.
INSERT CUTS: Her eyes (fear tightening), foot impact on floor, quick glance back.
BACKGROUND: Goons now much closer. Breathing and footsteps syncing behind.

0:06 – 0:08 · SUDDEN GRAB — IMPACT SLOW-MO
CAMERA:    Side angle → slight slow-motion ramp.
ACTION:    A goon lunges from a side corridor and grabs her arm.
PHYSICS:   Her forward momentum snaps sharply — body jerks forward then halts.
DETAIL:    Hair whips across face. Fingers tense as she resists.
IMPORTANT: Keep it sharp — not floaty.

0:08 – 0:09.5 · FULL RESTRAINT
CAMERA:    Tight medium, slight orbit.
ACTION:    Two more goons close in instantly.
DETAIL:    One grabs the other arm. One blocks the path.
MICRO:     She struggles briefly — short, real resistance.
EXPRESSION: Shock → anger → panic.

0:09.5 – 0:10 · FINAL HOLD
CAMERA:    Tight close-up on her face.
ACTION:    She stops struggling for a split second.
DETAIL:    Goons blurred around her.
EXPRESSION: Defiant + trapped.
END FRAME: Hold on her eyes.

CAMERA LANGUAGE
─────────────────────────────────────────────────────
• Start: fast and chaotic
• Mid:   tightening pressure
• Impact: controlled slow-motion
• End:   locked tension

NEGATIVES — DO NOT INCLUDE
─────────────────────────────────────────────────────
• No full-sequence slow motion
• No floating physics
• No exaggerated stunt reactions
• No cinematic hero style
• No pause before the grab
• No scene reset from Scene 1
```

---

### Scene 3 — Hero Entry — Mass Reveal (15s)

```
STYLE & LOOK
─────────────────────────────────────────────────────
STYLE:    Ultra-realistic Bollywood mass cinematic. TRUE 16:9 widescreen.
          240fps interpreted slow-motion with selective speed ramps.
          No 3D, no cartoon, no artificial glow VFX.
LIGHTING: Cold blue corridor + harsh overhead practical strips.
          Hard shadows, directional light slices.
          Warm skin tones cutting through cold environment.
LENS:     Mix of 85mm compression (hero moments) + 35mm dynamic tracking.
          Shallow depth of field, subtle film grain.

CHARACTER LOCK — HERO
─────────────────────────────────────────────────────
• Indian male, mid-30s
• Short black hair — slight movement with air only
• Light stubble, sharp jawline
• Black suit + black shirt, top buttons open
• No sunglasses
• Expression: charming, controlled, confident — no smile but full presence

ENVIRONMENT
─────────────────────────────────────────────────────
Same narrow corridor as Scene 2.
Heroine + goons far in the background — blurred initially.
Overhead lights flicker slightly.
Spatial geometry: Hero at one end, heroine + goons at the far opposite end.

TIMECODED SEQUENCE
─────────────────────────────────────────────────────
0:00 – 0:02 · IMPACT BOOT ENTRY — MASS START
CAMERA:    Low-angle macro cuts.
ACTION:    Boot steps into frame → heavy impact. Second step follows.
DETAIL:    Heel → toe roll. Subtle dust shift. Faint echo in corridor.
CUT STYLE: Quick rhythmic cuts — punchy beats, not fast-editing chaos.
SOUND:     Each step = a distinct thump moment.

0:02 – 0:04 · SIDE POWER WALK
CAMERA:    Side dolly tracking parallel to him (35mm).
ACTION:    Hero walks with controlled swagger.
           One hand adjusts sleeve or loosens wrist subtly.
DETAIL:    Jacket moves with stride. Shoulders relaxed, dominant presence.
AIR:       Natural corridor airflow lifts hair slightly — not stylized wind.

0:04 – 0:06 · BODY LANGUAGE HERO BEAT
CAMERA:    Slow push-in.
ACTION:    He slightly rolls his shoulder. Fingers flex once, releasing tension.
DETAIL:    Veins, knuckles, fabric tension all visible.

0:06 – 0:08 · BACK HERO SHOT — ICONIC
CAMERA:    Behind him, centered frame.
ACTION:    He walks toward the distant figures — heroine + goons.
DETAIL:    Corridor stretching infinitely. Symmetry building. Overhead lights
           passing over him one by one.

0:08 – 0:10 · TOP SHOT POWER MOMENT
CAMERA:    Top-down ceiling perspective.
ACTION:    Hero crosses under light strips. Shadow elongates dramatically.
DETAIL:    Movement clean, no rush. Spatial dominance clear.

0:10 – 0:12 · FACE TEASE — NOT FULL REVEAL
CAMERA:    85mm tight side angle.
ACTION:    He slightly tilts his head.
DETAIL:    Light slices across cheek → eye partially visible.
EXPRESSION: Charming, controlled, confident — presence without showing everything.

0:12 – 0:14 · FULL HERO REVEAL — WHISTLE MOMENT
CAMERA:    Front tracking, slow push.
ACTION:    He steps fully into the light.
DETAIL:    Eyes sharp. Hair subtly moving. Face now fully visible.
IMPORTANT: This is THE mass moment. Treat it accordingly.

0:14 – 0:15 · LOCK + STAREDOWN
CAMERA:    Wide symmetrical corridor shot.
ACTION:    Hero stops walking. Holds the gaze across the corridor.
HER:       Slight emotional shift — relief + disbelief.
GOONS:     Tension spike — subtle shift in stance. No action yet.
FINAL:     Hero in light, others in shadow, distance fully intact. Cut.

CAMERA LANGUAGE
─────────────────────────────────────────────────────
• Start: punchy impact cuts — mass energy
• Middle: flowing tracking shots — building presence
• End: slow, dominant stillness — authority

MASS CINEMA RULES
─────────────────────────────────────────────────────
• Entry is rhythmic — step → cut → movement → reveal
• Body language sells power — not speed
• Light reveals him progressively — not instantly
• Each beat must feel like it could be a poster frame

REALISM RULES
─────────────────────────────────────────────────────
• Airflow subtle — not a dramatic wind machine
• Fabric and hair respond naturally to movement
• Footsteps grounded and weighted
• No exaggerated slow-motion floating

NEGATIVES — DO NOT INCLUDE
─────────────────────────────────────────────────────
• No sunglasses
• No over-blown wind effect
• No artificial glow or halo
• No superhero posing
• No fast chaotic editing
• No VFX lighting
• No exaggerated expressions
```

---

### Scene 4 — Hallway Fight — Geography Lock (15s)

```
STYLE & LOOK
─────────────────────────────────────────────────────
STYLE:    Ultra-realistic cinematic, grounded Bollywood action.
          No 3D, no stylization, no fake choreography.
LIGHTING: Cold blue corridor lighting. High contrast shadows.
CAMERA:   Handheld operator — physically constrained movement throughout.

SPATIAL GEOGRAPHY — CRITICAL — LOCK THIS
─────────────────────────────────────────────────────
Corridor straight line:
[ HERO ] ────────────────── [ GOONS ] ────── [ HEROINE ]

• Hero alone at one end facing forward
• Heroine at opposite end — being held by goons
• Goons between hero and heroine — slightly closer to heroine
• All movement happens along this single axis
• AT NO POINT is anyone behind the hero

TIMECODED SEQUENCE
─────────────────────────────────────────────────────
0:00 – 0:02 · HERO LOCK-IN
CAMERA:    Front-facing medium shot of hero walking slowly forward.
DETAIL:    Shoulders relaxed but controlled. Eyes locked ahead. Subtle jaw tension.
CAMERA MOVE: Slow backward handheld drift — maintaining distance from him.

0:02 – 0:03 · THREAT ADVANCES
CAMERA:    From hero's POV axis — goons moving toward him.
IMPORTANT: We see their backs as they approach.
           Heroine visible between their shoulders — depth layering.
DETAIL:    One goon still gripping her arm.

0:03 – 0:09 · ONE-TAKE FIGHT — AXIS PRESERVED
CAMERA:    Starts slightly behind hero → orbits in semicircle during fight.
           Not full spin — geography must remain intact.

BEAT 1:    First goon lunges. Hero steps slightly sideways (not dramatic).
           Short punch → impact → goon stumbles sideways (not flying).

BEAT 2:    Second goon grabs from front. Brief struggle — important.
           Hero breaks grip → elbow to face.

CAMERA SHIFT: Operator moves right — revealing heroine clearly in background.
             She is still at the opposite end — not behind hero.

BEAT 3:    Third goon charges. Collision → both bodies compress into frame.
           Hero drives him into wall using body weight only.

DETAIL:    Tight hits. Imperfect timing. Breath, friction, and resistance visible.

0:09 – 0:11 · SPACE REVEAL — KEY MOMENT
CAMERA:    Completes orbit → positioned slightly behind fallen goons.
VISUAL:    Hero foreground. Heroine clearly visible in front of him on same axis.
           Distance still maintained.
NOTE:      This is where geography becomes crystal clear to viewer.

0:11 – 0:13 · CONNECTION
ACTION:    Hero walks toward her slowly. She steps forward slightly.
IMPORTANT: They close distance but do not fully collapse into each other.
MICRO:     Eye contact. Breath stabilizing. Subtle emotional shift.

0:13 – 0:15 · INTERRUPTED RESOLVE
ACTION:    Sound from behind her side — same direction goons came from.
           Both react instantly.
CAMERA:    Quick glance past her shoulder → more silhouettes entering.
FINAL:     Hero reaches her. Grabs her hand. Both turn toward escape direction.
           Cut mid-motion.

CAMERA RULES
─────────────────────────────────────────────────────
• No teleporting positions between beats
• Orbit must feel physically possible in a narrow hallway
• Maintain axis awareness at all times
• Reveal heroine only through rotation — not cheating cuts

REALISM ENFORCEMENT
─────────────────────────────────────────────────────
• No flying bodies
• No stylized spins
• No clean choreography rhythm
• Allow pauses, friction, imbalance
• Impacts are short, brutal, and efficient
• Breath and fatigue must be visible

NEGATIVES — DO NOT INCLUDE
─────────────────────────────────────────────────────
• No one behind the hero — ever
• No cross-axis breaking
• No cinematic slow-motion during the fight
• No over-dramatic action
• No symmetrical staging
• No fake stunt physics
```

---

### Scene 5 — Stairwell Escape — Gunfire & Garage (15s)

```
STYLE & LOOK
─────────────────────────────────────────────────────
STYLE:    Ultra-realistic cinematic, grounded chase physics.
          No 3D, no stylization, no slow-floating debris.
LIGHTING: Cold blue corridor → warm industrial garage contrast.
CAMERA:   Handheld chase + controlled slow-motion transition.

CONTINUITY LOCK — FROM SCENE 4
─────────────────────────────────────────────────────
• Same narrow hallway — hero and heroine already running together
• Hero pulling her by the hand — motion already in progress
• Threat is behind them — gunmen entering corridor
• No reset in posture, momentum, or emotional state

TIMECODED SEQUENCE
─────────────────────────────────────────────────────
0:00 – 0:03 · CORRIDOR SPRINT
CAMERA:    Rear tracking shot — camera behind them at shoulder height.
ACTION:    Both running full speed. Hero slightly ahead, pulling her by the hand.
DETAIL:    Foot impacts heavy. Breath audible. Jacket and hair reacting to motion.
CAMERA FEEL: Handheld chase, slight shake, tight space compression.

0:03 – 0:05 · STAIR DOOR BREAK-IN
ACTION:    Hero slams open a heavy metal door — push force visible.
           Door rebounds slightly (important physics detail).
CAMERA:    Quick whip-pan as door swings open → reveals stairwell.
LIGHT:     Shift from cold blue corridor → dim yellow stairwell practical lights.

0:05 – 0:08 · DESCENT + GUNFIRE
CAMERA:    Top-down + angled tracking as they run down stairs.
ACTION:    Fast descent — not jumping unrealistically.
DETAIL:    Footsteps echo. Slight slips on turns.
GUNSHOTS:  Bullets hit wall behind them — sparks, concrete chips.
           Sound echoes sharply in enclosed space.
REACTION:  Hero pulls her sideways. Both drop behind stair landing wall.
END BEAT:  Crouching low, breathing hard, bullets hitting above.

0:08 – 0:09 · DECISION BEAT
MICRO:     Quick eye contact. Hero nods slightly — 'move now.'
DIALOGUE:  None.

0:09 – 0:13 · ULTRA SLOW-MO RUN — 240fps FEEL
CAMERA:    Controlled slow-motion tracking — side + slight front angle.
ACTION:    They burst from cover and continue descending.
           Bodies leaning forward, momentum-driven.
DETAIL:    Bullet impacts near feet — dust kicks up.
           Subtle flinch reactions — not exaggerated dodging.
MOVEMENT:  Realistic zig-zag foot placement.
           Hands connected 1–2 steps then released for balance.
LIGHT:     Stairwell → garage entrance, warmer sodium light spill beginning.

0:13 – 0:15 · GARAGE ENTRY + BIKE REACH
CAMERA:    Wide reveal of underground garage.
ACTION:    They sprint toward parked bike — foreground right or center.
           Hero reaches first, swings leg over. She gets on behind him quickly.
IMPORTANT: No instant teleport mounting. Slight fumbling realism allowed.
FINAL:     Both seated on the bike. Engine not started yet.
           Tension still alive — threat behind. Cut.

CAMERA LANGUAGE
─────────────────────────────────────────────────────
• Start: chaotic handheld chase
• Mid:   reactive whip + vertical stairwell movement
• End:   controlled cinematic slow-motion

REALISM DETAILS
─────────────────────────────────────────────────────
• Door weight and hinge resistance must be visible
• Stair descent foot rhythm — no floating steps
• Bullets hit environment only — not clean misses
• Breathing and fatigue visible throughout
• Clothing reacts to movement and air drag

NEGATIVES — DO NOT INCLUDE
─────────────────────────────────────────────────────
• No superhero dodging
• No slow floating debris
• No instant bike-mount teleport
• No over-stylized slow motion
• No acrobatics on stairs
• No unrealistic bullet timing
```

---

### Scene 6 — Mumbai Bike Chase — Streets at Night (15s)

```
STYLE & LOOK
─────────────────────────────────────────────────────
STYLE:    Ultra-realistic cinematic chase, Mumbai night realism.
          Mixed-speed cinematography — real-time bursts + 240fps slow-motion accents.
          No 3D, no stylized VFX, no arcade driving.
LOOK:     Warm sodium streetlights. Wet asphalt reflections. Traffic density.
CAMERA:   Mounted tracking + low chase vehicle + side glide shots.
          Occasional handheld vibration for realism.

CONTINUITY LOCK — FROM SCENE 5
─────────────────────────────────────────────────────
• Same hero + heroine on the bike from the garage escape
• She is seated behind him — holding firmly around his waist
• Threat vehicles behind — 2–3 cars, headlights visible
• Engine already running — no startup sequence needed

ENVIRONMENT
─────────────────────────────────────────────────────
Mumbai night streets — real traffic density.
Taxis, autos, buses, civilian cars.
Wet asphalt reflecting streetlights.
Must feel like actual Mumbai — not empty roads.

TIMECODED SEQUENCE
─────────────────────────────────────────────────────
0:00 – 0:02 · HARD START — REAL-TIME BURST
CAMERA:    Side tracking shot — bike already in motion.
ACTION:    Bike accelerates aggressively into Mumbai street traffic.
           Engine vibration visible in frame.
DETAIL:    Her grip tightens instantly. His focus sharp, leaning forward.
ENVIRONMENT: Night traffic, taxis, autos, buses. Streetlights streaking.

0:02 – 0:05 · TRAFFIC WEAVE — SLOW-MO ACCENT
CAMERA:    Low front 3/4 angle tracking.
ACTION:    He threads between two moving cars — tight gap.
           Handlebars pass close to mirrors.
SLOW-MO:   Her hair trailing in wind. Tire rolling with visible grip.
           Suspension compression visible.
REALISM:   Small steering corrections — not perfect straight lines.

0:05 – 0:07 · THREAT REVEAL
CAMERA:    Rear-facing angle from bike.
ACTION:    Headlights of pursuing cars appear.
           One passenger leans slightly out a window.
GUNSHOT:   Single shot fired → sparks off the road behind the bike.
IMPORTANT: No bullet trails — only impact feedback.

0:07 – 0:10 · HIGH-SPEED PASS + BULLET PRESSURE
CAMERA:    Side tracking → quick over-shoulder.
ACTION:    Bike overtakes a slow truck or bus. He leans hard left → cuts into lane.
GUNFIRE:   2–3 shots hit nearby metal surfaces — car door, road divider.
REACTION:  She ducks slightly behind him. He adjusts line — not exaggerated swerving.

0:10 – 0:12 · STYLE MOMENT — CONTROLLED SLOW-MO
CAMERA:    Front low-angle shot of bike.
ACTION:    He leans into a turn under streetlight.
DETAIL:    Light sweeps across both faces.
HER EXPRESSION: Fear → trust.
HIS EXPRESSION: Calm control.

0:12 – 0:14 · CLOSE CALL
ACTION:    Car suddenly cuts lane ahead. He brakes + swerves narrowly past.
PHYSICS:   Front suspension dips under braking. Slight rear wobble before recovery.
SOUND:     Tire friction and engine rev drop implied.

0:14 – 0:15 · ESCAPE MOMENT
CAMERA:    Rear wide shot.
ACTION:    Bike shoots ahead into darker stretch of road.
           Pursuing headlights fall slightly behind.
FINAL:     Taillight streak moving into distance. City lights glowing. Cut.

CAMERA LANGUAGE
─────────────────────────────────────────────────────
• Blend real-time for urgency + slow-motion for hero beats
• Keep camera on physically plausible rigs only
• No impossible drone flips in tight traffic

REALISM DETAILS
─────────────────────────────────────────────────────
• Traffic behaves independently — no perfect gaps opening for the bike
• Small steering jitter at high speed
• Body weight shifts affect bike motion visibly
• No frictionless gliding
• Gunfire is sparse and threatening — not constant spray

NEGATIVES — DO NOT INCLUDE
─────────────────────────────────────────────────────
• No stylized drifting
• No bike flying or jumping
• No bullet slow-motion trails
• No empty roads — must feel like Mumbai
• No perfect choreography between vehicles
```

---

## Assembly Instructions

```
FINAL EDIT ORDER
─────────────────────────────────────────────────────
Scene 1 → Scene 2 → Scene 3 → Scene 4 → Scene 5 → Scene 6

Total runtime: ~1 min 25 sec (6 scenes × 10–15s each)

EDITING NOTES
─────────────────────────────────────────────────────
• Run scenes sequentially — supply both character images to Seedance with every prompt
• Edit resulting clips together maintaining continuity of motion, lighting, and emotional state
• Scene transitions: cut on motion — never cut on stillness
• Music: build from tension (Scene 1–2) → silence (Scene 3 entry) → impact beats (Scene 4) → chase score (Scene 5–6)
• No fades between scenes — hard cuts only except Scene 3 entry
```

---

## How to Adapt This Skill for Any Story

To create a completely different story using this structure:

1. Give Claude your story idea and genre
2. Claude will write the narrative script
3. Claude will map it into scenes (each 10–15 seconds)
4. For each scene Claude will fill in the prompt structure above:
   - Keep: Style & Look, Timecoded Sequence, Camera Language, Realism Rules, Negatives
   - Change: The actual content inside each section for your story
5. Generate storyboard images in Image 2.0 using the character descriptions
6. Feed each scene prompt + both character images into Seedance
7. Edit clips together in sequence

**The structure does the work. The words inside it are swappable.**

---

## Prompt Claude with This

```
Use the AI Cinematic Movie Maker skill.
My story: [DESCRIBE YOUR STORY IN ONE PARAGRAPH]
Genre: [ACTION / ROMANCE / THRILLER / COMEDY / DRAMA]
Hero description: [AGE, LOOK, CLOTHING, ENERGY]
Heroine/co-character description: [AGE, LOOK, CLOTHING, ENERGY]
Setting: [CITY, TIME OF DAY, LOCATIONS]
Number of scenes: [HOW MANY]

Generate all scene prompts following the exact skill structure.
Include timecodes, camera language, realism rules, and negatives for every scene.
```

---

*Skill developed by @growithkaran_ | AI + Digital Marketing*
*Comment "Movie" on the reel to get this skill file free*
