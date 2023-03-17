## QRS complex detection
This code processes ECG data and performs various operations on it. It imports various libraries, including numpy, matplotlib, scipy, and opensignalsreader.

The OpenSignalsReader function from the opensignalsreader library reads in ECG data from a file and stores it in data. The conversor function converts the data to millivolts.

The find_peaks function from the scipy.signal library identifies the peaks of the ECG signal and returns their positions as peaks. findHeight function then takes in the ECG signal and the positions of its peaks and calculates the heights of the peaks.

The code then prints out various statistics related to the ECG data, such as the mean amplitude of the QRS complex and the frequency of the ECG. It then plots the ECG signal with the detected peaks highlighted.

The code then applies various filtering techniques to the ECG signal, including a notch filter at 50 Hz and a Wiener filter. It then performs the same peak detection analysis on the filtered signal and prints out the statistics again. Finally, it plots the filtered signal with the detected peaks highlighted.

Overall, this code is a demonstration of how to process and analyze ECG data using Python libraries. It shows how to read in ECG data from a file, convert it to millivolts, detect peaks in the signal, and apply filters to the data to remove baseline noise.
