# MD-PINN
> [**AAAI'24 Accept**] [**An Interpretable Approach to the Solutions of High-Dimensional Partial Differential Equations**](https://ojs.aaai.org/index.php/AAAI/article/view/30050)

This project is a comparative experiment of the article: A program for solving multidimensional PDE(partial differential equations) based on PINN.  This program import [deepxde](https://github.com/lululxvi/deepxde) as a module, with reference to its example.

本项目是文章的对比实验：基于 PINN 的多维 PDE（偏微分方程）求解程序。本程序导入了[deepxde](https://github.com/lululxvi/deepxde) 作为模块，并参考了其示例。
## PDE Introduction
There are 3 types of PDE: Advection, Heat and Poission, every PDE have 2 different definitions. We worked out every 2D and 3D solusion of every definition of PDE. Detail materials are shown in .ipynb files. 

本次求解的PDE 有 3 种类型：Advection, Heat 和 Poission，每种 PDE 给定 2 种不同的定义。 我们计算出了 每个PDE每个定义的2D和3D解。 更多详细内容在 .ipynb 文件中。
## Dataset
Generated test datas ( from [Lulu Cao](https://github.com/grassdeerdeer)) are put on three floders. In this work, we did not use train data in PINN trainning.

测试数据已生成好（来自[曹璐璐](https://github.com/grassdeerdeer)），并放在三个文件夹中。 在这项工作中，我们没有在 PINN 训练中使用数据进行训练。
## Bibliography
If you find our paper or code helpful, consider citing:

如果您认为这篇文章或这份代码有用, 请引用:
```bibtex
@inproceedings{cao2024interpretable,
  title={An Interpretable Approach to the Solutions of High-Dimensional Partial Differential Equations},
  author={Cao, Lulu and Liu, Yufei and Wang, Zhenzhong and Xu, Dejun and Ye, Kai and Tan, Kay Chen and Jiang, Min},
  booktitle={Proceedings of the AAAI Conference on Artificial Intelligence},
  volume={38},
  number={18},
  pages={20640--20648},
  year={2024}
}
```

