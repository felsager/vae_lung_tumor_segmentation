# Changelog:
> **Nick**: Debugging nan loss.
> - Tried different loss function -> returned non-nan.
> - Tried adding eps to both BCE inputs -> no difference.
> - Switched `y` and `y_hat` in  `loss = lossfn(y,y_hat)` in training and evaluation loops -> success?
