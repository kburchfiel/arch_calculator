# Arch Calculator:
## A Python program that applies trigonometry to calculate the coordinates of components of an arch

*My blog post on this program can be found at https://kburchfiel3.wordpress.com/2022/03/23/arch-calculator-a-python-program-that-applies-trigonometry-to-make-3d-modeling-easier/.*

I created Arch Calculator in order to more easily calculate the coordinates of arches within Blender, a free and open-source 3D modeling program. The program allows you to create different arch shapes by modifying various input parameters, such as the height and thickness of the arch wedges and the angle of the diagonal components of each wedge. You can even use the program to calculate the coordinates of angled walls (such as the walls comprising an octagonal room).

Let's say that you wanted to calculate the coordinates of 3 wedges that, together, form half of an arch. The calculations of these coordinates would be as follows:
![](https://raw.githubusercontent.com/kburchfiel/arch_calculator/master/annotated_arch_output.png)

Performing each of these calculations individually would take a while. Instead, you can use the create_arch function within Arch Calculator to determine the coordinates of each block, which can then be copied and pasted into Blender. An example of the function's inputs and outputs is shown below:

![](https://raw.githubusercontent.com/kburchfiel/arch_calculator/master/sample_code_output.jpg)

I hope you find this program useful for your own 3D modeling work!
