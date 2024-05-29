# COL788-Project-G7

## Current Status:
We are not able to build yet. We have included all the paths in the project. We have to remove reference to Cortex Math library to build. 

## Steps we followed:
1. Installation of IDE
2. Running Blink demo on board (successful)
3. Followed steps to train, quantize, evaulate and deploy car horn detection model
  - https://github.com/STMicroelectronics/stm32ai-modelzoo/tree/main/audio_event_detection/scripts/training (training)
  - https://github.com/STMicroelectronics/stm32ai-modelzoo/tree/main/audio_event_detection/scripts/evaluate (evaluation)
  - https://github.com/STMicroelectronics/stm32ai-modelzoo/tree/main/audio_event_detection/scripts/deployment (deployment)
4. Successfully built qunatized ML model.
5. Moving to Deployment - could not build the project, and had to remove the paths
  - Updated rashu paths, according to our PC
  - Had to include more paths in Optimized model build
  - Had to remove reference to arm-cortex-m4 library
  - Had to add files from new build sent by TA to the old (Optimized) build as they were missing
  - Very long task - took many hours

## Files/Folders Added
Optimized_Transformer_code-master (contains our project with updated paths)
stm32ai-modelzoo (contains our best model and config.yaml files)
