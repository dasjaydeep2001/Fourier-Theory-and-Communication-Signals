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
