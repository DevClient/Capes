### MCP 1.8.8 Capes
## How to draw ?

1. Create a packet, for this case, ill create a packet named ```github``` <br>
2. In that packet; <br>
 - Create a new Class, for this case, ill name it ```Capes``` <br>
 - Paste the code into that class and change the class name and the resource location <br>
 - I assume you know how ```ResourceLocation``` works, so make the cape and move it to the correct folder <br>
 <br>
3. Go to ```net.minecraft.client.renderer.entity.RenderPlayer.java``` <br>
 - And right after ```this.addLayer(new LayerCustomHead(this.getMainModel().bipedHead));```, paste; <br>
  - ```this.addLayer(new <Classname>(this));``` <br>
 <br>
• Make sure you have a 64x32 image for the cape. download a [template here.](https://minecraftcapes.co.uk/upload-cape/template)
