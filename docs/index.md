# Looking further

This model classifies crop types for each field based on the field as well as on its surroundings.

![model_ecaas_agrifieldnet_bronze_v1](https://radiantmlhub.blob.core.windows.net/frontend-dataset-images/odk_sample_agricultural_dataset.png)

MLHub model id: `model_ecaas_agrifieldnet_bronze_v1`. Browse on [Radiant MLHub](https://mlhub.earth/model/model_ecaas_agrifieldnet_bronze_v1).

## Training Data

- [AgriFieldNet Competition Dataset - Source Imagery](https://api.radiant.earth/mlhub/v1/collections/ref_agrifieldnet_competition_v1_source)
- [AgriFieldNet Competition Dataset - Test Labels](https://api.radiant.earth/mlhub/v1/collections/ref_agrifieldnet_competition_v1_labels_train)

## Related MLHub Dataset

[AgriFieldNet Competition Dataset](https://mlhub.earth/data/ref_agrifieldnet_competition_v1)

## Citation

Ferreira, M.G. and Dung, T. "Looking further", Version 1.0, Radiant MLHub. [Date Accessed] Radiant MLHub

## License

[CC-BY-4.0](../LICENSE)

## Creators

MG Ferreira - Ferra Solutions www.ferrasolutions.com [LinkedIn](https://www.linkedin.com/in/mg-ferreira-35534)

Tien Dung

## Contact

Use linkedin to message.

## Applicable Spatial Extent

{{

Here please provide the applicable spatial extent, for new inferencing (this
may be the same, or different than the spatial extent of the training data).
Please provide the spatial extent bounding box as WKT text or GEOJSON text.

```geojson
{
  "type": "FeatureCollection",
  "features": [
    {
      "type": "Feature",
      "id": 1,
      "properties": {
        "ID": 0
      },
      "geometry": {
        "type": "Polygon",
        "coordinates": [
          [
              [-90,35],
              [-90,30],
              [-85,30],
              [-85,35],
              [-90,35]
          ]
        ]
      }
    }
  ]
}
```

<https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/creating-diagrams#creating-geojson-and-topojson-maps>

}}

## Applicable Temporal Extent

{{

The recommended start/end date of imagery for new inferencing. Example:

| Start | End |
|-------|-----|
| 2000-01-01 | present |

}}

## Learning Approach

{{

The learning approach used to train the model. It is recommended that you use
one of the values below, but other values are allowed.

- Supervised
- Unsupervised
- Semi-supervised
- Reinforcement-learning
- Other (explain)

}}

## Prediction Type

{{

The type of prediction that the model makes. It is recommended that you use one
of the values below, but other values are allowed.

- Object-detection
- Classification
- Segmentation
- Regression
- Other (explain)

}}

## Model Architecture

{{

Identifies the architecture employed by the model. This may include any string
identifiers, but publishers are encouraged to use well-known identifiers
whenever possible. More details than just “it’s a CNN”!

}}

## Training Operating System

{{

Identifies the operating system on which the model was trained.

- Linux
- Windows (win32)
- Windows (cygwin)
- MacOS (darwin)
- Other (explain)

}}

## Training Processor Type

{{

The type of processor used during training. Must be one of "cpu" or "gpu".

- cpu
- gpu

}}

## Model Inferencing

Review the [GitHub repository README](../README.md) to get started running
this model for new inferencing.

## Methodology

{{

Use this section to provide more information to the reader about the model. Be
as descriptive as possible. The suggested sub-sections are as following:

}}

### Training

{{

Explain training steps such as augmentations and preprocessing used on image
before training.

}}

### Model

{{

Explain the model and why you chose the model in this section. A graphical representation
of the model architecture could be helpful to individuals or organizations who would
wish to replicate the workflow and reproduce the model results or to change the model
architecture and improve the results.

}}

### Structure of Output Data

{{

Explain output file names and formats, interpretation, classes, etc.

}}
