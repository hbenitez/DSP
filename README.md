# DSP
The Python functions for my signal processing under-graduate course include application-oriented programming excercises on Fourier analysis and digital filters design.  (Finite impulse reponse (FIR) and infinite impulse response (IIR)) 

(1) Discrete Fourier Transform

This routine calculates the real DFT and shows the effects of compressing and expanding signal time duration in the frequency domain by analyzing a Gaussian function.

(2) Discrete Fourier Transform-Autotuner application

Auto-Tune uses a proprietary device to measure and alter pitch in vocal and instrumental music recording and performances. To apply auto-tuning we use the frequency shift property as indicated in page 478 of the book Digital Signal Processing de John. G Proakis y Dimitris G. Manolakis, 2007:


(3) SignalCodificationDecodification

This code creates an input signal called tonemistery that  has to be decoded by automatically determining its frequency and time content. The routine tonegen(digitos) receives as inputs a five element vector and outputs the signal tonemistery that contains a frequency coded version of the input vector in addition to the interference signal and the noise. There is a second input to this routine tonegen(digitos,escala). The escala parameter indicates the  scalar that multiplies the interference additive signal plus the noise. The tonemistery signal must contain:


(4) FilteringBioAcousticSignals

Fauna and birds surveys based on bioacoustic signal processing provide useful information for biodiversity conservation decisions. In Colombia, the Insthumid foreituto
Alexander von Humboldt (IAvH) [1] carries out projects on bioacoustic monitoring that generate hundreds of recording time in the paramo and humid forests. Because of this large volume of information, the automatic analysis of these audio signals is necessary to recognize the species. A common procedure in the analysis of these  signals is insect noise filtering from bird calls in teh recordings. For instance, the spectrogram of the bird Tucan pechiblanco (Ramphastos tucanus)  [2] is displayed below. The objetive of this progamming exercise is to analyze this bioacoustic signal to remove the frequency component that  correspond to insect noise by using finite impulse response (FIR) and infinite impulse response (IIR) filters.

http://www.humboldt.org.co/es/

https://xeno-canto.org/442392

(5) ConvolutionalLayer

This code implements the convolutional layer of a  CNN. This CNN receives an input RGB image along with a 3D filter specified by the user. The next stage adds a randomly generated bias to the the CNN output. Then, the ReLU (rectified linear unit) activation function transforms this output to generate a feature map.  

(6) SpectralEstimationWindowsFunctions

This code illustrates the effects of 'spectral leakage' and how can it be decreased by truncating the signal with triangular, Hamming, and Hanning windows.



