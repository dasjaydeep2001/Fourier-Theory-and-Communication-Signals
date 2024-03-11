# Fourier-theory-and-communication-signals
We identify deterministic signals as a class of signals whose waveforms are defined exactly as function of time. Mathematical description of such signals using Fourier transform that provides the link between the time-domain and frequency-domain descriptions of a signal. 
The waveform of a signal and its spectrum are two natural vechicles to understand the signal.

# Rectangular Pluse
## Parameters:
        t (array_like): Array of time values.
        T (float): Pulse width (duration of the pulse).
        A (float): Pulse amplitude.

    Returns:
        array_like: Array of pulse values corresponding to input time values.
# Rectangular pulse using Fourier series representation.
## Parameters:
        t (array_like): Array of time values.
        T (float): Pulse width (duration of the pulse).

    Returns:
        array_like: Array of pulse values corresponding to input time values.
# Exponential Pluse
## Parameters:
        t (array_like): Array of time values.
        tau (float): Time constant of the exponential decay.
        A (float): Pulse amplitude.

    Returns:
        array_like: Array of pulse values corresponding to input time values.
# Combination of Exponential Pulses
Consider a double exponential pluse.
#  Radio frequency (RF) pulse.
## Parameters:
        t (array_like): Array of time values.
        f (float): Frequency of the RF pulse (in Hz).
        A (float): Amplitude of the RF pulse.

    Returns:
        array_like: Array of pulse values corresponding to input time values.
#  Gaussian Pulse
## Parameters:
        t (array_like): Array of time values.
        sigma (float): Standard deviation of the Gaussian pulse.
        A (float): Amplitude of the Gaussian pulse.

    Returns:
        array_like: Array of pulse values corresponding to input time values.
#  Triangular pulse
## Parameters:
        t (array_like): Array of time values.
        T (float): Width of the triangular pulse (duration from peak to zero).
        A (float): Amplitude of the triangular pulse.

    Returns:
        array_like: Array of pulse values corresponding to input time values.
#  Real and Imaginary Parts of a time Function
   Define the time value
   Define the complex time function (example: sinusoidal function)
   Extract the real and imaginary parts of the complex function
#  convolution in the time domain
##  Parameters:
        x (array_like): Input signal.
        h (array_like): Impulse response.

    Returns:
        array_like: Convolved signal.
# Conjugate Functions
Define the complex-valued function (example: sinusoidal function)
Compute the complex conjugate
Plot the real and imaginary parts of the original and conjugate functions
# Time scaling on a signal
##  Parameters:
        signal (array_like): Input signal.
        scale_factor (float): Factor by which to scale the time axis.
    
    Returns:
        array_like: Time-scaled signal.
# Area under the curve in the frequency domain
##  Parameters:
        freq (array_like): Array of frequencies.
        magnitude (array_like): Array of magnitudes corresponding to frequencies.

    Returns:
        float: Area under the curve in the frequency domain.
# Duality
Duality in communication systems often involves operations such as convolution and multiplication, or modulation and demodulation, where operations in the time domain have corresponding operations in the frequency domain, and vice versa.
# The Delta Function as a Limiting form of the Gaussian Pulse
## Parameters:
        t (array_like): Array of time values.
        sigma (float): Standard deviation of the Gaussian pulse.
        A (float): Amplitude of the Gaussian pulse.

    Returns:
        array_like: Array of pulse values corresponding to input time values.
# Pulse Response of Ideal Low-pass Filter
## Parameters:
        frequency (array_like): Array of frequencies.
        cutoff_frequency (float): Cutoff frequency of the filter.

    Returns:
        array_like: Array representing the filter's frequency response.
# Ideal Sampling Function
## Parameters:
        t (array_like): Array of time values.
        T (float): Sampling period.

    Returns:
        array_like: Array representing the ideal sampling function.
        
