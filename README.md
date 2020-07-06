# workflow
Create a workflow for releases.

The workflow is as below:

There are a master and develop branch instead of a single master branch.
Feature branches use Develop as their parent branch.
Once work on features is done, the feature branches are merged into the develop branch.
Close to the 25th of the month, a release branch is created off the develop branch.
The release branch contains bug fixes if any and release documentation.
On the 25th of every month, the release branch is merged into the master branch as well as the develop branch.
