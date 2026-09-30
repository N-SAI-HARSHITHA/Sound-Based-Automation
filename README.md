# Sound Based Automation

A sound-based automation project developed as a team project for the 19ECE384 – Open Lab course at Amrita School of Engineering, Coimbatore.

## Project Details

- Input: Sound signal from an electret microphone
- Frequencies: 1kHz, 5kHz and 10kHz
- Output: LED indication for each detected frequency
- Op-amp: µA741
- Filter: Fliege Bandpass Filter

## How It Works

The sound signal is picked up by an electret microphone and amplified before being passed through the frequency detection stages.

Three bandpass filter stages are used to detect 1kHz, 5kHz and 10kHz signals. The filtered signal is then passed through a peak detector and comparator. When the required frequency is detected, the corresponding LED turns on.

## Circuit

The circuit was built using op-amps, resistors, capacitors, diodes, LEDs and breadboards.

A block diagram and photos of the completed hardware are included in the repository.

## Results

The circuit was tested for 1kHz, 5kHz and 10kHz signals. The corresponding LED was activated when the required frequency was detected.

## Course

19ECE384 – Open Lab  
Amrita School of Engineering, Coimbatore
