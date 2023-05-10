Followed this [guide](https://www.howtogeek.com/830179/how-to-run-stable-diffusion-on-your-pc-to-generate-ai-images/) for setting this repo up

# Setup
After following the guide above. Run the following command.

`conda env update -f environment_update.yaml`

This command will fix an import error I couldn't resolve on a fresh environment install.


# Generating images
Modify the following command

`python scripts/txt2img.py --prompt "a close-up portrait of a cat by pablo picasso, vivid, abstract art, colorful, vibrant" --plms --n_iter 5 --n_samples 1`

or use `run.ipynb`


# Sources
- [cannot import name 'SAFE_WEIGHTS_NAME' from 'transformers.utils'](https://github.com/CompVis/stable-diffusion/issues/627)
