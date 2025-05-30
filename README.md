# Finland Swedish Mispronunciation Detection
Code for the paper  
**“Mispronunciation Detection Without L2 Pronunciation Dataset in Low-Resource Setting: A Case Study in Finland Swedish”** (Interspeech 2025).

---

## Contents
| File | Purpose |
|---------------|---------|
| `temperature_scaling.ipynb` | Main notebook – temperature scaling and top-k normalization |
| `environment.yaml` | Exact Conda environment (optional) |

---

## Quick start
The algorihtm is very simple, so you can run without any specific requirement. However, you can also install the full environment from the yaml file

```bash
# optional: reproducible environment
conda env create -n FinSwe -f environment.yaml
conda activate FinSwe
```
Run the notebook **[`temperature_scaling.ipynb`](temperature_scaling.ipynb)**. Of course you still need the Wav2vec 2.0 model and an audio file.

---

## Word lists used in our experiments (Table 2 in the paper)

<details>
<summary><strong>'fara', 'göra'</strong></summary>

```text
fara, göra
```
</details>

<details>
<summary><strong>/rt/ and /u:/</strong></summary>

```text
bort, kors, kort, korta, borta  
telefon, telefonen, telefoner
```
</details>

<details>
<summary><strong>Others</strong></summary>

```text
sju, sjuk, sjuka, stjärna  
sport  
köpa  
kyrka, kyrkan, kyrkas  
kina  
kök  
tjära, tjärn, tjugo, tjugofem  
kjol, kjolar  
tjena, tjejen, tjejet  
domare, domaren  
döma, dömas  
skjorta, skjortan, skjortor  
djur, djuren, djuret  
djup, djupa, djupt, djupare  
djärvare
```
</details>

---

# Citation
Phan, N., Kuronen, M., Kautonen, M., Ullakonoja, R., von Zansen, A., Getman, Y., Voskoboinik, E., Grósz, T., Kurimo, M. (2025) Mispronunciation Detection Without L2 Pronunciation Dataset in Low-Resource Setting: A Case Study in Finland Swedish. Accepted in Interspeech 2025.  

```bibtex
@inproceedings{phan25,
  title     = {Mispronunciation Detection Without L2 Pronunciation Dataset in Low-Resource Setting: A Case Study in Finland Swedish},
  author    = {Nhan Phan and Mikko Kuronen and Maria Kautonen and Riikka Ullakonoja and Anna {von Zansen} and Yaroslav Getman and Ekaterina Voskoboinik and Tamás Grosz and Mikko Kurimo},
  year      = {2025},
}

```

# License
Our work is shared under [Creative Commons Attribution 4.0 International (CC-BY-4.0)](https://creativecommons.org/licenses/by/4.0/)
