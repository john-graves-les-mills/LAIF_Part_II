# LAIF_Part_II
Google Colab implementation of [LAIF Part II](https://github.com/biaslab/LAIF/blob/main/Part2/T-maze_Generalized.ipynb) discussed in [Realising Synthetic Active Inference Agents, Part II: Variational Message Updates](https://arxiv.org/abs/2306.02733) by Thijs van de Laar, Magnus Koudahl, Bert de Vries

## Usage

Open Colab 

File > Open notebook > Github and paste Github URL `https://github.com/john-graves-les-mills/LAIF_Part_II/blob/a67658ab7769958c2ca64e8cbb5d5124441f4777/T_maze_Generalized_Colab.ipynb`

Run cell containing the line `!git clone https://github.com/john-graves-les-mills/LAIF_Part_II.git` to copy LAIF_Part_II Julia files to this Colab instance.

Run cell starting with `%%shell` to install Julia.

Reload the browser (press F5).

Proceed to run remaining cells of the notebook. Note the cell starting with `using Pkg` may take over 6 minutes to complete as Julia packages are precompiled.

Inspect the figures produced (in figures folder) with reference to the Screenshot of the T-Maze Layout showing locations of O, L, R, C cells.

![Codelab after Git clone](https://github.com/john-graves-les-mills/LAIF_Part_II/blob/86ef5e8d36f6e019040b7f4261b4d85b99bd5f9c/colab_after_git_clone.png)
