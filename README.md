# Food-Calories-ESP32CAM-Tensorflow-Lite

Program ini berisi sistem pengenalan kalori makanan menggunakan Tensorflow Lite dengan ESP32CAM sebagai IP Camera

###### Persiapan sebelum menggunakan <br />
1. Install Python >=3.6 dan semua library (Dapat menggunakan Anaconda) atau ikuti https://github.com/EdjeElectronics/TensorFlow-Object-Detection-API-Tutorial-Train-Multiple-Objects-Windows-10#2-set-up-tensorflow-directory-and-anaconda-virtual-environment <br />
2. Install Tensorflow 1.15 <br />
3. Install pyrebase (Database Firebase) <br />
4. Install pyqt5 <br />
5. Install pyqt5-tools <br />
6. Install Arduino IDE <br />
7. Install Install Arduino JSON <br />
8. Install Library ESP32CAM <br /> 

###### Cara menggunakan <br />

1. Buka Python dan ketikan <br />
- Untuk mengetahui IP Address dari ESP32CAM <br />
'''
python ipscanner.py
'''

- Untuk membuka sistem <br />
'''
python kalori.py --modeldir=tflite
'''

###### Catatan<br />
- Ganti SSID dan Password WiFi pada program ESP32CAM <br />
- Ganti IP Address pada program kalori.py<br />
<br />
<br />
<br />
<br />
<br />
<br />

###### Author <br />

ASNProject<br />
email: asnproject02@gmail.com
