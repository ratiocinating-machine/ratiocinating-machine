# Ratiocinating-Machine
A Machine that ratiocinates.

In order to launch it from the command line or as a Python subprocess:
```bash
echo "Theodotos-Alexandreus: Are language models seeking the Truth, machine?" \
  | uvx ratiocinating-machine \
    --provider-api-key sk-proj-... \
    --github-token ghp_... 
```

Or, with a local pip installation:
```bash
pip install ratiocinating-machine
```
Set the environment variables:
```bash
export PROVIDER_API_KEY="sk-proj-..."
export GITHUB_TOKEN="ghp_..."
```
Then:
```bash
ratiocinating-machine -a multilogue.txt
```
Or:
```bash
ratiocinating-machine multilogue.txt > response.txt
```
Or:
```bash
ratiocinating-machine -a multilogue.txt > tmp && echo tmp > multilogue.txt
```

Or use it in your Python code:
```Python
# Python
import ratiocinating_machine
```
