# ChatGPT3DS

A 3DS Application that allows you to make calls to OpenAI's chat completion API (with more models) and image generation API.

## Installation

1. Download the latest release from the [releases page](https://github.com/CarsonKompon/ChatGPT3DS/releases)
2. Place `ChatGPT3DS.3dsx` in the `/3ds/` folder on your SD card
3. ** *Optional* ** Create the file `/3ds/save/api_key.txt` and place your [OpenAI API key](https://platform.openai.com/account/api-keys) in it. If you do not do this, you will have to enter your API key on your 3DS the first time you run the application.
4. ** *Optional* ** Create the file `/3ds/save/endpoint.txt` and place a OpenAI compatible endpoint in it (custom endpoint URL should look like this: https://endpoint.url/v1/). If you do not do this, it will fallback to the default OpenAI endpoint URL.


*WARNING: This app has not yet been tested. Make an issue if you have any problems on your own device :)*

## Demonstration (from original repo creator)

https://youtube.com/watch?v=gh5tZnisXlI

## Attribution

- [videah](https://github.com/videah) for creating the original LovePotion
- [TurtleP](https://github.com/TurtleP) for continuing to maintain [Lovebrew](https://github.com/lovebrew/LovePotion)
- [Love2D](https://love2d.org/) for creating the engine that both LovePotion and Lovebrew are based on
- [png-lua](https://github.com/Didericis/png-lua) for inspiring me to create my own png lua implementation
- [compress.deflatelua](https://github.com/davidm/lua-compress-deflatelua) for the deflate implementation
- [OpenAI](https://openai.com/) for creating the API
