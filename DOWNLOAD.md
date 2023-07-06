Dataset **Fish Market** can be downloaded in Supervisely format:

 [Download](https://assets.supervisely.com/supervisely-supervisely-assets-public/teams_storage/W/5/2S/MWkvG7AGd4xde2uaUyRM9ox730FvPTXZMhbk7jEUITLaOEqSuJIu7fas4rVfBoshCom5ekfQbcZpJjtMo7UjbTjNkkPVan2W7QaNbkB9z71InCUtr9p3RCYoWukD.tar)

As an alternative, it can be downloaded with *dataset-tools* package:
``` bash
pip install --upgrade dataset-tools
```

... using following python code:
``` python
import dataset_tools as dtools

dtools.download(dataset='Fish Market', dst_path='~/dtools/datasets/Fish Market.tar')
```
The data in original format can be 🔗[downloaded here](https://universe.roboflow.com/roboflow-100/fish-market-ggjso/dataset/6/download/coco)