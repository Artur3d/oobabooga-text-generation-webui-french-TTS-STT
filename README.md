# French voice input/ouput extensions for oobabooga text-generation-webui 
OobaBooga text-generation-webui with modified Silero TTS and whisper STT extensions for french voice input/ouput

# How to Use
1. Drop folders into your oobabooga extensions folder
2. Make sure you're in the `text-generation-webui` directory
```bash
pip install -r extensions/silero_tts_fr/requirements.txt
pip install -r extensions/whisper_stt_fr/requirements.txt
```
3. For Silero you need to donwload the french model 
https://models.silero.ai/models/tts/fr/v3_fr.pt
to \home\"user"\.cache\torch\hub\snakers4_silero-models_master\
