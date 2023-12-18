# lado-jack

## Questions

### Lydell's questions

1. What problem does the AI Model Solve?
2. What are the Elements of the AI Model?
3. Rather then Model would a Coach, mentor, or consultant for specific use case provide a direct quality of value?

### Jack's questions

1. What problems or tasks can AI _significantly_ improve?
2. What are some ways that an AI chatbot can improve daily tasks (e.g. ordering food, therapy, refilling prescriptions, reservations, scheduling appointments, etc.)?
3. Pretend you have the ability to instantly add an AI to any of your daily personal or work related tasks. What might a few of those tasks be? How would those AIs be used? Would those AIs be interactive or fully autonomous?
4. How private is the data that the AI uses?
    1. Is the data encrypted? How many layers or methods of encryption are there?
    2. Is cryptography used? If yes, how? Which algorithms?
    3. If data is kept private (i.e. encrypted), what limitations does this bring to the AI? Can the AI still operate efficiently with metadata?

## Tutorials

### Fooocus - Colab notebook

Fooocus is...
> is "a rethinking Stable Diffusion and Midjourney designs"

--------- 
> Notes from the Fooocus repository...

(Last tested - 2023 Dec 12)

| Colab | Info
| --- | --- |
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/lllyasviel/Fooocus/blob/main/fooocus_colab.ipynb) | Fooocus Official

In Colab, you can modify the last line to `!python entry_with_update.py --share` or `!python entry_with_update.py --preset anime --share` or `!python entry_with_update.py --preset realistic --share` for Fooocus Default/Anime/Realistic Edition.

> Jack recommends modifying it to include `--preset realistic` so that the images come out more realistic.  

Note that this Colab will disable refiner by default because Colab free's resource is relatively limited (and some "big" features like image prompt may cause free-tier Colab to disconnect). We make sure that basic text-to-image is always working on free-tier Colab.

---------
#### Jack's tips

1. Make sure to turn on the GPU runtime and select the T4 GPU. Here is a video below for how to do that:
https://github.com/ladiossato/lado-jack/assets/37757724/e2dfe6d7-77c7-498d-999f-95fbb8fa8767

2. After the last line, `!python entry_with_update.py --preset realistic`, is done running, you will see a Gradio URL that is returned. This is the URL where you will generate your images. Here is a screenshot below that shows what this URL will look like:
<img width="1029" alt="Screenshot 2023-12-17 at 10 32 23 PM" src="https://github.com/ladiossato/lado-jack/assets/37757724/a43c2965-8b75-4cef-953d-7091e2137b26">

3. Feel free to experiment with any of the `Advanced` settings. I highly recommend toggling the `Quality` Performance setting and raising the `Image Sharpness` setting, which is under the `Advanced` tab.
<img width="1029" alt="Screenshot 2023-12-17 at 10 37 14 PM" src="https://github.com/ladiossato/lado-jack/assets/37757724/51249735-0811-4b33-843e-659146cee494">
