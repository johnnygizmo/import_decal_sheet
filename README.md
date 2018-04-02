# import_decal_sheet
Import a PNG file as a stencil map on a mesh in Blender.

This addon takes the following steps:
-import the selected PNG file into blender
-create a new UV Map on the selected mesh object
-insert a mix shader at the end of your active material 
-create a node chain that uses the new UV map, the image tex, a principled shader and plugs it into the mix shader using the image's alpha as the mix factor
-Can be run multiple times for multiple decal sheets (up to the 8 UV Map limit)
