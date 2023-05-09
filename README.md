# Evaluation

We utilize 2 NVIDIA TITAN V GPU for testing. 

To evaluate the **PKSD** on the **market** dataset in "**dukemtmc-to-market**" setting, run:

```bash
# evaluate the target set "market" in "dukemtmc-to-market" setting on the PKSD.
python test_model.py  --dataset-target market1501 --dataset-source dukemtmc --data-dir your_data_dir --model-dir save_model_dir
```
