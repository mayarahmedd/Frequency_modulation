# Frequency_modulation
3.1 I NTRODUCTION
Frequency modulation (FM) is a modulation type in which the instantaneous frequency of the carrier is
changed according to the message amplitude. The motive behind the frequency modulation was to
develop a scheme with inherent ability to combat noise. The noise, being usually modeled as additive, has
a negative effect on the amplitude by introducing unavoidable random variations which are superimposed
on the desired signal. Unlike the amplitude, frequency has a latent immunity against noise. Since it resides
“away” from the amplitude, any changes in the amplitude would be completely irrelevant to the
frequency. In other words, there is no direct correlation between the variation in amplitude and
frequency, thus making FM a better candidate over AM with respect to noise immunity. However, what
FM gains in noise immunity lacks in bandwidth efficiency. Since FM usually occupies larger bandwidth, AM
is considered more bandwidth wise.
3.2 AIM
In this experiment, we investigate the narrowband frequency modulation when the SNR is varied.
Students are expected to:
1. Develop an appreciation of FM ability to counteract noise.
2. Be able to simulate the generation and the demodulation of NBFM using matlab.
3. To be able to tell the similarities and differences between AM and NBFM.
3.3 P ROCEDURE
1. Repeat steps 1 through four in experiment 1,2.
2. Generate the NBFM signal. Use a carrier frequency of 100kHz and a sampling frequency of 𝐹 𝑠 =
5𝐹 𝑐 . Plot the resulting spectrum. What can you make out of the resulting plot?
3.what is the condition we needed to achieve NBFM.
4. Demodulate the NBFM signal using a differentiator and an ED. For the differentiator, you can
use the following command: diff. Assume no noise is introduced.
3.4 U SEFUL COMMANDS
audioread, fft, fftshift, ifft,ifftshift, awgn, upsample,resample, sound,hilbert, abs,mean,cumsum,diff
