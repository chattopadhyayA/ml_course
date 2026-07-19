# Homework exercises

Each worksheet follows one clear path (the data, then preparing the data, then the algorithms, then judging the result) on one small,
intuitive dataset, so learners of any level can finish the core tasks while the more experienced
take the "Go further" challenges.

Each worksheet is written in simple B1 level English, with no special characters in the text, and
every task ends with four short notes: Check yourself, Why it matters, Fun fact (a real particle
physics connection), and Go further.

| Topic | Student file | Solutions file (internal) | Dataset | Methods |
|---|---|---|---|---|
| Supervised ML | `supervised_penguins_student.ipynb` | `supervised_penguins_solutions.ipynb` | Palmer Penguins | Decision Tree, SVM, Gradient Descent, Neural Network, Evaluation |
| Deep Learning | `deep_learning_student.ipynb` | `deep_learning_solutions.ipynb` | scikit-learn digits + text | Convolution, CNN, Tokens, Word order, Self attention |
| Unsupervised ML | `unsupervised_wine_student.ipynb` | `unsupervised_wine_solutions.ipynb` | Wine | K means clustering, choosing k, PCA, cluster evaluation |

Notes for mentors:
- Every worksheet runs in Google Colab with no setup: no extra installs and no large downloads.
- The `*_student.ipynb` files are for participants (blanks to fill). The `*_solutions.ipynb` files.
- Every solutions notebook was executed top to bottom with no errors, and each "Check yourself"
  target matches the real output.
- The deep-learning worksheet uses the small built-in digit images instead of MNIST, so it needs no
  download. The idea is the same as the MNIST lecture.
