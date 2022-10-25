# GANZZLE: Reframing Jigsaw Puzzle Solving as a Retrieval Task Using a Generative Mental Image

Have a look at our paper on [Arxiv](https://arxiv.org/abs/2207.05634).

PuzzleCelebA and PuzzleWikiArts metadata for test is available.
Each row contain a sample in the test dataset:
- image_file
- number of pieces per edge
- permutation of pieces

For instance, consider the sample:
```
29522.jpg,2,[2, 3, 1, 0]
```
the file associated to the sample is `29522.jpg` and it is chunked into 2 x 2 pieces with permutation `[2, 3, 1, 0]`.


To cite this paper:
```
@inproceedings{talon2022ganzzle,
  title={GANzzle: Reframing jigsaw puzzle solving as a retrieval task using a generative mental image},
  author={Talon, Davide and Del Bue, Alessio and James, Stuart},
  booktitle={IEEE International Conference on Image Processing (ICIP)},
  year={2022}
}
```
