---
badges:
    - Official
---
# Titan

![preview](assets/__ALL__.png)

EVA / Titan is the oldest and in my opinion one of the best variants. It was the original and only extruder option for the first [Easy-Mod](https://eva-3d.github.io/easy-mod/) - later was moved to a separate project which EVA become :smile:  
Since EVA 2.0.0 it does not require a unique `front` part, just a `top` (like BMG) which makes it not only easier to assemble but also to maintain. One can opt to use the `press fit` part if is lacking a groove mount adapter.  
There is a PTFE tube going from the Titan to the hotend so it's not as "direct" as one could imagine but still the print quality is excellent (or at least not impeded by the carriage). 

!!! tip "Custom Titan Tension Arm"

    ![Placeholder](assets/SSX.png){: align=left }
    The BOM contains my remix of the [E3D Titan Flex Upgrade](https://www.thingiverse.com/thing:2426505) thing which improves the Titan filament path greatly.  
    My remix improves it's printability - print on the side where the spring is. No supports are needed.


### Links

{{ eva_download_button("titan") }}

{{ eva_link("titan") }}

{{ onshape_link("titan") }}

### BOM

=== "E3D V6"

{{ bom("drives/titan/bom/v6.csv", 4) }}

=== "Mosquito"

{{ bom("drives/titan/bom/mosquito.csv", 4) }}

=== "Dragon"

{{ bom("drives/titan/bom/dragon.csv", 4) }}
