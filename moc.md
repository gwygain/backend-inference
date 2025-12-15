# Map of content

**WandB Report**

https://api.wandb.ai/links/duncanb013-polytechnic-university-of-the-philippines/spgwv1nq

![](wandb-report-qr.png)

## Datasets and models

The uploaded [QC dataset](https://www.kaggle.com/datasets/pipluppp/quezon-city-informal-settlements) used in training and testing and the  [trained_models/](trained_models)

## Training runs

Kaggle notebook runs for the six models, together with the local copies of the notebooks with output. 

- **ConvNeXt UNet decoder Satellite** ([Kaggle notebook](https://www.kaggle.com/code/pipluppp/2025-09-23-unetdecoder?scriptVersionId=285953239) and [Local copy](kaggle_runs\convnext-unet-satellite.ipynb))
- **ConvNeXt encoder-decoder Satellite** ([Kaggle notebook](https://www.kaggle.com/code/kcbognot/2025-9-22-baseline-training?scriptVersionId=263273041) and [Local copy](kaggle_runs\convnext-satellite.ipynb))
- **ConvNeXt encoder-decoder Building count** ([Kaggle notebook](https://www.kaggle.com/code/togepiiiiiiiiiiiii/2025-9-22-baseline-training?scriptVersionId=263269916) and [Local copy](kaggle_runs/convnext-bc.ipynb))
- **ConvNeXt encoder-decoder Building height** ([Kaggle notebook](https://www.kaggle.com/code/lannzsalalima/2025-9-22-baseline-training?scriptVersionId=263273331) and [Local copy](kaggle_runs/convnext-bh.ipynb))
- **ConvNeXt encoder-decoder Pixel-level fusion All** ([Kaggle notebook](https://www.kaggle.com/code/gwynethannegabales/2025-9-22-baseline-training?scriptVersionId=263273075) and [Local copy](kaggle_runs/convnext-fusion-all.ipynb))
- **SettleNet Progressive CBAM attention fusion All** ([Kaggle notebook](https://www.kaggle.com/code/togepiiiiiiiiiiiii/2025-09-23-settlenet) and [Local copy](kaggle_runs/settlenet-all.ipynb) )


## Test inference, Stat test, and Logging to WandB

Kaggle notebook runs for the model inference of the six models on the test set, and the statistical test for SOP 3

- **Model inference of the six models on the test set and Statistical Test** ([Kaggle notebook](https://www.kaggle.com/code/pipluppp/thesis-significance-testing?scriptVersionId=285986599), [Local copy](kaggle_runs/model_inference.ipynb))
- **Stat test** ([Kaggle notebook](https://www.kaggle.com/code/pipluppp/thesis-significance-testing?scriptVersionId=286138235) and [Local copy](kaggle_runs/stat-test.ipynb))
- **WandB Log all confusion matrix, metrics, stat tests across all models and test set** ([Kaggle notebook](https://www.kaggle.com/code/pipluppp/thesis-significance-testing?scriptVersionId=286370967), [WandB run](https://wandb.ai/duncanb013-polytechnic-university-of-the-philippines/settlement-segmentation/runs/sub3qnxk), [WandB report](https://api.wandb.ai/links/duncanb013-polytechnic-university-of-the-philippines/spgwv1nq))

## Metrics, Stat Test data

The local copies of all the confusion matrix, metrics, stat test across all models

**Metrics**

- [SettleNet Logs](result_logs/settlenet-logs.csv)
- [ConvNeXt UNet satellite Logs](result_logs/convnext-unet-satellite-logs.csv)
- [ConvNeXt satellite Logs](result_logs/convnext-satellite-logs.csv)
- [ConvNeXt fusion all Logs](result_logs/convnext-fusion-all-logs.csv)
- [ConvNeXt building height Logs](result_logs/convnext-building-height-logs.csv)
- [ConvNeXt building count Logs](result_logs/convnext-building-count-logs.csv)

**Stat Test**

- [Per-image IoU and Difference](result_logs/stat-test-per-image-481.csv)
- [Statistical Test Statistics](result_logs/stat-test-statistics.csv)


## Validation

- **JC Peralta** (Faculty/Geospatial Machine Learning Consultant) [PDF](<Melchor - PUP-Certification-of-Validation.pdf>)
- **Kyle Melchor** (Senior Artificial Intelligence and Machine Learning Engineer) [PDF](<Peralta - PUP Certification of Validation.pdf>)
