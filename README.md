# Pain Paints w.r.t Synapse Notebooks Experience

## 1) Why note `.ipynb`?

I can't even.

## 2) No clear file system?

In every Jupyter notebook experience I've EVER used, if I open a notebook, the files associated with the directory will be available from within the notebook. This is not the case with Synapse Notebook UI.

If I run the the below snippet from [example.ipynb](example.ipynb) inside of the Synapse Studio UI, I don't see a `synapse_studio_pain_point/` as a directory, nor does `config.json` show up as a file in the current directory.

```python
import os
print(os.getcwd())
print(os.listdir())
```