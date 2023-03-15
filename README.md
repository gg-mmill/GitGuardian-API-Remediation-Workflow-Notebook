# GitGuardian API Remediaion Workflow Kitchen Sink

## What
A [Jupyter Notebook](https://jupyter.org/install) to run locally to learn how to use the GitGuardian APIs.

The notebook walks through using the GitGuardian API for:  
- Authentication
- Listing triggered incidents
- Assigning incidents
- Unassign incidents
- Resovling incidents
- Ignoring incidents
- Sharing incidents
- Scaning for secrets (though you are likely better off using [ggshield](https://github.com/GitGuardian/ggshield) for that)

### Automating a workflow example
The last section of the notebook combines several steps into one!
With a single code execution the example
- Gets a list of the most recent triggered incidents
- Assigns the newest one to the first listed member of the workspace (owner in most cases)
- Generates and prints the sharing URL
- Prints the updated incident details as a json dump for further inspection


## How
Prerequisites:
- You will need to have [Jupyter Notebook](https://jupyter.org/install) installed for this to run locally. 
- You will need to have a GitGuardian account with Owner (preferred) or Member access. 

1. Clone this repo
2. `cd` to the folder locally
3. run the command `jupyter notebook` in your terminal
4. follow the instructions in the notebook

