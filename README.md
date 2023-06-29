# haberman-survival-dataset

Slightly modified copy of Haberman's Survival Data Set (<https://doi.org/10.24432/C5XK51>).

## Metadata

This repository contains the file `haberman.csv`.
It is a slightly modified version of the original `haberman.data`.
Here, the CSV contains a header, years are written with 4 instead of 2 numbers, and survival is `0` or `1`.
The file contains the following columns:

- `age`: Age of patient at time of operation (integer)
- `year`: Patient's year of operation (integer)
- `nodes`: Number of positive axillary nodes detected (integer)
- `survival`: Survival status (class attribute; integer) where `0` denotes that the patient died within 5 years and `1` denotes that the patient survived 5 years or longer.

## Citation

This repository contains a copy of the UCI Machine Learning Repository dataset.

If you publish material based on databases obtained from this repository, then, in your acknowledgements, please note the assistance you received by using the UCI's repository.
This will help others to obtain the same data sets and replicate your experiments.
We suggest the following pseudo-APA reference format for referring to this repository:

> Haberman, S. (1999). Haberman's Survival. UCI Machine Learning Repository. https://doi.org/10.24432/C5XK51.

Here is a BiBTeX citation as well:

```bibtex
@misc{dua2017haberman,
  author = {Haberman, S},
  title = {{Haberman's Survival}},
  year = {1999},
  howpublished = {UCI Machine Learning Repository},
  doi = {10.24432/C5XK51}
  url = {https://doi.org/10.24432/C5XK51}
}
```

## Metadata

1. Title: Haberman's Survival Data

2. Sources:
   (a) Donor:   Tjen-Sien Lim (limt@stat.wisc.edu)
   (b) Date:    March 4, 1999

3. Past Usage:
   1. Haberman, S. J. (1976). Generalized Residuals for Log-Linear
      Models, Proceedings of the 9th International Biometrics
      Conference, Boston, pp. 104-122.
   2. Landwehr, J. M., Pregibon, D., and Shoemaker, A. C. (1984),
      Graphical Models for Assessing Logistic Regression Models (with
      discussion), Journal of the American Statistical Association 79:
      61-83.
   3. Lo, W.-D. (1993). Logistic Regression Trees, PhD thesis,
      Department of Statistics, University of Wisconsin, Madison, WI.

4. Relevant Information:
   The dataset contains cases from a study that was conducted between
   1958 and 1970 at the University of Chicago's Billings Hospital on
   the survival of patients who had undergone surgery for breast
   cancer.

5. Number of Instances: 306

6. Number of Attributes: 4 (including the class attribute)

7. [See the Metadata section.]

8. Missing Attribute Values: None
