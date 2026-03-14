Latest Logs From Latest Build
==============================

Generated On: 2026-03-14 16:07:37 UTC

These are the latest logs generated from your latest build.  

.. tip:: 
   Complete logs from all builds can be found `here on GitHub <https://github.com/KavyaSJ/raspberrypitss/blob/main/tml-airflow/logs/logs.txt>`_

.. code-block:: 
  :linenos:

  [INFO 2026-03-14_15:56:11] STEP 1: completed - TML system parameters successfully gathered

  [INFO 2026-03-14_15:56:19] STEP 2: Create topics started

  [INFO 2026-03-14_15:56:51] STEP 2: Completed

  [INFO 2026-03-14_15:57:04] STEP 3: producing data started

  [INFO 2026-03-14_15:57:12] STEP 4: Preprocessing started

  [INFO 2026-03-14_15:57:14] STEP 4: Preprocessing started

  [INFO 2026-03-14_15:57:15] STEP 3: reading local file..successfully

  [INFO 2026-03-14_15:57:21] STEP 5: Machine learning started

  [INFO 2026-03-14_15:57:27] STEP 6: Predictions started

  [INFO 2026-03-14_15:57:32] STEP 7: Visualization started

  [INFO 2026-03-14_15:57:38] STEP 7: /Viperviz/viperviz-linux-amd64 0.0.0.0 9005

  [INFO 2026-03-14_15:57:49] STEP 9b: Starting ollama server

  [INFO 2026-03-14_15:57:59] STEP 9b: Ollama container.  Here is the run command: docker run -d -p 11434:11434 --net=host --gpus all -v /var/run/docker.sock:/var/run/docker.sock:z -v /mnt/c/maads/tml-airflow/rawdata/ollama:/root/.ollama:z --env OLLAMA_LOAD_TIMEOUT=30m0s --env PORT=11434 --env TSS=1 --env GPU=1 --env COLLECTION=tml-llm-model-v2 --env WEB_CONCURRENCY=2 --env CUDA_VISIBLE_DEVICES=0 --env TOKENIZERS_PARALLELISM=false --env temperature=0.1 --env LLAMAMODEL="phi3:3.8b && phi3:3.8b && llama3.2:3b" --env mainembedding="nomic-embed-text" --env OLLAMASERVERPORT="http://127.0.0.1:11434" maadsdocker/tml-privategpt-with-cpu-amd64-llama3-tools, v=125

  [INFO 2026-03-14_15:57:59] STEP 9b: Success starting Agentic AI.  Here is the run command: docker run -d -p 11434:11434 --net=host --gpus all -v /var/run/docker.sock:/var/run/docker.sock:z -v /mnt/c/maads/tml-airflow/rawdata/ollama:/root/.ollama:z --env OLLAMA_LOAD_TIMEOUT=30m0s --env PORT=11434 --env TSS=1 --env GPU=1 --env COLLECTION=tml-llm-model-v2 --env WEB_CONCURRENCY=2 --env CUDA_VISIBLE_DEVICES=0 --env TOKENIZERS_PARALLELISM=false --env temperature=0.1 --env LLAMAMODEL="phi3:3.8b && phi3:3.8b && llama3.2:3b" --env mainembedding="nomic-embed-text" --env OLLAMASERVERPORT="http://127.0.0.1:11434" maadsdocker/tml-privategpt-with-cpu-amd64-llama3-tools

  [INFO 2026-03-14_15:58:06] STEP 8: Starting docker push for: kavyasj/tml-multi-agenticai-iot-3f10-ml_agenticai-cc4a-amd64

  [WARN 2026-03-14_16:07:04] STEP 8: There seems to be an issue optimizing the container.  Here is the commit command: docker commit e783468ab538 kavyasj/tml-multi-agenticai-iot-3f10-ml_agenticai-cc4a-amd64 - message=0.  Container may NOT pushed.

  [INFO 2026-03-14_16:07:37] STEP 10: Started to build the documentation

  [INFO 2026-03-14_16:07:38] STEP 10: Documentation successfully built on GitHub..Readthedocs build in process and should complete in few seconds


