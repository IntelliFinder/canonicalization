# A Canonicalization Perspective on Invariant and Equivariant Learning

Source code for the paper "**[A Canonicalization Perspective on Invariant and Equivariant Learning](https://openrev Lets iew.net/forum?id=jjcY92FX4R&noteId=jjcY92FX4R)**", NeurIPS 2024.

**Attribution**: Our code is built on top of the [[SignNet repo](https://github.com/cptq/SignNet-BasisNet)] by Lim et al. in 2022, which in turn builds off of the setup in [[LSPE repo](https://github.com/vijaydwivedi75/gnn-lspe)] by Dwivedi et al. in 2021.

To reproduce the repo follow the instructions in LSPE (see yml file in repo for GPU).
We want to run:

 python main_ZINC_graph_regression.py --gpu_id 0 --config 'configs/GatedGCN_ZINC_OAP.json' --dataset ZINC-full

and compare to EPNN as in the latex file.



If you use our code, please cite

```
@inproceedings{canonicalization-perspective,
    title={{A Canonicalization Perspective on Invariant and Equivariant Learning}},
    author={Ma, George and Wang, Yifei and Lim, Derek and Jegelka, Stefanie and Wang, Yisen},
    booktitle={NeurIPS},
    year={2024}
}
```
