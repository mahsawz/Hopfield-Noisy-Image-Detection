# Hopfield-Noisy-Image-Detection

A Hopfield network (or Ising model of a neural network or Ising–Lenz–Little model) is a form of recurrent artificial neural network popularized by [John Hopfield](https://en.wikipedia.org/wiki/John_Hopfield) in 1982, but described earlier by Little in 1974 based on Ernst Ising's work with Wilhelm Lenz. Hopfield networks serve as content-addressable ("associative") memory systems with binary threshold nodes. They are guaranteed to converge to a local minimum, and can therefore store and recall multiple memories, but they may also converge to a false pattern (wrong local minimum) rather than a stored pattern (expected local minimum) if the input is too dissimilar from any memory[citation needed]. Hopfield networks also provide a model for understanding human memory.

Here, I design a noise-robust model using Hopfield Network and train it on the images of the first 10 letters of English alphabet to get a noisy image and correct it.

There is some outputs sample:

<img src="https://github.com/mahsawz/Hopfield-Noisy-Image-Detection/blob/main/outputs/64/A.jpeg" width="200" height="200">

<img src="https://github.com/mahsawz/Hopfield-Noisy-Image-Detection/blob/main/outputs/64/D.jpeg" width="200" height="200">

<img src="https://github.com/mahsawz/Hopfield-Noisy-Image-Detection/blob/main/outputs/64/G.jpeg" width="200" height="200">

<img src="https://github.com/mahsawz/Hopfield-Noisy-Image-Detection/blob/main/outputs/64/H.jpeg" width="200" height="200">
