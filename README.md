# audio_restoration_MusicGen
A pipeline to enhance MusicGen audio quality through preprocessing, denoising and neural bandwidth extension

# Audio-restoration-MusicGen
A pipeline to enhance MusicGen audio quality through preprocessing, denoising and neural bandwidth extension

- [Open in Colab]()

## Project Overview  
This project proposes a **post-processing restoration pipeline** that operates on generated audio without modifying the generative model itself.

The pipeline includes:
1. **Audio generation using MusicGen**: select random prompts from a list with 5 prompts per genre
2. **Peak normalization and high-pass filtering**
3. **Denoising** with noisereduce
4. **Neural bandwidth extension** using a HiFi-GAN–based model trained on speech, applied to music in a zero-shot setting.

The project is intended as an exploratory analysis of audio post-processing techniques for generative music models.

---
## References
- https://github.com/facebookresearch/audiocraft
- https://github.com/timsainb/noisereduce
- https://github.com/brentspell/hifi-gan-bwe


 ## License
This project is released under the MIT License.
