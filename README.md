# audiovisual-sampler

use rust + nannou

have a bash script:

```
video -> script -> /output/image_00001.jpg
                   /output/image_00002.jpg
                   ...
                   /output/image_0000n.jpg
                   /output/audio.mp3
```

maybe even output into a special zip format "samplePAQ" and call it something nice in extension see https://github.com/zip-rs/zip

then in rust:
you add the "samplePAQ"s somehow and run the program

the program will use the image sequences and the audio to create a polyphonic audiovisual synth/sampler for each samplePAQ

each samplePAQ gets its own square texture on the output screen


consider using libpd rust crate for audio stuff
