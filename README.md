# Blip-captioner-on-fashion-datasets
Finetuning blip on pairs of fashion products (image and a detailed description) to automatise captioning fashion product images)
## Packages nécessaires
Trois packages nécessaires à installer (torch, datasets et transformers) dont deux sont installables depuis le fichier requirements.txt via la commande 

```python
pip install -r requirements.txt
```
## Dataset
Le dataset utilisé pour l'entaînement est importé depuis huggingface (cf https://huggingface.co/docs/datasets/v1.16.0/upload_dataset.html por voir comment uploader et importer un dataset depuis huggingface:
Le dataset contient deux colonnes: image et description détaillée 

<table>
  <tr>
    <td align="center">
      <img src="watch.png" alt="Image" style="width:100%;">
    </td>
  </tr>
  <tr>
    <td align="center">
      <strong>a watch with pink leather strap and rose bezel with circular white dial with roman numerals</strong>
    </td>
  </tr>
</table>
