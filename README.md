# KISS: Psycho Circus - The Nightmare Child Upscale
Upscale project for KISS: Psycho Circus - The Nightmare Child game

Uses DTX v1.5 texture format

For starters I'll place all the original textures including converted from DTX format pcx and png images, alpha layers and used cluts. Everything you need to upscale textures and repack them back to DTX format

More info about DTX and its conversion can be found here:  
https://github.com/AkvenJan/DTX-Meta-Transfer

Logic of folder structure:
  * Textures - original DTX & SPR - contains original DTX and SPR files, extracted from game archive. Each DTX contain texture in game format. Each SPR file contain sprite logic description based on actual DTX textures
  * Textures - converted PCX - all the DTX textures converted to PCX format using DEDIT editor
  * Textures - extracted alpha PNG - alpha layers were extracted from DTX files and converted to DTX
  * Textures - extracted palettes ACT - palettes were exctracred in ACT format from PCX files
  * Textures - converted PNG - PCX were converted to PNG to use in any upscale process
