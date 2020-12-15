# Configuring

## Program of requirements

<table><thead><tr class="header"><th>Area</th><th>m² and explanation</th></tr></thead><tbody><tr class="odd"><td>Student housing</td><td>30 m² times 80 units = 2400 m²</p><p> 
- Small private kitchen </p><p>
- Small private living room </p><p>
- Private bathroom </p><p>
- Common areas such as co-cooking and the community center. </td></tr><tr class="even"><td>Assisted living</td><td><p>
35 m² times 30 units = 1050 m²</p><p>
- Small private kitchen </p><p>
- Small private living room </p><p>
- Private bathroom </p><p>
- Common areas such as co-cooking and the community center. <tr class="odd"><td>Starter housing</td><td>
75 m² times 100 units = 7500 m²</p><p>  
-   bedroom, bathroom, livingroom, kitchen, extra bedroom/ study room
</td></tr><tr class="even"><td>Restaurant</td><td><p>
80 places to sit = 104 m² (= 60% of total area)</p><p>
The kitchen is 70 m² (= 40% of total area)</p><p>  
Total of 180 m² <tr class="odd"><td>Shop</td><td>
Supermarket 800 m² </td></tr><tr class="even"><td>Co-cooking</td><td><p>
Next to the common area, 100 m² <tr class="odd"><td>Atrium/ community center</td><td>
200 m². A place just for the residents, where people can meet their neighbours. Important is that there are different spaces from more private to more public.
![title](../img/atrium.png) 
</td></tr><tr class="even"><td>Pub</td><td><p>
180 m². 80 places to sit (same as the restaurant)
<tr class="odd"><td>Gym</td><td>
220 m². Mostly used by residents 
</td></tr><tr class="even"><td>Arcade</td><td><p>
400 m²
<tr class="odd"><td>Cinematheque</td><td>
120 visitors. The seating are is 120 m², the walking area ± 80 m²</p><p>
Total of 200 m²
</td></tr><tr class="even"><td>Offices</td><td><p>
Shared offices are 18,5 m². There will be room for 50 employees, so 25 shared offices = 460 m²
<tr class="odd"><td>Co-work spaces</td><td>
Work group areas of 7,5 m² per employee. Place for 100 employees = 750 m²
</td></tr><tr class="even"><td>Library</td><td><p>
200 m²
<tr class="odd"><td>Fablab</td><td>
150 m²
</td></tr><tr class="even"><td>Parking</td><td><p>
Minimum of 105 parking places times 12,5 m². The total area, including the walking area = 2500 m²
</p></td></tr></tbody></table>


## Matrix of connections

Before we dived into the analyses with python, we first wanted to visualize the mapping of the relations between relation.
We did this in several subdivisions with each there own main focus. These different themes are shown below.

![title](../img/Overzicht analyses.png)

### Sun analysis

![title](../img/Volumes_Licht.png)

### Public Entrance acces

![title](../img/Volumes_Entrance.png)

### Green access

![title](../img/Volumes_acces_green.png)

### Noise repel

![title](../img/Volumes_Geluid_tijd.png)

## Voxel Size

After we developped a clear notice of our wants for the building, we were able to start thinking of a proper voxel size. For this we started on the micro scale namely the stairs.

<table><thead><tr class="header"><th>Riser-Thread</th><th>2x Riser 1x Thread</th><th>Ratio</th><th>Common Denominator</th><th>Voxel Size</th></tr></thead><tbody><tr class="odd"><td>180mm x 240mm</td><td>(2 x 180) + (1 x 240) = 610</td><td>3:4</td><td>6</td><td>900x900 mm
</th></tr></thead><tbody><tr class="odd"><td></td><td></td><td></td><td></td><td>1800x1800 mm
</th></tr></thead><tbody><tr class="odd"><td></td><td></td><td></td><td></td><td>3600x3600 mm</td></tr><tr class="even"><td></p></td></tr></tbody></table>
</td></tr><tr class="even"><td></p></td></tr></tbody></table>

## Building Envelope

Now that we have a specified voxel size, we are able to voxelize our envelope. We have chosen to make the existing building mass with the football field in between available as a new envelope. To keep as much greenery as possible, the park behind the building will be retain. 

![voxelized envelope](../img/voxelized_envelope.jpg)