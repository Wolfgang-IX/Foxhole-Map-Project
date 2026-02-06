# How to Download
In case I didn't upload the resource in **[Releases](https://github.com/Wolfgang-IX/Foxhole-Map-Project/releases)** section, you'll need to have [Git LFS](https://git-lfs.com) installed and clone this repo.

or use **[GitHub Desktop](https://desktop.github.com/download)**

You can download the mod on Nexus Mods [WG.IX Map](https://www.nexusmods.com/foxhole/mods/135)
# Processed Map
![ProcessedMap](https://github.com/user-attachments/assets/8a1a6472-d68c-44d2-938e-579e61652284)


## 1. **Map**
      Map with features (road tiers)
## 2. **Base Map**
      Map without features.
## 3. **Landscape ID**
      same ID as baked mesh, but this takes account of bridges and original map that baked mesh map can't provide.
## 4. **Roads**
      Roads layer.
## 5. **Contour Lines**
      Contour Lines.
## 6. **Bulwark**
      Bulwark and Relic Vault.
## 7. **RDZ**
      Rapid Decay Zone, taking into account World Bases Radius.


# Baked Mesh Map
![Mesh Maps](https://github.com/user-attachments/assets/f7776080-a9a7-40cc-9dd1-448065fd3b4a)


      Generated informations from imported map models.
      Result may be inaccurate since it's limited by the tools that import the map models.
      Resolution is 2048x2048px.
## 1. **Ambient Occlusion**
      Ambient Shadow.
## 2. **Curvature**
      Information about the convexity and concavity of a mesh.
## 3. **Color IDs**
      Used for masking.
   ### a. **Landscape ID**
      Include Land, Rock and Water Body.
   ### b. **Roads ID**
      Include Land, Rock and Roads.
      
<img width="642" height="507" alt="Height_Map" src="https://github.com/user-attachments/assets/b01916e2-bb77-4979-a424-92dcc8e63f94" />

## 4. **Height Map**
      Baked Height map generated from Land, Rock, Water meshes/model.
      It's not normalized (height values for all map not matching), but on top left there's 100 values sample, each represent 10m increments with total of 1km from the baking plane.
      The baking plane itself is 400m below World Origin (0,0,0).
<img width="711" height="534" alt="Height_Map" src="https://github.com/user-attachments/assets/249da1d3-5ccc-4256-97f2-62f16c9f2a0f" />

## 5. **Normal Map (OpenGL)**


Credits:
**Tsekho**, for Normalized Height map, Contour Lines and support for this project.
**Rustard**, for the Rocks and "Bulwark and Vault" layer used as mask.
**Kov**, for the help and his _FoxholeMapLayersAssembler_ tool.
