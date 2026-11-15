Requirements:
- Python 3.11 (macOS, Linux, Windows)
- pyhealth==1.1.6
- torch>=2.2
- numpy<2
- pandas<2
- setuptools<81

Useful Commands:
- conda activate eecs568   #activates anaconda environment (change eecs568 to whatever your environment is named)
- python baseline_synthetic_mimic3_rnn.py --verify --root .   #checks for csv files in current directory path
- python baseline_synthetic_mimic3_rnn.py --dev --model rnn --epochs 5 --root .   #runs rnn model and generates results
