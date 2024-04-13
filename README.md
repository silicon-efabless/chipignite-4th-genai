# Fourth AI Generated Silicon Challenge on ChipIgnite

The [challenge](https://efabless.com/genai/challenges/4) aims to leverage generative AI to develop an open-source hardware accelerator designed explicitly for _Keyword Spotting_ (KWS) applications on the Caravel System-on-Chip.

Utilize\ing generative AI to optimize the KWS machine learning model and/or the audio features extractor (e.g., MFCC) to create an energy-efficient KWS accelerator that seamlessly integrates into the Caravel SoC environment.

# Abstract

As part of the challenge, this project will aim to generate an entire hardware accelerator for the specific application of Keyword Spotting (KWS) using generative AI (gen-AI) such as ChatGPT.

    This project will target applications that are mostly dormant and are activated infrequently using a wake-up cal such as "Wakeup Neo". It will also assume target applications to be very power conscious so it is using the bare minimum power when sleeping or dormant.

    Keeping the above application in mind, we will target a two-step architecture where an ultra-low-power audio feature extraction algorithm will be implemented on a purely digital architecture, assuming that a digitized audio stream is provided as the input to this feature extractor while trading accuracy for power. This feature extractor will wake up an accurate hardware accelerator for KWS that can process a wide range of audio features more accurately, but at the expense of higher power consumption.

    This project will not only demonstrate the use of Gen-AI to generate accurate hardware for high-performance applications, but also assist a non-expert as well. As analog designers, with minimal experience in digital design, we will take the help of gen-AI to come up with the right architecture for the above application with some skillful prompt engineering. Once the architecture has been verified to work with the above application, we will again take the help of Gen-AI to generate the hardware for the low-power feature extractor and the hardware accelerator for KWS. We will also use Gen-AI to assist designers in creating test plans for the generated design as well. It is understood that during the course of the project, the user will fine-tune the design without the help of gen-AI keeping it to as minimum as possible.

    We will integrate the final GDS of this design into the chipIgnite platform using the Caravel SoC harness from eFabless.
