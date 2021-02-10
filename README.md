# Pain Paints w.r.t Synapse Notebooks Experience

## 1) Why `.json` and not `.ipynb`?

No further comments.

## 2) No clear file system?

In every Jupyter notebook experience I've EVER used, if I open a notebook, the files associated with the directory will be available from within the notebook. This is not the case with Synapse Notebook UI.

If I run the the below snippet from [example.ipynb](example.ipynb) inside of the Synapse Studio UI, I don't see a `synapse_studio_pain_point/` as a directory, nor does `config.json` show up as a file in the current directory.

Not only that, but there is no way in the UI to import a file that isn't a `.ipynb` right now.

As someone who might be labeled with the the "developer" persona, it is hard for me to imagine adopting a product that does not have this functionality.

```python
import os
print(os.getcwd())
print(os.listdir())
```