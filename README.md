# First step

We are using the tflite-micro repository at it latest verion, at 1/12/2025 (EU date). At the first page of that repo, it includes the boards that have examples available. The STM32 boards are not on that list, so we have to move to the [New Platform Support](https://github.com/tensorflow/tflite-micro/blob/main/tensorflow/lite/micro/docs/new_platform_support.md). 

Inside of this folder, it tells us to execute the following commands: 

```bash
python3 tensorflow/lite/micro/tools/project_generation/create_tflm_tree.py \
  -e hello_world \
  -e micro_speech \
  -e person_detection \
  /tmp/tflm-tree
```

This results in the creation of this folder, which we can find with:

```bash
xdg-open /tmp/tflm-tree
```


