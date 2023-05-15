# French voice input/ouput extensions for oobabooga text-generation-webui 
OobaBooga text-generation-webui with modified Silero TTS and whisper STT extensions for french voice input/ouput

## Features
- Memories are fetched using a semantic search, which understands the "actual meaning" of the messages.
- Separate memories for different characters, all handled under the hood for you. (legacy users see [character namespace migration instructions](#character-namespace-migration-instructions).)
- Ability to load an arbitrary number of "memories".
- Other configuration options, see below.

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
