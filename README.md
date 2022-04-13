# md-setup-gist-cross-solvation
Starting structures and parameter files for the paper "Grid Inhomogeneous Solvation Theory for Cross-Solvation in Rigid Solvents"

Molecule naming is as follows:
| Abbreviation | Molecule  |
| ------------ | --------- |
| ALN | Aniline |
| BZN | Benzene |
| CL3 | Chloroform |
| CX4 | Tetrachloromethane |
| DMD | Dimethylacetamide |
| MTL | Methanol |
| PPN | Acetone (Propanone) |
| PRN | Pyridine |
| TOL | Toluene |
| WAT | Water |

The parameter files for water are missing because TIP3P was used. The parameter files for CL3 are taken from AmberTools. All other parameter files were generated using antechamber, and charges were produced using a RESP fit based on HF/6-31G* calculations performed in Gaussian 16.

# References
* Gaussian 16, Revision C.01, M. J. Frisch, G. W. Trucks, H. B. Schlegel, G. E. Scuseria, M. A. Robb, J. R. Cheeseman, G. Scalmani, V. Barone, G. A. Petersson, H. Nakatsuji, X. Li, M. Caricato, A. V. Marenich, J. Bloino, B. G. Janesko, R. Gomperts, B. Mennucci, H. P. Hratchian, J. V. Ortiz, A. F. Izmaylov, J. L. Sonnenberg, D. Williams-Young, F. Ding, F. Lipparini, F. Egidi, J. Goings, B. Peng, A. Petrone, T. Henderson, D. Ranasinghe, V. G. Zakrzewski, J. Gao, N. Rega, G. Zheng, W. Liang, M. Hada, M. Ehara, K. Toyota, R. Fukuda, J. Hasegawa, M. Ishida, T. Nakajima, Y. Honda, O. Kitao, H. Nakai, T. Vreven, K. Throssell, J. A. Montgomery, Jr., J. E. Peralta, F. Ogliaro, M. J. Bearpark, J. J. Heyd, E. N. Brothers, K. N. Kudin, V. N. Staroverov, T. A. Keith, R. Kobayashi, J. Normand, K. Raghavachari, A. P. Rendell, J. C. Burant, S. S. Iyengar, J. Tomasi, M. Cossi, J. M. Millam, M. Klene, C. Adamo, R. Cammi, J. W. Ochterski, R. L. Martin, K. Morokuma, O. Farkas, J. B. Foresman, and D. J. Fox, Gaussian, Inc., Wallingford CT, 2016.
* D.A. Case, I.Y. Ben-Shalom, S.R. Brozell, D.S. Cerutti, T.E. Cheatham, III, V.W.D. Cruzeiro, T.A. Darden,
R.E. Duke, D. Ghoreishi, G. Giambasu, T. Giese, M.K. Gilson, H. Gohlke, A.W. Goetz, D. Greene, R Harris,
N. Homeyer, Y. Huang, S. Izadi, A. Kovalenko, R. Krasny, T. Kurtzman, T.S. Lee, S. LeGrand, P. Li, C. Lin,
J. Liu, T. Luchko, R. Luo, V. Man, D.J. Mermelstein, K.M. Merz, Y. Miao, G. Monard, C. Nguyen, H.
Nguyen, A. Onufriev, F. Pan, R. Qi, D.R. Roe, A. Roitberg, C. Sagui, S. Schott-Verdugo, J. Shen, C.L.
Simmerling, J. Smith, J. Swails, R.C. Walker, J. Wang, H. Wei, L. Wilson, R.M. Wolf, X. Wu, L. Xiao, Y.
Xiong, D.M. York and P.A. Kollman (2019), AMBER 2019, University of California, San Francisco.
* C. I. Bayly, P. Cieplak, W. Cornell and P. A. Kollman. A well-behaved electrostatic potential based method using charge restraints for deriving atomic charges: the RESP model. The Journal of Physical Chemistry 1993 Vol. 97 Issue 40 Pages 10269-10280. DOI: 10.1021/j100142a004
* W. L. Jorgensen, J. Chandrasekhar, J. D. Madura, R. W. Impey and M. L. Klein. Comparison of Simple Potential Functions for Simulating Liquid Water. Journal of Chemical Physics 1983 Vol. 79 Issue 2 Pages 926-935
