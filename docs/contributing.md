# Please contribute!

The Pyrates would love help in building out this repository! There exists a multidude of resources across the internet for practicing Python, but we want a spot where:

* Problems are organized by topic, and somewhat ordered by difficulty
* Exercises and solutions are version controlled
* Exercises are posted in a place where you can easily run the code (a Colab notebook)
* Anyone can access these problems
* Anyone can contribute/add problems and solutions

## Steps to contribute

As such, building out this repo is a way we can accomplish all of these goals. It will take some work, so we'd love it if you contributed. Here are the steps to doing so:

1. Look at the [open issues](https://github.com/PDXPythonPirates/python-practice-problems/issues) page for areas where we need help and pick a specific problem to tackle.
2. Fork this repository to your own GitHub account. We recommend calling it `python-practice-problems-{your-first-name}` (e.g., `python-pracitce-problems-bryan` if you are blessed with such an awesome name).
3. Clone the fork to your local machine.
4. Connect your fork to the upstream `python-practice-problems` repository.
5. Before you begin making edits, pull the latest code
6. Create a new branch and make edits. Edits will be at least one of the following, and guidelines for how to do these are given in [the following section](#edit-guidelines).
    * Adding exercise ideas to a problem set
    * Creating an exercise notebook (or notebooks) for problem(s) in a problem set
    * Creating a solution notebook (or notebooks) for problem(s) in a problem set
    * Updating readmes to make these problems easy to find
7. Review your changes and push them to your fork
8. Submit a pull request
9. After a review, make any necessary changes

## Edit guidelines

Follow these guidelines when doing the following updates.

## Creating a new problem set

If you are creating a new problem set ... 

1. Add an apporpiately named folder in the [`problem_sets`](../problem_sets/) folder and keep all related resources there. For example, all of the problems related to the `print()` function are in [`problem_sets/print/`](../problem_sets/print/).
2. Update the main [repo README](../README.md) to list this new problem set and add a link to the new folder.
3. Add a README.md file to the folder you created. This is where the exercises and their solutions will be listed. At the top of the README add a title and a note that exercises are generally listed in order of difficulty and put a disclaimer that presented solutions are not the only solution. Fee free to copy the paragraph at the top of [the `print()` README](../problem_sets/print/README.md).

## Adding problems to a problem set

1. Feel free to add ideas for exercises even if you aren't adding the exercise or solution notebooks. Having these problems in a single spot is helpful!
2. If you came up with the exercise on your own, feel free to give yourself credit, else add a link to the original author and url.

## Creating notebooks for exercises and solutions

1. Exercises and their solutions should be saved in separate folders – encouraging the user to figure the problem out on their own before viewing the solution.
2. Exercises and solutions should be stored in a folder of the same name within the appropriate problem set. For example, [../problem_sets/print/exercises/](../problem_sets/print/exercises/) and [../problem_sets/print/solutions/](../problem_sets/print/solutions/).
3. The name of the notebook should reference the exercise number within the problem set and a couple keywords that hints at the content of the exercise. For example, the first exercise in the [`print() problem set`](../problem_sets/print/) is titled [01_print_multiple_lines.ipynb](../problem_sets/print/exercises/01_print_multiple_lines.ipynb).
4. Make sure that instructions at the top of exercises and their corresponding solutions _are the exact same_.
5. After adding exercise and solution notebooks, provide a link to these notebooks in the problem set README. These links should not be relative links to the notebooks, but links to [Google Colaboratory](https://colab.research.google.com) that point to the notebooks on the GitHub repo. The urls will look like `https://colab.research.google.com/github/PDXPythonPirates/python-practice-problems/blob/main/problem_sets/{problem_set}/{exercises}/{file}.ipynb` and `https://colab.research.google.com/github/PDXPythonPirates/python-practice-problems/blob/main/problem_sets/{problem_set}/{solutions}/{file}.ipynb`. See the [`print()` problem set README](../problem_sets/print/README.md) for an example.

**Note on above!** The fact that notebook links are not relative means they won't work until your updates are pulled into the main branch. This is a nuisance that we don't have a remedy for at the moment.