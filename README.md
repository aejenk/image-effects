# Dithering Experiment

The name is a placeholder - this project started out as just me wanting to learn more about dithering. After looking into algorithms and other code I've seen online, this is what I've got!

Might become a library, or a tool. I'd like to provide a good GUI for it at least.

Currently supports the following algorithms:

|            **Name** |                                  *2-bit* |                             *RGB (Web-safe)* |                             *RGB (8-bit)* |                             *RGB (Custom palette)* |
| ------------------: | ---------------------------------------: | -------------------------------------------: | ----------------------------------------: | -------------------------------------------------: |
|               Basic |               ![](./data/basic-mono.png) |               ![](./data/basic-web-safe.png) |               ![](./data/basic-8-bit.png) |               ![](./data/basic-custom-palette.png) |
|     Floyd-Steinberg |     ![](./data/floyd-steinberg-mono.png) |     ![](./data/floyd-steinberg-web-safe.png) |     ![](./data/floyd-steinberg-8-bit.png) |     ![](./data/floyd-steinberg-custom-palette.png) |
| Jarvis-Judice-Ninke | ![](./data/jarvis-judice-ninke-mono.png) | ![](./data/jarvis-judice-ninke-web-safe.png) | ![](./data/jarvis-judice-ninke-8-bit.png) | ![](./data/jarvis-judice-ninke-custom-palette.png) |
|              Stucki |              ![](./data/stucki-mono.png) |              ![](./data/stucki-web-safe.png) |              ![](./data/stucki-8-bit.png) |              ![](./data/stucki-custom-palette.png) |
|            Atkinson |            ![](./data/atkinson-mono.png) |            ![](./data/atkinson-web-safe.png) |            ![](./data/atkinson-8-bit.png) |            ![](./data/atkinson-custom-palette.png) |
|              Burkes |              ![](./data/burkes-mono.png) |              ![](./data/burkes-web-safe.png) |              ![](./data/burkes-8-bit.png) |              ![](./data/burkes-custom-palette.png) |
|              Sierra |              ![](./data/sierra-mono.png) |              ![](./data/sierra-web-safe.png) |              ![](./data/sierra-8-bit.png) |              ![](./data/sierra-custom-palette.png) |
|        SierraTwoRow |      ![](./data/sierra-two-row-mono.png) |      ![](./data/sierra-two-row-web-safe.png) |      ![](./data/sierra-two-row-8-bit.png) |      ![](./data/sierra-two-row-custom-palette.png) |
|          SierraLite |         ![](./data/sierra-lite-mono.png) |         ![](./data/sierra-lite-web-safe.png) |         ![](./data/sierra-lite-8-bit.png) |         ![](./data/sierra-lite-custom-palette.png) |
|           Bayer 2x2 |           ![](./data/bayer-2x2-mono.png) |           ![](./data/bayer-2x2-web-safe.png) |           ![](./data/bayer-2x2-8-bit.png) |           ![](./data/bayer-2x2-custom-palette.png) |
|           Bayer 4x4 |           ![](./data/bayer-4x4-mono.png) |           ![](./data/bayer-4x4-web-safe.png) |           ![](./data/bayer-4x4-8-bit.png) |           ![](./data/bayer-4x4-custom-palette.png) |
|           Bayer 8x8 |           ![](./data/bayer-8x8-mono.png) |           ![](./data/bayer-8x8-web-safe.png) |           ![](./data/bayer-8x8-8-bit.png) |           ![](./data/bayer-8x8-custom-palette.png) |
|         Bayer 16x16 |         ![](./data/bayer-16x16-mono.png) |         ![](./data/bayer-16x16-web-safe.png) |         ![](./data/bayer-16x16-8-bit.png) |         ![](./data/bayer-16x16-custom-palette.png) |