# threelearn

```
カメラを移動せずに、壁を変更する。移動したかは、ミニマップと座標を提示する事で解決。
□
□
□
□
□<--- camera 
```
```
//three dungeron setting
/*
0115.01
0:n wall tile number
 1:e wall tile number
  1:w wall tile number
   5:s wall tile number
    .:separater
     01:ground tile number
*/
//壁がなくても透明な壁として配置する。

num:1 //floornumber
size:20, //mapsize
map:[0111.01,0111.01,0111.01,0111.01,0111.01,0111.01,0111.01,0111.01,0111.01 ...],  //20x20 ex)0115.01 n+e+w+swall.ground
tilesize:32, //
walltile:"https://gnjo.github.../wall_01.png",
groundtile:".../ground_01.png",
background:"..../background_01.png"

```
