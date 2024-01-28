# Belajar Pengembangan Machine Learning

## Proyek Pertama: Membuat Model NLP dengan TensorFlow
### Hasil
Training completed successfully! Accuracy and val_accuracy are both above 92%. Stopping training.
400/400 - 3s - loss: 0.1159 - accuracy: 0.9577 - val_loss: 0.3036 - val_accuracy: 0.9222 - 3s/epoch - 7ms/step
![image](https://github.com/AditiaW/dicoding-belajar-pengembangan-machine-learning/assets/106371535/0b87fcf1-6e70-4a4c-a68f-3b682884661c)

### Kriteria Submission
- Dataset minimal 1000 sampel.
- Menggunakan LSTM dalam arsitektur model.
- Model sequential.
- Validation set 20% dari total dataset.
- Menggunakan Embedding.
- Fungsi tokenizer.
- Akurasi minimal 75% pada train dan validation set.

### Penilaian
Submission dinilai dengan skala 1-5 berdasarkan parameter yang ada. Saran untuk mendapatkan nilai tinggi:
- Akurasi di atas 80%.
- Implementasikan callback.
- Plot loss dan akurasi saat training dan validation.

![image](https://github.com/AditiaW/dicoding-belajar-pengembangan-machine-learning/assets/106371535/3c65e6b3-5ce4-4b77-87b8-4328790e4932) Semua ketentuan terpenuhi, namun terdapat indikasi plagiat yaitu dengan menggunakan proyek orang lain dan hanya mengubah kontennya saja.

![image](https://github.com/AditiaW/dicoding-belajar-pengembangan-machine-learning/assets/106371535/3450e5b2-68aa-4447-8add-cf36da1cae23) Semua ketentuan terpenuhi, namun penulisan kode berantakan.

![image](https://github.com/AditiaW/dicoding-belajar-pengembangan-machine-learning/assets/106371535/355d6808-5b78-4562-a3a4-cb9bf84e1073) Semua ketentuan terpenuhi namun hanya mengikuti seperti apa yang ada pada modul.

![image](https://github.com/AditiaW/dicoding-belajar-pengembangan-machine-learning/assets/106371535/5798b58a-a237-4b7d-a664-361dda51fd8f) Semua ketentuan terpenuhi, dataset memiliki minimal 2000 sampel data dan akurasi pada training set dan validation set di atas 85%.

![image](https://github.com/AditiaW/dicoding-belajar-pengembangan-machine-learning/assets/106371535/a87b5f34-2b0f-42cd-87cd-fc3cc5d7aec6) Semua ketentuan terpenuhi, dataset memiliki 3 kelas atau lebih dan minimal 2000 sampel data. Serta akurasi pada training set dan validation set di atas 90%.

## Proyek Kedua: Membuat Model Machine Learning dengan Data Time Series
### Hasil
MAE and val_mae < 2.00 (2.25% of data scale). Training stopped.
754/754 [==============================] - 22s 28ms/step - loss: 0.9933 - mae: 1.3832 - val_loss: 1.5547 - val_mae: 1.9892
![image](https://github.com/AditiaW/dicoding-belajar-pengembangan-machine-learning/assets/106371535/4e6b82d1-d007-45b1-a562-957c25f0aa12)

### Kriteria Submission
- Dataset minimal 1000 sampel.
- Menggunakan LSTM dalam arsitektur model.
- Validation set 20% dari total dataset.
- Model harus menggunakan model sequential.
- Menggunakan Learning Rate pada Optimizer.
- MAE < 10% skala data.

### Penilaian
Submission dinilai dengan skala 1-5 berdasarkan parameter yang ada. Saran untuk mendapatkan nilai tinggi:
- Dataset banyak sampel data.
- Implementasikan Callback.
- Plot loss dan akurasi saat training dan validation.

![image](https://github.com/AditiaW/dicoding-belajar-pengembangan-machine-learning/assets/106371535/3c65e6b3-5ce4-4b77-87b8-4328790e4932) Semua ketentuan terpenuhi, namun terdapat indikasi plagiat yaitu dengan menggunakan proyek orang lain dan hanya mengubah kontennya saja.

![image](https://github.com/AditiaW/dicoding-belajar-pengembangan-machine-learning/assets/106371535/3450e5b2-68aa-4447-8add-cf36da1cae23) Semua ketentuan terpenuhi, namun penulisan kode berantakan.

![image](https://github.com/AditiaW/dicoding-belajar-pengembangan-machine-learning/assets/106371535/355d6808-5b78-4562-a3a4-cb9bf84e1073) Semua ketentuan terpenuhi namun hanya mengikuti seperti apa yang ada pada modul.

![image](https://github.com/AditiaW/dicoding-belajar-pengembangan-machine-learning/assets/106371535/5798b58a-a237-4b7d-a664-361dda51fd8f) Semua ketentuan terpenuhi, dataset memiliki minimal 2000 sampel data dan MAE dari model < 10% skala data.

![image](https://github.com/AditiaW/dicoding-belajar-pengembangan-machine-learning/assets/106371535/a87b5f34-2b0f-42cd-87cd-fc3cc5d7aec6) Semua ketentuan terpenuhi, dataset memiliki minimal 10000 sampel data dan MAE dari model < 10% skala data.

## Proyek Akhir: Image Classification Model Deployment

### Hasil
Epoch 24/30
328/328 [==============================] - ETA: 0s - loss: 3.5001e-04 - accuracy: 0.9999Accuracy and val_accuracy >= 96.000% of targets. Training stopped.
328/328 [==============================] - 76s 232ms/step - loss: 3.5001e-04 - accuracy: 0.9999 - val_loss: 0.2678 - val_accuracy: 0.9601 - lr: 1.0000e-04
![image](https://github.com/AditiaW/dicoding-belajar-pengembangan-machine-learning/assets/106371535/70f8102c-0539-4c3d-ba9e-addcb94452f7)
![image](https://github.com/AditiaW/dicoding-belajar-pengembangan-machine-learning/assets/106371535/a4a5b497-3ef5-4d64-bf28-a94c26463284)

### Kriteria Submission
- Dataset minimal 1000 gambar.
- Dataset tidak pernah digunakan pada submission kelas machine learning sebelumnya.
- 80% train set dan 20% test set.
- Model sequential.
- Conv2D Maxpooling Layer.
- Akurasi pada training dan validation set minimal sebesar 80%.
- Menggunakan Callback.
- Membuat plot terhadap akurasi dan loss model.
- Menulis kode untuk menyimpan model ke dalam format TF-Lite.

### Penilaian
Submission dinilai dengan skala 1-5 berdasarkan parameter yang ada. Saran untuk mendapatkan nilai tinggi:
- Dataset lebih dari 2000 gambar.
- Implementasikan Callback.
- Gambar-gambar pada dataset memiliki resolusi yang tidak seragam.

### Detail Penilaian Submission
![image](https://github.com/AditiaW/dicoding-belajar-pengembangan-machine-learning/assets/106371535/3c65e6b3-5ce4-4b77-87b8-4328790e4932) 
Semua ketentuan terpenuhi, namun terdapat indikasi plagiat yaitu dengan menggunakan proyek orang lain dan hanya mengubah kontennya saja.

![image](https://github.com/AditiaW/dicoding-belajar-pengembangan-machine-learning/assets/106371535/3450e5b2-68aa-4447-8add-cf36da1cae23) 
Semua ketentuan terpenuhi, namun penulisan kode berantakan.

![image](https://github.com/AditiaW/dicoding-belajar-pengembangan-machine-learning/assets/106371535/355d6808-5b78-4562-a3a4-cb9bf84e1073) 
Semua ketentuan wajib terpenuhi, namun tidak terdapat improvisasi atau persyaratan opsional yang dipenuhi.

![image](https://github.com/AditiaW/dicoding-belajar-pengembangan-machine-learning/assets/106371535/5798b58a-a237-4b7d-a664-361dda51fd8f) 
Semua ketentuan terpenuhi, dataset memiliki minimal 2000 sampel gambar dan minimal 3 kelas. Serta akurasi pada training dan validation set minimal 85%.

![image](https://github.com/AditiaW/dicoding-belajar-pengembangan-machine-learning/assets/106371535/a87b5f34-2b0f-42cd-87cd-fc3cc5d7aec6) 
Semua ketentuan terpenuhi, dataset memiliki minimal 10000 gambar, resolusi gambar pada dataset tidak seragam. Serta akurasi pada training set dan validation set minimal 92%.

Jika submission Anda ditolak maka tidak ada penilaian. Kriteria penilaian bintang di atas hanya berlaku jika submission Anda lulus.

Diakses pada tanggal 28 Januari 2024 pukul 19:46:12.
