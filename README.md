# Pulse response of an RLC circuit analised in frequency and time domain
The abstract has been translated in English below, the report is in Italian.

## Abstract
In questo esperimento si è analizzata la risposta di un circuito RLC a un segnale impulsivo.
Misurando la tensione ai capi del condensatore, si è cercato di risalire alla pulsazione di
risonanza ω0 e al coefficiente di smorzamento γ, con valori attesi ω0 = 55.4(4) kHz e γ =
12.46(12) kHz. L’analisi nel dominio del tempo ha restituito ω0 = 56.9832(7) kHz e γ =
13.5017(14) kHz. Attraverso una trasformata di Fourier sul segnale di risposta, calcolata
grazie all’algoritmo FFT (fast Fourier tranform), è stata analizzata la risposta in frequenza,
ottenendo ω0 = 57.0549(10) kHz e γ = 13.521(2) kHz.

In this experiment the response of an RLC circuit to a pulse excitation was analised. Measuring the potential on the capacitator, the resonant angular frequency $\omega_0$ and the damping coefficient $\gamma$ were found. The expected values were $\omega_0 = 55.4(4)$ kHz and $\gamma = 12.46(12)$ kHz. An analysis in the time domained resulted in $\omega_0 = 56.9832(7)$ kHz and $\gamma = 13.5017(14)$ kHz. Apllying a Fourier transform to the signal, using an FFT (Fast Fourier Transform) algorithm, the frequency response was analysed as well, resulting in $\omega_0 = 57.0549(10)$ kHz and $\gamma = 13.521(2)$ kHz.

## Structure of the repository
```
.
├── README.md                                 # this file
├── analysis                                  # data analysis 
    ├── analysis.ipynb                        # Jupyter notebook used for the data analysis
    ├── *.pgf and *.tex                       # plots for the tex report
├── Relazione
    ├── RLC_pulse.pdf                              # report
    ├── ...
```
