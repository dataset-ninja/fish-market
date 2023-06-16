Dataset **Fish Market** can be downloaded in Supervisely format:

 [Download](https://assets.supervise.ly/supervisely-supervisely-assets-public/teams_storage/O/f/QI/aJWzwZ4EDEnmRL9e37GzddyWqc0FSJF507vAsyMOTyRakcUSUEeec52Gp5GpQkqGcvMs8f0RcJ0l9FrqBMvPvEWHKlPnXx9FdpHA0tAtpxDTXIIjCFFKtj1s27IF.tar)

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