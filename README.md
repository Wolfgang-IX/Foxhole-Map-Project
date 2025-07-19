# Baked Mesh Map
      Result may be inaccurate since it's limited by the tools that import the map models.
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
      It's not normalized (not matching height values for all map), but on top left there's 100 values sample, each represent 10m increments with total of 990m from the baking plane.
      The baking plane itself is 400m below World Origin (0,0,0).
<img width="711" height="534" alt="Height_Map" src="https://github.com/user-attachments/assets/249da1d3-5ccc-4256-97f2-62f16c9f2a0f" />
