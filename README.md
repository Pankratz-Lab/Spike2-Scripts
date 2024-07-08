# Spike2-Scripts

Spike-Delay (31/07/2020):
This Spike2-script measures the delay between two events in separate channels. To extract events from a recording (waveform channel) the Spike2-software offers several searching mode: peak (maximum detection), through (minimum detection), signal rising through a level and signal falling through a level. After event-extraction from your recordings, you can use this script to measure the delay in a semi-automatic manner. Additional functions were included into this script, like opening of a new file and saving the results. In our study, we used this script to measure the delay of a propagating action potential between two recording sites of one abdominal nerve in Drosophila larva for analysis of the conduction velocity.

GCaMP-recording (cycle frequency,08/07/2024):
This Spike2-script measures the cycle frequency (in Hz) between two “peaks” (calcium spikes). Analyzed GCaMP-recording are imported as a TXT-file into Spike2 as a waveform-channel. After running the script, select the button “Import” to extract all calcium-spikes as event. To do this, adjust the horizontal cursor “baseline” to the baseline of the recording and horizontal cursor “peak” to the minimum peak to be detected. The script extracts the events based on the time of a peak in the waveform and the level specified by the two horizontal cursor. After this process, the event-channel has to be saved. “Analysis” is used to calculate the cycle frequency for each event in a TXT-file.

