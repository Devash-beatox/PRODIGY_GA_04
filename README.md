# PRODIGY_GA_04 — Image-to-Image Translation with cGAN (pix2pix)

## Task
Used pix2pix, a conditional GAN (cGAN), to translate building facade sketches
into realistic photos using a pretrained checkpoint on the "facades" dataset.

## What I learned
- How GANs work: a generator and discriminator trained together in competition
- What makes a GAN "conditional" — the output is based on an input image,
  not random noise
- Why pix2pix requires paired training data (same scene as sketch + real photo)
- Why GAN training is unstable, and why starting from a pretrained checkpoint
  gives a reliable first result

## Files
- `[your-notebook-filename].ipynb` — pix2pix inference pipeline
- `*_real_A.png` — input sketches
- `*_real_B.png` — ground truth real photos
- `*_fake_B.png` — model-generated translations

## Sample Results
(paste 2-3 example real_A / real_B / fake_B comparisons here)
