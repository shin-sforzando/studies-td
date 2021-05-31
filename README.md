# studies-td

![screenshot](https://user-images.githubusercontent.com/32637762/120210822-3025b980-c26b-11eb-84a8-c70f32d68479.png)

Some studies using [TouchDesigner](https://derivative.ca).

- [Study Environments](#study-environments)
- [Works](#works)
- [Ideas](#ideas)
- [Experienced operators](#experienced-operators)
  - [COMP](#comp)
    - [Object Components (3D objects for rendering)](#object-components-3d-objects-for-rendering)
    - [Panel Components (interactive 2D panels)](#panel-components-interactive-2d-panels)
    - [Miscellaneous Components](#miscellaneous-components)
  - [TOP](#top)
  - [CHOP](#chop)
  - [SOP](#sop)
  - [MAT](#mat)
  - [DAT](#dat)
- [References](#references)

## Study Environments

- TouchDesigner Commercial (099, build 2021.13610 or higher)
  - Intel MacOS 11 (Big Sur)
  - Windows 10 Home with Nvidia GTX2080

## Works

(T.B.D.)

## Ideas

- [ ] Calibration of multiple projectors
- [ ] Slit Camera
- [ ] Autonomous Drone

## Experienced operators

### COMP

#### Object Components (3D objects for rendering)

- [ ] Ambient Light COMP
- [ ] Blend COMP
- [ ] Bone COMP
- [ ] Camera COMP
- [ ] Camera Blend COMP
- [ ] Environment Light COMP
- [ ] Nvidia Flow Emitter COMP
- [ ] Geometry COMP
- [ ] Handle COMP
- [ ] Light COMP
- [ ] Null COMP
- [ ] Shared Mem In COMP
- [ ] Shared Mem Out COMP
- [ ] FBX COMP
- [ ] USD COMP

#### Panel Components (interactive 2D panels)

- [ ] Button COMP
- [ ] Container COMP
- [ ] Field COMP
- [ ] List COMP
- [ ] OP Viewer COMP
- [ ] Parameter COMP
- [ ] Select COMP
- [ ] Slider COMP
- [ ] Table COMP
- [ ] Widget COMP

#### Miscellaneous Components

- [ ] Base COMP
  - the Base COMP has no panel gadgets and no object gadgets. It is the most basic shell of a component and can be used when a new network is required.
- [ ] Engine COMP
  - the Engine COMP will run a .tox file (component) in a separate process.
- [ ] Time COMP
  - the Time COMP contains a network of operators that can drive a Timeline, drive animations in Animation COMPs, or be used to drive any custom time-based system.
- [ ] Animation COMP
  - the Animation COMP is used to create keyframe animation data. Keyframed channels are stored inside the component and can be edited by scoping the Animation COMP in the Animation Editor.
- [ ] Replicator COMP
  - the Replicator COMP creates a node for every row of a table, adding and deleting nodes ("replicants") as the table changes.
- [ ] Window COMP
  - the Window COMP create a separate floating application window. This can be used for control panels or when outputting to multiple monitors.

### TOP

- [ ] Add
- [ ] Analyze
- [ ] Anti Alias
- [ ] Blob Track
- [ ] Blur
- [ ] Cache Select
- [ ] Cache
- [ ] Channel Mix
- [ ] CHOP to
- [ ] Chroma Key
- [ ] Circle
- [ ] Composite
- [ ] Constant
- [ ] Convolve
- [ ] Corner Pin
- [ ] CPlusPlus
- [ ] Crop
- [ ] Cross
- [ ] Cube Map
- [ ] Depth
- [ ] Difference
- [ ] DirectX In
- [ ] DirectX Out
- [ ] Displace
- [ ] Edge
- [ ] Emboss
- [ ] Feedback
- [ ] Fit
- [ ] Flip
- [ ] Function
- [ ] GLSL Multi
- [ ] GLSL
- [ ] HSV Adjust
- [ ] HSV to RGB
- [ ] Import Select
- [ ] In
- [ ] Inside
- [ ] Introduction To s Vid
- [ ] Kinect Azure Select
- [ ] Kinect Azure
- [ ] Kinect
- [ ] Layout
- [ ] Leap Motion
- [ ] Lens Distort
- [ ] Level
- [ ] Limit
- [ ] Lookup
- [ ] Luma Blur
- [ ] Luma Level
- [ ] Math
- [ ] Matte
- [ ] Mirror
- [ ] Monochrome
- [ ] Movie File In
- [ ] Movie File Out
- [ ] Multiply
- [ ] Ncam
- [ ] NDI In
- [ ] NDI Out
- [ ] Noise
- [ ] Normal Map
- [ ] Notch
- [ ] Null
- [ ] Nvidia Background
- [ ] Nvidia Denoise
- [ ] Nvidia Flex
- [ ] Nvidia Flow
- [ ] Oculus Rift
- [ ] OP Viewer
- [ ] OpenColorIO
- [ ] OpenVR
- [ ] Ouster Select
- [ ] Ouster
- [ ] Out
- [ ] Outside
- [ ] Over
- [ ] Pack
- [ ] Photoshop In
- [ ] Point File In
- [ ] Point File Select
- [ ] Point Transform
- [ ] PreFilter Map
- [ ] Projection
- [ ] Ramp
- [ ] RealSense
- [ ] Rectangle
- [ ] Remap
- [ ] Render Pass
- [ ] Render Select
- [ ] Render
- [ ] Reorder
- [ ] Resolution
- [ ] RGB Key
- [ ] RGB to HSV
- [ ] Scalable Display
- [ ] Screen Grab
- [ ] Screen
- [ ] Script
- [ ] Select
- [ ] Shared Mem In
- [ ] Shared Mem Out
- [ ] Slope
- [ ] Spectrum
- [ ] SSAO
- [ ] Stype
- [ ] Substance Select
- [ ] Substance
- [ ] Subtract
- [ ] SVG
- [ ] Switch
- [ ] Syphon Spout In
- [ ] Syphon Spout Out
- [ ] Text
- [ ] Texture 3D
- [ ] Texture Sampling Parameters
- [ ] Threshold
- [ ] Tile
- [ ] Time Machine
- [ ] TOP
- [ ] TOP Viewer
- [ ] Touch In
- [ ] Touch Out
- [ ] Transform
- [ ] Under
- [ ] Video Device In
- [ ] Video Device Out
- [ ] Video Stream In
- [ ] Video Stream Out
- [ ] Vioso
- [ ] Web Render
- [ ] ZED

### CHOP

- [ ] Ableton Link
- [ ] Analyze
- [ ] Angle
- [ ] Attribute
- [ ] Audio Band EQ
- [ ] Audio Device In
- [ ] Audio Device Out
- [ ] Audio Dynamics
- [ ] Audio File In
- [ ] Audio File Out
- [ ] Audio Filter
- [ ] Audio Movie
- [ ] Audio NDI
- [ ] Audio Oscillator
- [ ] Audio Para EQ
- [ ] Audio Play
- [ ] Audio Render
- [ ] Audio Spectrum
- [ ] Audio Stream In
- [ ] Audio Stream Out
- [ ] Beat
- [ ] Bind
- [ ] BlackTrax
- [ ] Blend
- [ ] Blob Track
- [ ] Bullet Solver
- [ ] Clip Blender
- [ ] Clip
- [ ] Clock
- [ ] Composite
- [ ] Constant
- [ ] Copy
- [ ] Count
- [ ] CPlusPlus
- [ ] Cross
- [ ] Cycle
- [ ] DAT to
- [ ] Delay
- [ ] Delete
- [ ] DMX In
- [ ] DMX Out
- [ ] Envelope
- [ ] EtherDream
- [ ] Event
- [ ] Expression
- [ ] Extend
- [ ] Face Track
- [ ] Fan
- [ ] Feedback
- [ ] File In
- [ ] File Out
- [ ] Filter
- [ ] FreeD
- [ ] Function
- [ ] Gesture
- [ ] Handle
- [ ] Helios DAC
- [ ] Hog
- [ ] Hokuyo
- [ ] Hold
- [ ] Import Select
- [ ] In
- [ ] Info
- [ ] Interpolate
- [ ] Introduction To s Vid
- [ ] Inverse Curve
- [ ] Inverse Kin
- [ ] Join
- [ ] Joystick
- [ ] Keyboard In
- [ ] Keyframe
- [ ] Kinect Azure
- [ ] Kinect
- [ ] Lag
- [ ] Laser
- [ ] Leap Motion
- [ ] Leuze ROD4
- [ ] LFO
- [ ] Limit
- [ ] Logic
- [ ] Lookup
- [ ] LTC In
- [ ] LTC Out
- [ ] Math
- [ ] Merge
- [ ] MIDI In
- [ ] MIDI In Map
- [ ] MIDI Out
- [ ] Mouse In
- [ ] Mouse Out
- [ ] NatNet In
- [ ] Ncam
- [ ] Noise
- [ ] Null
- [ ] Object
- [ ] Oculus Audio
- [ ] Oculus Rift
- [ ] OpenVR
- [ ] OSC In
- [ ] OSC Out
- [ ] Out
- [ ] Override
- [ ] Panel
- [ ] Pangolin
- [ ] Parameter
- [ ] Pattern
- [ ] Perform
- [ ] Phaser
- [ ] Pipe In
- [ ] Pipe Out
- [ ] PosiStageNet
- [ ] Pulse
- [ ] RealSense
- [ ] Record
- [ ] Rename
- [ ] Render Pick
- [ ] Reorder
- [ ] Replace
- [ ] Resample
- [ ] S Curve
- [ ] Scan
- [ ] Script
- [ ] Select
- [ ] Sequencer
- [ ] Serial
- [ ] Shared Mem In
- [ ] Shared Mem Out
- [ ] Shift
- [ ] Shuffle
- [ ] Slope
- [ ] SOP to
- [ ] Sort
- [ ] Speed
- [ ] Splice
- [ ] Spring
- [ ] Stretch
- [ ] Stype
- [ ] Switch
- [ ] Sync In
- [ ] Sync Out
- [ ] Tablet
- [ ] Time Slice
- [ ] Timeline
- [ ] Timer
- [ ] TOP to
- [ ] Touch In
- [ ] Touch Out
- [ ] Trail
- [ ] Transform
- [ ] Transform XYZ
- [ ] Trigger
- [ ] Trim
- [ ] Warp
- [ ] Wave
- [ ] WrnchAI
- [ ] ZED

### SOP

- [ ] Add
- [ ] Alembic
- [ ] Align
- [ ] Arm
- [ ] Attribute Create
- [ ] Attribute
- [ ] Basis
- [ ] Blend
- [ ] Bone Group
- [ ] Boolean
- [ ] Box
- [ ] Bridge
- [ ] Cache
- [ ] Cap
- [ ] Capture Region
- [ ] Capture
- [ ] Carve
- [ ] CHOP to
- [ ] Circle
- [ ] Clay
- [ ] Clip
- [ ] Convert
- [ ] Copy
- [ ] CPlusPlus
- [ ] Creep
- [ ] Curveclay
- [ ] Curvesect
- [ ] DAT to
- [ ] Deform
- [ ] Delete
- [ ] Divide
- [ ] Extrude
- [ ] Face Track
- [ ] Facet
- [ ] File In
- [ ] Fillet
- [ ] Fit
- [ ] Font
- [ ] Force
- [ ] Fractal
- [ ] Grid
- [ ] Group
- [ ] Hole
- [ ] Import Select
- [ ] In
- [ ] Introduction To s Vid
- [ ] Inverse Curve
- [ ] Iso Surface
- [ ] Join
- [ ] Joint
- [ ] Kinect
- [ ] Lattice
- [ ] Limit
- [ ] Line
- [ ] Line Thick
- [ ] LOD
- [ ] LSystem
- [ ] Magnet
- [ ] Material
- [ ] Merge
- [ ] Metaball
- [ ] Model
- [ ] Noise
- [ ] Null
- [ ] Object Merge
- [ ] Oculus Rift
- [ ] OpenVR
- [ ] Out
- [ ] Particle
- [ ] Point
- [ ] Polyloft
- [ ] Polypatch
- [ ] Polyreduce
- [ ] Polyspline
- [ ] Polystitch
- [ ] Primitive
- [ ] Profile
- [ ] Project
- [ ] Rails
- [ ] Raster
- [ ] Ray
- [ ] Rectangle
- [ ] Refine
- [ ] Resample
- [ ] Revolve
- [ ] Script
- [ ] Select
- [ ] Sequence Blend
- [ ] Skin
- [ ] Sort
- [ ] Sphere
- [ ] Spring
- [ ] Sprinkle
- [ ] Sprite
- [ ] Stitch
- [ ] Subdivide
- [ ] Superquad
- [ ] Surfsect
- [ ] Sweep
- [ ] Switch
- [ ] Text
- [ ] Texture
- [ ] Torus
- [ ] Trace
- [ ] Trail
- [ ] Transform
- [ ] Trim
- [ ] Tristrip
- [ ] Tube
- [ ] Twist
- [ ] Vertex
- [ ] Wireframe
- [ ] ZED

### MAT

- [ ] Constant
- [ ] Depth
- [ ] GLSL
- [ ] In
- [ ] Line
- [ ] MAT
- [ ] MAT Common Page
- [ ] MAT Generator Common Page
- [ ] Null
- [ ] Out
- [ ] PBR
- [ ] Phong
- [ ] Point Sprite
- [ ] Select
- [ ] Switch
- [ ] Texture Sampling Parameters
- [ ] Wireframe

### DAT

- [ ] Art-Net
- [ ] CHOP Execute
- [ ] CHOP to
- [ ] Clip
- [ ] Convert
- [ ] CPlusPlus
- [ ] DAT
- [ ] Execute
- [ ] DAT Export
- [ ] Error
- [ ] EtherDream
- [ ] Evaluate
- [ ] Examine
- [ ] Execute
- [ ] FIFO
- [ ] File In
- [ ] File Out
- [ ] Folder
- [ ] In
- [ ] Indices
- [ ] Info
- [ ] Insert
- [ ] JSON
- [ ] Keyboard In
- [ ] Lookup
- [ ] Merge
- [ ] MIDI Event
- [ ] MIDI In
- [ ] Monitors
- [ ] MQTT Client
- [ ] Multi Touch In
- [ ] NDI
- [ ] Null
- [ ] OP Execute
- [ ] OP Find
- [ ] OSC In
- [ ] OSC Out
- [ ] Out
- [ ] Panel Execute
- [ ] Parameter
- [ ] Parameter Execute
- [ ] Perform
- [ ] Render Pick
- [ ] Reorder
- [ ] Script
- [ ] Select
- [ ] Serial
- [ ] SocketIO
- [ ] SOP to
- [ ] Sort
- [ ] Substitute
- [ ] Switch
- [ ] Table
- [ ] TCP/IP
- [ ] Text
- [ ] Touch In
- [ ] Touch Out
- [ ] Transpose
- [ ] TUIO In
- [ ] UDP In
- [ ] UDP Out
- [ ] UDT In
- [ ] UDT Out
- [ ] Web Client
- [ ] Web
- [ ] Web Server
- [ ] WebSocket
- [ ] XML

## References

See at [Wiki](https://github.com/shin-sforzando/studies-td/wiki/References).
