# How to contribute

Whether you are looking to report a bug, propose a new feauture or simply getting involved in the project, this document is intended as a guide/reference for you!

<a name="reporting_bugs"></a>

## Reporting Bugs
If you encounter any kind of issue with any of the Dyna&omega;o [repositories](https://github.com/dynawo), the first things to do is to ask for help creating an issue in the repository where the problem has been identified. If possible, explain in the most clear way the matter and try to associate one of the available labels to the issue. Any test case helping clarifying the issue can be added.

The github [repositories](https://github.com/dynawo) are the privileged environment to exchange informations.

If you experince any difficulty to create an issue on one of the Dyna&omega;o repository, you can also send an e-mail to [rte-dynawo@rte-france.com](mailto:rte-dynawo@rte-france.com).

## Creating a Pull Request
If you wish to contribute to one of the Dyna&omega;o [repositories](https://github.com/dynawo) proposing a patch on a newly created issue or an existing one, please create a dedicated [git branch](#branch_creation). Once you consider you contribution ready for being merged in the main repository branch, please create a pull request on the Dyna&omega;o github repository, it will be reviewed by the development team as soon as possible. If any modification/discussion is need on your contribution, you will be notified on the related pull request. Notice that there is also the possibility to open a pull request in a draft mode.

## Proposing enhancements
If you are interested in proposing a new feature, the first things to do is to ask for help creating an issue in the impacted repository.

If you experince any difficulty to create an issue on one of the Dyna&omega;o repository, you can also send an e-mail to [rte-dynawo@rte-france.com](mailto:rte-dynawo@rte-france.com).

<a name="branch_creation"></a>

## Creating and pushing a branch
To create a branch proposing a code contribution, you need first to create an issue in one of the Dyna&omega;o [repositories](https://github.com/dynawo).
Then, on your terminal, you can write:
``` bash
$> git checkout -b NUMBEROFISSUE_name_of_your_branch
```
Notice that NUMBEROFISSUE refers to the issue number reported in the github repository when an issue is created. The branch name must respect this convention to be considered as available in any Dynaw&omega;o repository
As soon your contribution is ready to be pushed on the repository, please use:
``` bash
$> git push
```
and follow the git instructions.

<a name="repositories"></a>

## Dyna&omega;o repositories
[Here](https://github.com/dynawo) you will find the list of available Dyna&omega;o repositories.