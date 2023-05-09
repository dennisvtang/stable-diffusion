Followed this [guide](https://www.howtogeek.com/830179/how-to-run-stable-diffusion-on-your-pc-to-generate-ai-images/) for setting this repo up

# Activate environment
`conda activate ldm`

# Generating images
Modify the following command
`python scripts/txt2img.py --prompt "a close-up portrait of a cat by pablo picasso, vivid, abstract art, colorful, vibrant" --plms --n_iter 5 --n_samples 1`