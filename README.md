# fasttext-reducer
A tiny package (and standalone script) for downloading any pretrained fasttext word vector model to any desired location and then reducing its number of dimensions.

## Example usage
To download the English pretrained model, reduce it to 30 dimensions, and save it to `/Users/admin/`, you can run the following command:
```
python reduce_fasttext_models.py --root_dir /Users/admin --lang en --dim 30
```
