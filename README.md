# NLP-project

## Listen to the Generated Music
1.TRIGRAM

2.[FIFTYGRAM](https://soundcloud.com/mahi-dhoni-132311286/test-output-fiftygram?si=3d0b5bf5cede40ecba22a83acc0ae599&utm_source=clipboard&utm_medium=text&utm_campaign=social_sharing)

3.[HUNDREDGRAM](https://soundcloud.com/mahi-dhoni-132311286/hundred-gram?si=3d0b5bf5cede40ecba22a83acc0ae599&utm_source=clipboard&utm_medium=text&utm_campaign=social_sharing)

4.LSTM




This repository contains the code, dataset, and outputs related to the research project **"Automating the Process of Music Creation: A Study of LSTM and N-Gram Models."** This study focuses on using machine learning techniques, particularly Long Short-Term Memory (LSTM) networks and N-Gram models, to generate music automatically.

## Abstract
This project explores the realm of automated music composition using AI, demonstrating how LSTM networks and N-Gram models can be applied to create music based on a dataset of MIDI files. The focus is on generating symbolic music (MIDI) by modeling notes and chords, aiming to balance accurate note prediction with the generation of diverse and creative sequences.

## Methodology

### Data
- **Dataset**: We used a dataset of 92 MIDI recordings from the Classical Piano Dataset, primarily featuring compositions from the **Final Fantasy** soundtracks.

### Models
- **N-Gram Models**: We implemented Trigram, Fifty-Gram, and Hundred-Gram N-Gram models to analyze the musical sequences. 
- **LSTM Model**: A multi-layer LSTM network was developed to learn long-term dependencies in music, demonstrating superior pattern generation compared to the N-Gram models.

### Evaluation Metrics
- **Perplexity**: Used to evaluate the performance of N-Gram models, with lower perplexity indicating better predictive accuracy.
- **Pitch-Time Graphs**: Visualized the patterns generated by the models, comparing their ability to maintain melodic flow and coherence.

## Key Results
- The **LSTM model** achieved superior results in generating complex and diverse musical sequences compared to the N-Gram models.
- The **Trigram Model** achieved the lowest perplexity (0.26), but it produced repetitive patterns. The **Fifty-Gram** and **Hundred-Gram** models had higher perplexities (0.73 and 0.81, respectively) but improved in generating more varied sequences.

## Project Structure
```plaintext
- /data: Contains the MIDI recordings used for training the models.
- /src: Includes Python scripts for model training, evaluation, and MIDI file generation.
- /output_midi: Generated MIDI files from the models.
```
## Results
Generated MIDI files and pitch-time graphs are

1. TRIGRAM
![image](https://github.com/Pranay36/Music-Generation---NLP-Project/blob/main/assets/Trigram.png)
<Br/>
<Br/>
<Br/>

2. FIFTYGRAM
![image](https://github.com/Pranay36/Music-Generation---NLP-Project/blob/main/assets/Fiftygram.png)
<Br/>
<Br/>
<Br/>


3. HUNDREDGRAM
![image](https://github.com/Pranay36/Music-Generation---NLP-Project/blob/main/assets/hundredgram.png)
<Br/>
<Br/>
<Br/>


4. LSTM
![image](https://github.com/Pranay36/Music-Generation---NLP-Project/blob/main/assets/LSTM.png)
<Br/>
<Br/>
<Br/>


