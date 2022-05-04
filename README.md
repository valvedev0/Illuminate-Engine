# Illuminate Game Engine




Since this project is based on WebGL, which means it is used in the browser, it uses AMD instead of CommonJS, with the outFile option when built. This means standard imports will not work. Instead, reference tags should be used by games including this library.



# Projects Using this Engine
- StupidDuck - (FlappyBird Clone, 2D)
- TBD - 

## Items to do:
- Asset loader error handling
- UI System with controls:
    - GameScreens
    - Panel (scrollable if set)
    - Label
    - Button
    - ImageBox
    - Checkbox
    - Radio Button
    - Window/Dialogs
- Multi-page bitmap fonts
- Configurable bitmap fonts
- Configurable audio
- State Machines 
- System fonts?
- Advanced audio
- Configurable materials
- Networking (including server?)
- 3D
    - Lighting
    - Normal maps
    - Specular maps
    - Physics
    - Object/mesh loading
    - Animation system
- RenderBuffer/PostFX system
- WebGL2?
- Input handler overhaul
- Zone overhaul - potentially change to a better format
