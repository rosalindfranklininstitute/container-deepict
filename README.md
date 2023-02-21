# container-deepict

Install as a module share module using `shpc`.

```
# Install
cd /path/to/registry
git clone git@github.com:rosalindfranklininstitute/container-deepict.git
shpc install deepict

# Update
cd /path/to/registry/deepict
git pull
shpc install deepict

# Usage
module load deepict

# Open deepict GUI by running
deepict

# Run commands against the container
deepict-run which deepict
# gives the path within the container to the install location
/usr/local/deepict/bin/deepict

# Print the module usage help
module help deepict
```

This module aliases `deepict` to `/usr/local/deepict/bin/deepict` within the container. 