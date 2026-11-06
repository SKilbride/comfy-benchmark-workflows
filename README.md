# Comfy benchmark workflows

This repository contains ComfyUI editor workflows used by Comfy Desktop benchmark automation.

Each folder groups a benchmark family. Extended workflows contain `extra.workflow_model_studio` metadata and configuration tags; the benchmark runner converts a selected tag to a standard workflow before execution. Keep workflow filenames unique across folders because ComfyUI API exports use their basenames.

Workflow JSON files may reference model and input downloads. Model weights and generated results do not belong in this repository.
