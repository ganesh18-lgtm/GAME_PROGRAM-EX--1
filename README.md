# GAME_PROGRAM-EX--1
# EXP:1 Implementing various effects in a material such as emissive, roughness and metallic properties in Unreal Engine
## Aim:
 To implement and demonstrate various material effects in Unreal Engine, including emissive, roughness, and metallic properties, using the Material Editor.

## Procedure
Create a New Material:

Open Unreal Engine.
In the Content Browser, right-click and select Material.
Name it M_EffectsDemo.
Apply Base Color:

Open the material.
Add a Vector Parameter or Constant3Vector node and connect it to the Base Color input.
Add Emissive Effect:

Add a Multiply node.
Connect a Constant3Vector (for emissive color) and a Scalar Parameter (for intensity).
Connect the result to the Emissive Color input.
Control Roughness:

Add a Scalar Parameter node and connect it to the Roughness input.
Lower values = shinier surface, higher values = rougher surface.
Control Metallic Property:

Add a Scalar Parameter node and connect it to the Metallic input.
0 = non-metal, 1 = fully metallic.
Save and Apply Material:

Save the material.
Apply it to any mesh in the scene (like a sphere or cube) to preview the results.

## Output

 <img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/73c85dc1-db01-4af0-b944-0136e25b460e" />
 
 <img width="1192" height="791" alt="image" src="https://github.com/user-attachments/assets/e88b6639-2e3a-4d47-aba0-5d99618c27a6" />
 
## Result:

Successfully implemented a material in Unreal Engine showcasing:

  • Emissive glow using emissive color and intensity.
  
  • Variable surface roughness to simulate different textures.
  
  • Metallic appearance adjustment to reflect light like real-world metals.
  
This setup enables dynamic, realistic materials suitable for use in environments, characters, and VFX in Unreal Engine projects.
