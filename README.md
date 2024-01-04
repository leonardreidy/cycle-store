# cycle-store

Storage for Cycle

## Installation

Assuming you are running `DevPod` follow the steps below:

1) Fire up `DevPod`
2) Click `Workspaces` in left sidepane if it is not already selected
3) Click `Create Workspace`
4) Copy/paste repository url `https://github.com/leonardreidy/cycle-store` to input under `Enter Workspace Source`
5) Choose default IDE (VSCode)
6) Enter a name for the workspace in the input under `Workspace Name`
7) Click `Create Workspace`

## Notes

The network that the store shares with the other containers is defined in this repo. As such, if you bring up the others in advance, they will fail as the network doesn't yet exist. I will revisit this later. For now, it is adequate as it is simply a matter of spinning up this container first.

Note also that if the chosen IDE is the browser variant of VSCode it should open automatically at:

`http://localhost:10800/?folder=/workspace`