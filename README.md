# ColorWheelMapping.m
-Mapping script with magnitude and angle map
2022/02/18 (Y/M/D)

Autor:  Semin Cheon. M.D/Ph.D integrated course. MDAIL(KAIST).
          chsm0338@kaist.ac.kr
Function:
        [mapping] = colorwheel(Magnitude_map, Angle_map)
        
Input - Gmag: Magnitude map ( M x N Grid ). This grid give
      radial displacement to the color wheel.
      - Gdir: Angle map (Grid size must be equal to "Magnitue map").
      This grid give information of angular direction to the color wheel.

Output - mapping: Mapped image which color is assigned corresponding to
the magnitude and angle from the generated color wheel.

※ For th color wheel, i use a matlab code from:
https://kr.mathworks.com/matlabcentral/answers/442739-how-to-plot-a-smooth-color-wheel
Author: "Image Analyst" 
