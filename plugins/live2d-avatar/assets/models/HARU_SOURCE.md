# Bundled Haru Test Model

The default test model is `Haru` from the `pixi-live2d-display` test assets.
That project uses this model in its Cubism 4 examples, so it is a better smoke
test for the `pixi-live2d-display@0.4.0` runtime than newer SDK sample models.

- Source: https://github.com/guansss/pixi-live2d-display/tree/master/test/assets/haru
- Upstream note: the project README says Haru is redistributed under Live2D's
  Free Material License.
- Code license file copied from source: `pixi-live2d-display-LICENSE`

The local `haru_greeter_t03.model3.json` copy removes optional references to a
missing display-info file and external sound files so the model can load as a
self-contained test asset.
