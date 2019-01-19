# ProdigyModels

Collection of some of the models trained by [Project Prodigy](https://github.com/RayDiab/Prodigy)

- `jazzy.xml`: trained on two short pieces of Bach, gets stuck into a cycle during prediction, 512 hidden units. `rho = 5`
- `easybach.xml`: trained on a collection of Bach's works with simple combination of notes, 256 hidden units. Also the model used in the GUI in Project Prodigy. `rho = 20`
- `512easy.xml`: trained on the same collection of Bach's works as above, with 512 hidden units. `rho = 5`
- `river.xml`: trained on Yiruma's "River flows into you", with 256 hidden units. `rho = 10`
- `sixbach.xml`: trained on six long Bach pieces, with 256 hidden units. Gives chaotic compositions. `rho = 20`

More experimenting with parameters should be done but so far, the best-performing models seem to be the ones with 512 hidden units with `rho` between 5 and 10.
