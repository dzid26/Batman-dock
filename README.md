- KiCad 9
    - [Fabrication plugin](https://github.com/bennymeg/Fabrication-Toolkit)
- FreeCAD 1.1
    - Use [exportProject.FCMacro](https://gist.github.com/dzid26/e0ff365de43cabe658df9d93b92d1954) to quickly export step files with a macro
    - KiStepUp plugin to export `PCB_Sketch_master.stp` to Kicad and import part positions from Kicad

![image](https://github.com/user-attachments/assets/739f0e47-febb-44e5-81ba-151b46a670c6)


The design accounts for windshield curvature (R=4m). Although in hindsight this is not very useful as it translates to only 0.08mm surface delta for the batman width. The 3d printer can do it, but bigger effects might be even due to part warping and flex. 