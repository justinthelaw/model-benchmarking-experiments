# Model Benchmarking Experiments

## Whisper Benchmarking

IMPORTANT NOTE:
1. whispercpp only support CPU inferencing
2. faster-whisper supports CPU or GPU inferencing
3. whisper (base) supports CPU or GPU inferencing

Add and remove authoritative-source-of-truth transcripts (baselines) in the `samples/truth/` directory, and ensure the audio files of the same name goes into `samples/audio/`. Use the `samples/**/hide/` directories to hide audio and text files from the script during a run.

Press the "Run All" button in the Jupyter Notebook to do a full run of the transcription and accuracy analysis process.

Please see the following [Google Sheet](https://docs.google.com/spreadsheets/d/1waInbma8AZGSw99mrOVGwpe1hyKE_xTeL_PRzQHRo2s/edit?usp=sharing) for the in-progress benchmarks.

## Todo:
- Import base whisper package for benchmarking
- Automate posting to a csv file
- Complete the benchmarks on law-desktop
- Add more inferencing options
- Ensure this works on other GPUs, CPUs, and OSs