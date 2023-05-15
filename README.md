# French voice input/ouput extensions for oobabooga text-generation-webui 
OobaBooga text-generation-webui with modified Silero TTS and whisper STT extensions for french voice input/ouput for french model like Vigogne (https://huggingface.co/cmh/vigogne-13b-4bit-128g)

## Features
- silero_tts_fr modified script for french voice output (you have to manually download the french model).
- whisper_stt_fr modified script for french voice input (it will auto download medium model, because base model could be not enought).
- whisper_stt_lite modified script for french voice input if you don't have enough vram (it will auto download base model,  bad quality recognition but it's working).

# How to Use
1. Drop folders into your oobabooga extensions folder
2. Make sure you're in the `text-generation-webui` directory within the `textgen` conda environment, run the following commands to install dependencies :
```bash
pip install -r extensions/silero_tts_fr/requirements.txt
pip install -r extensions/whisper_stt_fr/requirements.txt
```
3. For Silero you need to download the french model 
https://models.silero.ai/models/tts/fr/v3_fr.pt
and drop it into `\home\"user"\.cache\torch\hub\snakers4_silero-models_master\`
4. Add flags `--silero_tts_fr` and `--whisper_stt_fr` or `--whisper_stt_lite` when starting Oobabooga like other extensions.

