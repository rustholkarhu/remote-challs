<h1 align="center"><code>Chall04 / Falling Sand</code></h1>

<div align="center">
  <sub>Created by <a href="https://github.com/jgengo">Jordane Gengo (Titus)</a>, <a href="">Oleksii Martynovskyi (Disky)</a>, <a href="">Paula Lantran (Ablette)</a></sub>
</div>
<div align="center">
  <sub>From <a href="https://hive.fi">Hive Helsinki</a> for all the 42 Network</sub>
</div>

---

### Instructions

<sub>**Turn-in directory:** `chall04/`</sub><br />
<sub>**Files to turn in:** `<xlogin>.py`</sub><br />
<sub>**Language:** `Python` *(specify the version you used in the top of your code commented)*</sub>
  
<sub>**Deadline:** 07.04.2020 - 9:42am</sub>

<br /><br />
### Subject
  
<p align="center">
  <img width="350" height="350" src="https://gamepedia.cursecdn.com/minecraft_gamepedia/b/b0/Sand_JE5_BE2.png">
</p>


Your goal is to implement a mini falling-sand simulation for just sand and stone. The simulation is in 2D-space on a uniform grid, where we are viewing this grid from the side. Each type's simulation properties are as follows:
 - Stone always stays where it was originally placed. It never moves.
 - Sand keeps moving down through air, one step at a time, until it either hits the bottom of the grid, other sand, or stone.
 
 On standard console input, you will be given an integer `N` which represents the `N x N` grid of ASCII characters. This means there will be N-lines of N-characters long. This is the starting grid of your simulated world: the character ` ` (space) means an empty space, while `.` (dot) means sand, and `#` (hash or pound) means stone. Once you parse this input, simulate the world until all particles are settled (e.g. the sand has fallen and either settled on the ground or on stone). "Ground" is defined as the solid surface right below the last row.
 
Print the end result of all particle positions using the input format for particles.

It has to be an executable
<br /><br />
### Examples

input:

```
5
.....
  #  
#    
     
    .
```

output:

```
  .  
. #  
#    
    .
 . ..
```

### Reward

 - The first one to submit a working solution will earn `15` points for their coalition.
 - Everyone else submitting a working solution *(not yet submitted)* will earn `5` points for their coalition.
 - Every participant that tried to solve the challenge and pushed a solution will earn `3` points for their coalition.
 
<br /><br />
Good luck!
