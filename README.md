### MCP 1.8.8 Capes
## How to draw ?

Go to ````net.minecraft.client.renderer.entity.RenderPlayer.java```` and add this right after -
  ```this.addLayer(new LayerCustomHead(this.getMainModel().bipedHead));```
 
```
this.addLayer(new ClientOwner(this));
```

• Make sure you have a 64x32 image for the cape. download a [template here.](https://minecraftcapes.co.uk/upload-cape/template)
