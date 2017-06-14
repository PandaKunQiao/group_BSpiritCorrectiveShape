# group_BSpiritCorrectiveShape
can create corrective shape together instead of one by one

All the raw corrective shapes should be named in the convention:
nameofjoint_rotateaxis_rotatedegree

for example, if the blendshape deformer is 1 when rotate bn_jaw on x axis of 50 degree, the corrective mesh should be named as
bn_jaw_x_50

for negative degrees, use
bn_jaw_x_n50

First, select all your corrective meshes, then select the binded mesh, then select the root joint. All the resulted mesh will be created and under a new group
