# NER-using-IndoBERT

Proyek ini merupakan proyek *Natural Language Processing* (NLP) untuk memenuhi tugas technical test menggunakan model IndoBERT. *Named Entity Recognition* (NER) merupakan salah satu metode NLP yang berfungsi untuk mengekstrak informasi penting dari teks tidak terstruktur.

## Deskripsi Proyek
Proyek ini bertujuan untuk mengembangkan sistem *Named Entity Recognition* yang mampu mendapatkan informasi jumlah barang, nama barang, motif dan dan lokasi pengiriman berdasarkan kalimat-kalimat tertentu.

## Tujuan
1. 
2. 

## Datasets
Dataset yang akan digunakan adalah ....

## Data Preparation
Pada tahapan data preparation dilakukan beberapa langkah, diantaranya:
1. 
2. 
3. 
   
## Pembuatan Model
Data dibagi kedalam data training dan data testing dengan perbandingan 90% data training, 10% data validation sedangkan testing menggunakan data terpisah.

### Model Configuration

| Parameter                          | Value        |
|------------------------------------|--------------|
| `output_attentions`                | ``      |
| `output_hidden_states`             | ``      |

### Training Configuration

| Parameter             | Value      |
|-----------------------|------------|
| `epochs`              | `3`        |
| `batch size`          | `16`        |

### Optimizer Configuration: AdamW

| Parameter             | Value                  |
|-----------------------|------------------------|
| `learning rate (lr)`  | `5e-5`                 |
| `epsilon (eps)`       | `1e-8`                 |
| `num_warmup_steps`    | `0`                    |

## Evaluasi Model
* F1-Score = 100%
  Kenapa hal ini terjadi, ada beberapa catatan

## Kesimpulan
