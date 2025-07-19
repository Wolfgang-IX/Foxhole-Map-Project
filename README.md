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
      
![maps_ID](https://github.com/user-attachments/assets/b01916e2-bb77-4979-a424-92dcc8e63f94)

## 4. **Height Map**
      Baked Height map generated from of Land, Rock, Water meshes/model.
      It's not normalized (not matching height values for all map), but on top left there's 100 values sample, each represent 10m increments with total of 990m from the baking plane.
      The baking plane itself is 400m below World Origin (0,0,0).
    
