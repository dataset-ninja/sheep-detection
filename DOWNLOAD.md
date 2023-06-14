Dataset **Sheep Detection** can be downloaded in Supervisely format:

 [Download](https://assets.supervise.ly/supervisely-supervisely-assets-public/teams_storage/k/z/qu/LHQuKiniDmOXAXMZdmewNMw6UkQU8eETkDvK6pmZmyEh58Q4MM428jMlwYAMNkVRVNMIc0l3b0O86CvbIQ92R231u9SfXulG0WmrkUsC88oQVa8Z6arF71EwKgVg.tar)

As an alternative, it can be downloaded with *dataset-tools* package:
``` bash
pip install --upgrade dataset-tools
```

... using following python code:
``` python
import dataset_tools as dtools

dtools.download(dataset='Sheep Detection', dst_path='~/dtools/datasets/Sheep Detection.tar')
```
The data in original format can be 🔗[downloaded here](https://www.kaggle.com/datasets/andrewmvd/sheep-detection/download?datasetVersionNumber=1)