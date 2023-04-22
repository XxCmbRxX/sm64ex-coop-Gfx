# sm64ex-coop-Gfx
Aquí aprenderás a descargar gfx 

* Ejemplo - [Render96 HD Texture Pack]
(https://github.com/pokeheadroom/RENDER96-HD-TEXTURE-PACK/tree/sm64ex-and-others):

# Usaremos Termux para poner estos comandos 
```bash
termux-setup-storage
```
```bash
pkg install git
```
# le daremos en `y` cada que nos pregunte 

# después pondremos estos comandos para la instalación 
```bash
pkg install rsync 
```
```bash
mkdir -p /storage/emulated/0/com.owokitty.sm64excoop/dynos/packs
```
```bash
git clone -b sm64ex-and-others https://github.com/pokeheadroom/RENDER96-HD-TEXTURE-PACK.git
```
```bash
rsync -r RENDER96-HD-TEXTURE-PACK/gfx /storage/emulated/0/com.owokitty.sm64excoop/dynos/packs
 ```

# Y listo ya tendremos las texturas que pesan alrededor de 980MB

## Sígueme En redes sociales para estar al tanto
* [Facebook](https://www.facebook.com/profile.php?id=100087203207899&mibextid=ZbWKwL "MIGUEL RAMOS")
* [YouTube](https://youtube.com/@miguelrmos64)
