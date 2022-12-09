# VAE-based Tumor Segmentation
This repository contains the files and notebooks, which accompany our (Nicklas Vraa and David Felsager) final project reports. We cannot provide our data, as they take up several Gigabytes of space, but the raw datasets can be found [here](http://medicaldecathlon.com/). Thank you for your attention.

## Changelog:
> **Nick**: Debugging nan loss.
> - Tried different loss function -> returned non-nan.
> - Tried adding eps to both BCE inputs -> no difference.
> - Switched `y` and `y_hat` in  `loss = lossfn(y,y_hat)` in training and evaluation loops -> success?
