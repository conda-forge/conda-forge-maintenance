Running the feedstock ``rerender`` script
-----------------------------------------

This script generates the ```MNT:``` pull requests which rerender with the latest conda-smithy.

```
heroku run python conda-forge.github.io/scripts/regenerate_feedstock.py --feedstocks-dir feedstocks --limit 5
```
