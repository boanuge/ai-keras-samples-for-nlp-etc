================================================================================
(base) USER@192-168-0-1:~/AI_test$ conda create -n textgen2 python=3.10.9
================================================================================

Collecting package metadata (current_repodata.json): done
Solving environment: failed with repodata from current_repodata.json, will retry with next repodata source.
Collecting package metadata (repodata.json): done
Solving environment: done


==> WARNING: A newer version of conda exists. <==
  current version: 4.10.3
  latest version: 23.9.0

Please update conda by running

    $ conda update -n base -c defaults conda



## Package Plan ##

  environment location: /home/gbike/anaconda3/envs/textgen2

  added / updated specs:
    - python=3.10.9


The following packages will be downloaded:

    package                    |            build
    ---------------------------|-----------------
    _openmp_mutex-5.1          |            1_gnu          21 KB
    ca-certificates-2023.08.22 |       h06a4308_0         123 KB
    ld_impl_linux-64-2.38      |       h1181459_1         654 KB
    libffi-3.4.4               |       h6a678d5_0         142 KB
    libgcc-ng-11.2.0           |       h1234567_1         5.3 MB
    libgomp-11.2.0             |       h1234567_1         474 KB
    libstdcxx-ng-11.2.0        |       h1234567_1         4.7 MB
    libuuid-1.41.5             |       h5eee18b_0          27 KB
    ncurses-6.4                |       h6a678d5_0         914 KB
    openssl-1.1.1w             |       h7f8727e_0         3.7 MB
    pip-23.3                   |  py310h06a4308_0         2.7 MB
    python-3.10.9              |       h7a1cb2a_2        26.8 MB
    readline-8.2               |       h5eee18b_0         357 KB
    setuptools-68.0.0          |  py310h06a4308_0         936 KB
    sqlite-3.41.2              |       h5eee18b_0         1.2 MB
    tk-8.6.12                  |       h1ccaba5_0         3.0 MB
    tzdata-2023c               |       h04d1e81_0         116 KB
    wheel-0.41.2               |  py310h06a4308_0         109 KB
    xz-5.4.2                   |       h5eee18b_0         642 KB
    zlib-1.2.13                |       h5eee18b_0         103 KB
    ------------------------------------------------------------
                                           Total:        52.0 MB

The following NEW packages will be INSTALLED:

  _libgcc_mutex      pkgs/main/linux-64::_libgcc_mutex-0.1-main
  _openmp_mutex      pkgs/main/linux-64::_openmp_mutex-5.1-1_gnu
  bzip2              pkgs/main/linux-64::bzip2-1.0.8-h7b6447c_0
  ca-certificates    pkgs/main/linux-64::ca-certificates-2023.08.22-h06a4308_0
  ld_impl_linux-64   pkgs/main/linux-64::ld_impl_linux-64-2.38-h1181459_1
  libffi             pkgs/main/linux-64::libffi-3.4.4-h6a678d5_0
  libgcc-ng          pkgs/main/linux-64::libgcc-ng-11.2.0-h1234567_1
  libgomp            pkgs/main/linux-64::libgomp-11.2.0-h1234567_1
  libstdcxx-ng       pkgs/main/linux-64::libstdcxx-ng-11.2.0-h1234567_1
  libuuid            pkgs/main/linux-64::libuuid-1.41.5-h5eee18b_0
  ncurses            pkgs/main/linux-64::ncurses-6.4-h6a678d5_0
  openssl            pkgs/main/linux-64::openssl-1.1.1w-h7f8727e_0
  pip                pkgs/main/linux-64::pip-23.3-py310h06a4308_0
  python             pkgs/main/linux-64::python-3.10.9-h7a1cb2a_2
  readline           pkgs/main/linux-64::readline-8.2-h5eee18b_0
  setuptools         pkgs/main/linux-64::setuptools-68.0.0-py310h06a4308_0
  sqlite             pkgs/main/linux-64::sqlite-3.41.2-h5eee18b_0
  tk                 pkgs/main/linux-64::tk-8.6.12-h1ccaba5_0
  tzdata             pkgs/main/noarch::tzdata-2023c-h04d1e81_0
  wheel              pkgs/main/linux-64::wheel-0.41.2-py310h06a4308_0
  xz                 pkgs/main/linux-64::xz-5.4.2-h5eee18b_0
  zlib               pkgs/main/linux-64::zlib-1.2.13-h5eee18b_0


Proceed ([y]/n)? y


Downloading and Extracting Packages
xz-5.4.2             | 642 KB    | ################################################################################################################################################## | 100%
ca-certificates-2023 | 123 KB    | ################################################################################################################################################## | 100%
openssl-1.1.1w       | 3.7 MB    | ################################################################################################################################################## | 100%
libffi-3.4.4         | 142 KB    | ################################################################################################################################################## | 100%
wheel-0.41.2         | 109 KB    | ################################################################################################################################################## | 100%
python-3.10.9        | 26.8 MB   | ################################################################################################################################################## | 100%
pip-23.3             | 2.7 MB    | ################################################################################################################################################## | 100%
sqlite-3.41.2        | 1.2 MB    | ################################################################################################################################################## | 100%
zlib-1.2.13          | 103 KB    | ################################################################################################################################################## | 100%
tzdata-2023c         | 116 KB    | ################################################################################################################################################## | 100%
ncurses-6.4          | 914 KB    | ################################################################################################################################################## | 100%
libgcc-ng-11.2.0     | 5.3 MB    | ################################################################################################################################################## | 100%
ld_impl_linux-64-2.3 | 654 KB    | ################################################################################################################################################## | 100%
libstdcxx-ng-11.2.0  | 4.7 MB    | ################################################################################################################################################## | 100%
tk-8.6.12            | 3.0 MB    | ################################################################################################################################################## | 100%
setuptools-68.0.0    | 936 KB    | ################################################################################################################################################## | 100%
libuuid-1.41.5       | 27 KB     | ################################################################################################################################################## | 100%
readline-8.2         | 357 KB    | ################################################################################################################################################## | 100%
libgomp-11.2.0       | 474 KB    | ################################################################################################################################################## | 100%
_openmp_mutex-5.1    | 21 KB     | ################################################################################################################################################## | 100%
Preparing transaction: done
Verifying transaction: done
Executing transaction: done
#
# To activate this environment, use
#
#     $ conda activate textgen2
#
# To deactivate an active environment, use
#
#     $ conda deactivate

================================================================================
(base) USER@192-168-0-1:~/AI_test$ conda activate textgen2
================================================================================
(textgen2) USER@192-168-0-1:~/AI_test$ git clone https://github.com/oobabooga/text-generation-webui
================================================================================

Cloning into 'text-generation-webui'...
remote: Enumerating objects: 13325, done.
remote: Counting objects: 100% (2485/2485), done.
remote: Compressing objects: 100% (327/327), done.
remote: Total 13325 (delta 2224), reused 2320 (delta 2158), pack-reused 10840
Receiving objects: 100% (13325/13325), 24.14 MiB | 18.26 MiB/s, done.
Resolving deltas: 100% (9109/9109), done.

================================================================================
(textgen2) USER@192-168-0-1:~/AI_test$ cd text-generation-webui/
================================================================================
(textgen2) USER@192-168-0-1:~/AI_test/text-generation-webui$ pip install -r requirements.txt
================================================================================

Ignoring exllamav2: markers 'platform_system != "Darwin" and platform_machine != "x86_64"' don't match your environment
Collecting git+https://github.com/oobabooga/torch-grammar.git (from -r requirements.txt (line 23))
  Cloning https://github.com/oobabooga/torch-grammar.git to /tmp/pip-req-build-ocku7khc
  Running command git clone --filter=blob:none --quiet https://github.com/oobabooga/torch-grammar.git /tmp/pip-req-build-ocku7khc
  Resolved https://github.com/oobabooga/torch-grammar.git to commit 82850b5383a629f3b0fa1fba7d8f2aba3185ddb2
  Installing build dependencies ... done
  Getting requirements to build wheel ... done
  Preparing metadata (pyproject.toml) ... done
Ignoring bitsandbytes: markers 'platform_system == "Windows"' don't match your environment
Ignoring llama-cpp-python: markers 'platform_system == "Linux" and platform_machine == "x86_64" and python_version == "3.11"' don't match your environment
Collecting llama-cpp-python==0.2.11 (from -r requirements.txt (line 31))
  Downloading https://github.com/abetlen/llama-cpp-python/releases/download/v0.2.11/llama_cpp_python-0.2.11-cp310-cp310-manylinux_2_17_x86_64.manylinux2014_x86_64.whl (1.0 MB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 1.0/1.0 MB 25.3 MB/s eta 0:00:00
Ignoring llama-cpp-python: markers 'platform_system == "Linux" and platform_machine == "x86_64" and python_version == "3.9"' don't match your environment
Ignoring llama-cpp-python: markers 'platform_system == "Linux" and platform_machine == "x86_64" and python_version == "3.8"' don't match your environment
Ignoring llama-cpp-python: markers 'platform_system == "Windows" and python_version == "3.11"' don't match your environment
Ignoring llama-cpp-python: markers 'platform_system == "Windows" and python_version == "3.10"' don't match your environment
Ignoring llama-cpp-python: markers 'platform_system == "Windows" and python_version == "3.9"' don't match your environment
Ignoring llama-cpp-python: markers 'platform_system == "Windows" and python_version == "3.8"' don't match your environment
Ignoring auto-gptq: markers 'platform_system == "Windows" and python_version == "3.11"' don't match your environment
Ignoring auto-gptq: markers 'platform_system == "Windows" and python_version == "3.10"' don't match your environment
Ignoring auto-gptq: markers 'platform_system == "Windows" and python_version == "3.9"' don't match your environment
Ignoring auto-gptq: markers 'platform_system == "Windows" and python_version == "3.8"' don't match your environment
Ignoring auto-gptq: markers 'platform_system == "Linux" and platform_machine == "x86_64" and python_version == "3.11"' don't match your environment
Collecting auto-gptq==0.4.2+cu121 (from -r requirements.txt (line 45))
  Downloading https://github.com/jllllll/AutoGPTQ/releases/download/v0.4.2/auto_gptq-0.4.2+cu121-cp310-cp310-linux_x86_64.whl (1.9 MB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 1.9/1.9 MB 16.3 MB/s eta 0:00:00
Ignoring auto-gptq: markers 'platform_system == "Linux" and platform_machine == "x86_64" and python_version == "3.9"' don't match your environment
Ignoring auto-gptq: markers 'platform_system == "Linux" and platform_machine == "x86_64" and python_version == "3.8"' don't match your environment
Ignoring exllama: markers 'platform_system == "Windows" and python_version == "3.11"' don't match your environment
Ignoring exllama: markers 'platform_system == "Windows" and python_version == "3.10"' don't match your environment
Ignoring exllama: markers 'platform_system == "Windows" and python_version == "3.9"' don't match your environment
Ignoring exllama: markers 'platform_system == "Windows" and python_version == "3.8"' don't match your environment
Ignoring exllama: markers 'platform_system == "Linux" and platform_machine == "x86_64" and python_version == "3.11"' don't match your environment
Collecting exllama==0.0.18+cu121 (from -r requirements.txt (line 53))
  Downloading https://github.com/jllllll/exllama/releases/download/0.0.18/exllama-0.0.18+cu121-cp310-cp310-linux_x86_64.whl (434 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 434.6/434.6 kB 29.3 MB/s eta 0:00:00
Ignoring exllama: markers 'platform_system == "Linux" and platform_machine == "x86_64" and python_version == "3.9"' don't match your environment
Ignoring exllama: markers 'platform_system == "Linux" and platform_machine == "x86_64" and python_version == "3.8"' don't match your environment
Ignoring exllamav2: markers 'platform_system == "Windows" and python_version == "3.11"' don't match your environment
Ignoring exllamav2: markers 'platform_system == "Windows" and python_version == "3.10"' don't match your environment
Ignoring exllamav2: markers 'platform_system == "Windows" and python_version == "3.9"' don't match your environment
Ignoring exllamav2: markers 'platform_system == "Windows" and python_version == "3.8"' don't match your environment
Ignoring exllamav2: markers 'platform_system == "Linux" and platform_machine == "x86_64" and python_version == "3.11"' don't match your environment
Collecting exllamav2==0.0.6+cu121 (from -r requirements.txt (line 61))
  Downloading https://github.com/turboderp/exllamav2/releases/download/v0.0.6/exllamav2-0.0.6+cu121-cp310-cp310-linux_x86_64.whl (12.3 MB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 12.3/12.3 MB 9.7 MB/s eta 0:00:00
Ignoring exllamav2: markers 'platform_system == "Linux" and platform_machine == "x86_64" and python_version == "3.9"' don't match your environment
Ignoring exllamav2: markers 'platform_system == "Linux" and platform_machine == "x86_64" and python_version == "3.8"' don't match your environment
Ignoring flash-attn: markers 'platform_system == "Windows" and python_version == "3.11"' don't match your environment
Ignoring flash-attn: markers 'platform_system == "Windows" and python_version == "3.10"' don't match your environment
Ignoring flash-attn: markers 'platform_system == "Linux" and platform_machine == "x86_64" and python_version == "3.11"' don't match your environment
Collecting flash-attn==2.3.2+cu122torch2.1cxx11abiFALSE (from -r requirements.txt (line 67))
  Downloading https://github.com/Dao-AILab/flash-attention/releases/download/v2.3.2/flash_attn-2.3.2+cu122torch2.1cxx11abiFALSE-cp310-cp310-linux_x86_64.whl (57.0 MB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 57.0/57.0 MB 45.5 MB/s eta 0:00:00
Ignoring flash-attn: markers 'platform_system == "Linux" and platform_machine == "x86_64" and python_version == "3.9"' don't match your environment
Ignoring flash-attn: markers 'platform_system == "Linux" and platform_machine == "x86_64" and python_version == "3.8"' don't match your environment
Ignoring llama-cpp-python-cuda: markers 'platform_system == "Windows" and python_version == "3.11"' don't match your environment
Ignoring llama-cpp-python-cuda: markers 'platform_system == "Windows" and python_version == "3.10"' don't match your environment
Ignoring llama-cpp-python-cuda: markers 'platform_system == "Windows" and python_version == "3.9"' don't match your environment
Ignoring llama-cpp-python-cuda: markers 'platform_system == "Windows" and python_version == "3.8"' don't match your environment
Ignoring llama-cpp-python-cuda: markers 'platform_system == "Linux" and platform_machine == "x86_64" and python_version == "3.11"' don't match your environment
Collecting llama-cpp-python-cuda==0.2.11+cu121 (from -r requirements.txt (line 75))
  Downloading https://github.com/jllllll/llama-cpp-python-cuBLAS-wheels/releases/download/textgen-webui/llama_cpp_python_cuda-0.2.11+cu121-cp310-cp310-manylinux_2_31_x86_64.whl (15.1 MB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 15.1/15.1 MB 17.2 MB/s eta 0:00:00
Ignoring llama-cpp-python-cuda: markers 'platform_system == "Linux" and platform_machine == "x86_64" and python_version == "3.9"' don't match your environment
Ignoring llama-cpp-python-cuda: markers 'platform_system == "Linux" and platform_machine == "x86_64" and python_version == "3.8"' don't match your environment
Ignoring gptq-for-llama: markers 'platform_system == "Windows" and python_version == "3.11"' don't match your environment
Ignoring gptq-for-llama: markers 'platform_system == "Windows" and python_version == "3.10"' don't match your environment
Ignoring gptq-for-llama: markers 'platform_system == "Windows" and python_version == "3.9"' don't match your environment
Ignoring gptq-for-llama: markers 'platform_system == "Windows" and python_version == "3.8"' don't match your environment
Ignoring gptq-for-llama: markers 'platform_system == "Linux" and platform_machine == "x86_64" and python_version == "3.11"' don't match your environment
Collecting gptq-for-llama==0.1.1+cu121 (from -r requirements.txt (line 83))
  Downloading https://github.com/jllllll/GPTQ-for-LLaMa-CUDA/releases/download/0.1.1/gptq_for_llama-0.1.1+cu121-cp310-cp310-linux_x86_64.whl (739 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 739.5/739.5 kB 11.6 MB/s eta 0:00:00
Ignoring gptq-for-llama: markers 'platform_system == "Linux" and platform_machine == "x86_64" and python_version == "3.9"' don't match your environment
Ignoring gptq-for-llama: markers 'platform_system == "Linux" and platform_machine == "x86_64" and python_version == "3.8"' don't match your environment
Collecting ctransformers==0.2.27+cu121 (from -r requirements.txt (line 86))
  Downloading https://github.com/jllllll/ctransformers-cuBLAS-wheels/releases/download/AVX2/ctransformers-0.2.27+cu121-py3-none-any.whl (15.5 MB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 15.5/15.5 MB 96.2 MB/s eta 0:00:00
Collecting accelerate==0.23.* (from -r requirements.txt (line 1))
  Downloading accelerate-0.23.0-py3-none-any.whl.metadata (18 kB)
Collecting colorama (from -r requirements.txt (line 2))
  Downloading colorama-0.4.6-py2.py3-none-any.whl (25 kB)
Collecting datasets (from -r requirements.txt (line 3))
  Downloading datasets-2.14.6-py3-none-any.whl.metadata (19 kB)
Collecting einops (from -r requirements.txt (line 4))
  Downloading einops-0.7.0-py3-none-any.whl.metadata (13 kB)
Collecting gradio==3.50.* (from -r requirements.txt (line 6))
  Downloading gradio-3.50.2-py3-none-any.whl.metadata (17 kB)
Collecting markdown (from -r requirements.txt (line 7))
  Downloading Markdown-3.5-py3-none-any.whl.metadata (7.1 kB)
Collecting numpy==1.24.* (from -r requirements.txt (line 8))
  Downloading numpy-1.24.4-cp310-cp310-manylinux_2_17_x86_64.manylinux2014_x86_64.whl.metadata (5.6 kB)
Collecting optimum==1.13.1 (from -r requirements.txt (line 9))
  Downloading optimum-1.13.1-py3-none-any.whl.metadata (17 kB)
Collecting pandas (from -r requirements.txt (line 10))
  Downloading pandas-2.1.1-cp310-cp310-manylinux_2_17_x86_64.manylinux2014_x86_64.whl.metadata (18 kB)
Collecting peft==0.5.* (from -r requirements.txt (line 11))
  Downloading peft-0.5.0-py3-none-any.whl.metadata (22 kB)
Collecting Pillow>=9.5.0 (from -r requirements.txt (line 12))
  Downloading Pillow-10.1.0-cp310-cp310-manylinux_2_28_x86_64.whl.metadata (9.5 kB)
Collecting pyyaml (from -r requirements.txt (line 13))
  Downloading PyYAML-6.0.1-cp310-cp310-manylinux_2_17_x86_64.manylinux2014_x86_64.whl.metadata (2.1 kB)
Collecting requests (from -r requirements.txt (line 14))
  Downloading requests-2.31.0-py3-none-any.whl.metadata (4.6 kB)
Collecting safetensors==0.4.0 (from -r requirements.txt (line 15))
  Downloading safetensors-0.4.0-cp310-cp310-manylinux_2_17_x86_64.manylinux2014_x86_64.whl.metadata (3.8 kB)
Collecting scipy (from -r requirements.txt (line 16))
  Downloading scipy-1.11.3-cp310-cp310-manylinux_2_17_x86_64.manylinux2014_x86_64.whl.metadata (60 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 60.4/60.4 kB 6.0 MB/s eta 0:00:00
Collecting sentencepiece (from -r requirements.txt (line 17))
  Downloading sentencepiece-0.1.99-cp310-cp310-manylinux_2_17_x86_64.manylinux2014_x86_64.whl (1.3 MB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 1.3/1.3 MB 64.3 MB/s eta 0:00:00
Collecting tensorboard (from -r requirements.txt (line 18))
  Downloading tensorboard-2.15.0-py3-none-any.whl.metadata (1.7 kB)
Collecting transformers==4.34.* (from -r requirements.txt (line 19))
  Downloading transformers-4.34.1-py3-none-any.whl.metadata (121 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 121.5/121.5 kB 17.5 MB/s eta 0:00:00
Collecting tqdm (from -r requirements.txt (line 20))
  Downloading tqdm-4.66.1-py3-none-any.whl.metadata (57 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 57.6/57.6 kB 8.1 MB/s eta 0:00:00
Collecting wandb (from -r requirements.txt (line 21))
  Downloading wandb-0.15.12-py3-none-any.whl.metadata (9.8 kB)
Collecting bitsandbytes==0.41.1 (from -r requirements.txt (line 26))
  Downloading bitsandbytes-0.41.1-py3-none-any.whl.metadata (9.8 kB)
Collecting autoawq==0.1.4 (from -r requirements.txt (line 87))
  Downloading autoawq-0.1.4-cp310-cp310-manylinux2014_x86_64.whl.metadata (13 kB)
Collecting packaging>=20.0 (from accelerate==0.23.*->-r requirements.txt (line 1))
  Downloading packaging-23.2-py3-none-any.whl.metadata (3.2 kB)
Collecting psutil (from accelerate==0.23.*->-r requirements.txt (line 1))
  Downloading psutil-5.9.6-cp36-abi3-manylinux_2_12_x86_64.manylinux2010_x86_64.manylinux_2_17_x86_64.manylinux2014_x86_64.whl.metadata (21 kB)
Collecting torch>=1.10.0 (from accelerate==0.23.*->-r requirements.txt (line 1))
  Downloading torch-2.1.0-cp310-cp310-manylinux1_x86_64.whl.metadata (25 kB)
Collecting huggingface-hub (from accelerate==0.23.*->-r requirements.txt (line 1))
  Downloading huggingface_hub-0.18.0-py3-none-any.whl.metadata (13 kB)
Collecting aiofiles<24.0,>=22.0 (from gradio==3.50.*->-r requirements.txt (line 6))
  Downloading aiofiles-23.2.1-py3-none-any.whl.metadata (9.7 kB)
Collecting altair<6.0,>=4.2.0 (from gradio==3.50.*->-r requirements.txt (line 6))
  Downloading altair-5.1.2-py3-none-any.whl.metadata (8.6 kB)
Collecting fastapi (from gradio==3.50.*->-r requirements.txt (line 6))
  Downloading fastapi-0.104.0-py3-none-any.whl.metadata (24 kB)
Collecting ffmpy (from gradio==3.50.*->-r requirements.txt (line 6))
  Downloading ffmpy-0.3.1.tar.gz (5.5 kB)
  Preparing metadata (setup.py) ... done
Collecting gradio-client==0.6.1 (from gradio==3.50.*->-r requirements.txt (line 6))
  Downloading gradio_client-0.6.1-py3-none-any.whl.metadata (7.1 kB)
Collecting httpx (from gradio==3.50.*->-r requirements.txt (line 6))
  Downloading httpx-0.25.0-py3-none-any.whl.metadata (7.6 kB)
Collecting importlib-resources<7.0,>=1.3 (from gradio==3.50.*->-r requirements.txt (line 6))
  Downloading importlib_resources-6.1.0-py3-none-any.whl.metadata (4.1 kB)
Collecting jinja2<4.0 (from gradio==3.50.*->-r requirements.txt (line 6))
  Downloading Jinja2-3.1.2-py3-none-any.whl (133 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 133.1/133.1 kB 18.8 MB/s eta 0:00:00
Collecting markupsafe~=2.0 (from gradio==3.50.*->-r requirements.txt (line 6))
  Downloading MarkupSafe-2.1.3-cp310-cp310-manylinux_2_17_x86_64.manylinux2014_x86_64.whl.metadata (3.0 kB)
Collecting matplotlib~=3.0 (from gradio==3.50.*->-r requirements.txt (line 6))
  Downloading matplotlib-3.8.0-cp310-cp310-manylinux_2_17_x86_64.manylinux2014_x86_64.whl.metadata (5.8 kB)
Collecting orjson~=3.0 (from gradio==3.50.*->-r requirements.txt (line 6))
  Downloading orjson-3.9.9-cp310-cp310-manylinux_2_17_x86_64.manylinux2014_x86_64.whl.metadata (49 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 49.3/49.3 kB 6.6 MB/s eta 0:00:00
Collecting pydantic!=1.8,!=1.8.1,!=2.0.0,!=2.0.1,<3.0.0,>=1.7.4 (from gradio==3.50.*->-r requirements.txt (line 6))
  Downloading pydantic-2.4.2-py3-none-any.whl.metadata (158 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 158.6/158.6 kB 21.8 MB/s eta 0:00:00
Collecting pydub (from gradio==3.50.*->-r requirements.txt (line 6))
  Downloading pydub-0.25.1-py2.py3-none-any.whl (32 kB)
Collecting python-multipart (from gradio==3.50.*->-r requirements.txt (line 6))
  Downloading python_multipart-0.0.6-py3-none-any.whl (45 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 45.7/45.7 kB 6.2 MB/s eta 0:00:00
Collecting semantic-version~=2.0 (from gradio==3.50.*->-r requirements.txt (line 6))
  Downloading semantic_version-2.10.0-py2.py3-none-any.whl (15 kB)
Collecting typing-extensions~=4.0 (from gradio==3.50.*->-r requirements.txt (line 6))
  Downloading typing_extensions-4.8.0-py3-none-any.whl.metadata (3.0 kB)
Collecting uvicorn>=0.14.0 (from gradio==3.50.*->-r requirements.txt (line 6))
  Downloading uvicorn-0.23.2-py3-none-any.whl.metadata (6.2 kB)
Collecting websockets<12.0,>=10.0 (from gradio==3.50.*->-r requirements.txt (line 6))
  Downloading websockets-11.0.3-cp310-cp310-manylinux_2_5_x86_64.manylinux1_x86_64.manylinux_2_17_x86_64.manylinux2014_x86_64.whl (129 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 129.9/129.9 kB 17.0 MB/s eta 0:00:00
Collecting coloredlogs (from optimum==1.13.1->-r requirements.txt (line 9))
  Downloading coloredlogs-15.0.1-py2.py3-none-any.whl (46 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 46.0/46.0 kB 6.2 MB/s eta 0:00:00
Collecting sympy (from optimum==1.13.1->-r requirements.txt (line 9))
  Downloading sympy-1.12-py3-none-any.whl (5.7 MB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 5.7/5.7 MB 115.1 MB/s eta 0:00:00
Collecting filelock (from transformers==4.34.*->-r requirements.txt (line 19))
  Downloading filelock-3.12.4-py3-none-any.whl.metadata (2.8 kB)
Collecting regex!=2019.12.17 (from transformers==4.34.*->-r requirements.txt (line 19))
  Downloading regex-2023.10.3-cp310-cp310-manylinux_2_17_x86_64.manylinux2014_x86_64.whl.metadata (40 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 40.9/40.9 kB 4.9 MB/s eta 0:00:00
Collecting tokenizers<0.15,>=0.14 (from transformers==4.34.*->-r requirements.txt (line 19))
  Downloading tokenizers-0.14.1-cp310-cp310-manylinux_2_17_x86_64.manylinux2014_x86_64.whl.metadata (6.7 kB)
Collecting lm-eval (from autoawq==0.1.4->-r requirements.txt (line 87))
  Downloading lm_eval-0.3.0-py3-none-any.whl (178 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 178.7/178.7 kB 24.8 MB/s eta 0:00:00
Collecting texttable (from autoawq==0.1.4->-r requirements.txt (line 87))
  Downloading texttable-1.7.0-py2.py3-none-any.whl.metadata (9.8 kB)
Collecting toml (from autoawq==0.1.4->-r requirements.txt (line 87))
  Downloading toml-0.10.2-py2.py3-none-any.whl (16 kB)
Collecting attributedict (from autoawq==0.1.4->-r requirements.txt (line 87))
  Downloading attributedict-0.3.0-py3-none-any.whl (14 kB)
Collecting protobuf (from autoawq==0.1.4->-r requirements.txt (line 87))
  Downloading protobuf-4.24.4-cp37-abi3-manylinux2014_x86_64.whl.metadata (540 bytes)
Collecting torchvision (from autoawq==0.1.4->-r requirements.txt (line 87))
  Downloading torchvision-0.16.0-cp310-cp310-manylinux1_x86_64.whl.metadata (6.6 kB)
Collecting tabulate (from autoawq==0.1.4->-r requirements.txt (line 87))
  Downloading tabulate-0.9.0-py3-none-any.whl (35 kB)
Collecting fsspec (from gradio-client==0.6.1->gradio==3.50.*->-r requirements.txt (line 6))
  Downloading fsspec-2023.10.0-py3-none-any.whl.metadata (6.8 kB)
Collecting pyarrow>=8.0.0 (from datasets->-r requirements.txt (line 3))
  Downloading pyarrow-13.0.0-cp310-cp310-manylinux_2_28_x86_64.whl.metadata (3.0 kB)
Collecting dill<0.3.8,>=0.3.0 (from datasets->-r requirements.txt (line 3))
  Downloading dill-0.3.7-py3-none-any.whl.metadata (9.9 kB)
Collecting xxhash (from datasets->-r requirements.txt (line 3))
  Downloading xxhash-3.4.1-cp310-cp310-manylinux_2_17_x86_64.manylinux2014_x86_64.whl.metadata (12 kB)
Collecting multiprocess (from datasets->-r requirements.txt (line 3))
  Downloading multiprocess-0.70.15-py310-none-any.whl.metadata (7.2 kB)
Collecting aiohttp (from datasets->-r requirements.txt (line 3))
  Downloading aiohttp-3.8.6-cp310-cp310-manylinux_2_17_x86_64.manylinux2014_x86_64.whl.metadata (7.7 kB)
Collecting python-dateutil>=2.8.2 (from pandas->-r requirements.txt (line 10))
  Downloading python_dateutil-2.8.2-py2.py3-none-any.whl (247 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 247.7/247.7 kB 31.5 MB/s eta 0:00:00
Collecting pytz>=2020.1 (from pandas->-r requirements.txt (line 10))
  Downloading pytz-2023.3.post1-py2.py3-none-any.whl.metadata (22 kB)
Collecting tzdata>=2022.1 (from pandas->-r requirements.txt (line 10))
  Downloading tzdata-2023.3-py2.py3-none-any.whl (341 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 341.8/341.8 kB 38.7 MB/s eta 0:00:00
Collecting charset-normalizer<4,>=2 (from requests->-r requirements.txt (line 14))
  Downloading charset_normalizer-3.3.1-cp310-cp310-manylinux_2_17_x86_64.manylinux2014_x86_64.whl.metadata (33 kB)
Collecting idna<4,>=2.5 (from requests->-r requirements.txt (line 14))
  Downloading idna-3.4-py3-none-any.whl (61 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 61.5/61.5 kB 9.1 MB/s eta 0:00:00
Collecting urllib3<3,>=1.21.1 (from requests->-r requirements.txt (line 14))
  Downloading urllib3-2.0.7-py3-none-any.whl.metadata (6.6 kB)
Collecting certifi>=2017.4.17 (from requests->-r requirements.txt (line 14))
  Downloading certifi-2023.7.22-py3-none-any.whl.metadata (2.2 kB)
Collecting absl-py>=0.4 (from tensorboard->-r requirements.txt (line 18))
  Downloading absl_py-2.0.0-py3-none-any.whl.metadata (2.3 kB)
Collecting grpcio>=1.48.2 (from tensorboard->-r requirements.txt (line 18))
  Downloading grpcio-1.59.0-cp310-cp310-manylinux_2_17_x86_64.manylinux2014_x86_64.whl.metadata (4.0 kB)
Collecting google-auth<3,>=1.6.3 (from tensorboard->-r requirements.txt (line 18))
  Downloading google_auth-2.23.3-py2.py3-none-any.whl.metadata (4.2 kB)
Collecting google-auth-oauthlib<2,>=0.5 (from tensorboard->-r requirements.txt (line 18))
  Downloading google_auth_oauthlib-1.1.0-py2.py3-none-any.whl.metadata (2.7 kB)
Collecting protobuf (from autoawq==0.1.4->-r requirements.txt (line 87))
  Downloading protobuf-4.23.4-cp37-abi3-manylinux2014_x86_64.whl.metadata (540 bytes)
Requirement already satisfied: setuptools>=41.0.0 in /home/gbike/anaconda3/envs/textgen2/lib/python3.10/site-packages (from tensorboard->-r requirements.txt (line 18)) (68.0.0)
Collecting six>1.9 (from tensorboard->-r requirements.txt (line 18))
  Downloading six-1.16.0-py2.py3-none-any.whl (11 kB)
Collecting tensorboard-data-server<0.8.0,>=0.7.0 (from tensorboard->-r requirements.txt (line 18))
  Downloading tensorboard_data_server-0.7.2-py3-none-manylinux_2_31_x86_64.whl.metadata (1.1 kB)
Collecting werkzeug>=1.0.1 (from tensorboard->-r requirements.txt (line 18))
  Downloading werkzeug-3.0.0-py3-none-any.whl.metadata (4.1 kB)
Collecting Click!=8.0.0,>=7.1 (from wandb->-r requirements.txt (line 21))
  Downloading click-8.1.7-py3-none-any.whl.metadata (3.0 kB)
Collecting GitPython!=3.1.29,>=1.0.0 (from wandb->-r requirements.txt (line 21))
  Downloading GitPython-3.1.40-py3-none-any.whl.metadata (12 kB)
Collecting sentry-sdk>=1.0.0 (from wandb->-r requirements.txt (line 21))
  Downloading sentry_sdk-1.32.0-py2.py3-none-any.whl.metadata (9.8 kB)
Collecting docker-pycreds>=0.4.0 (from wandb->-r requirements.txt (line 21))
  Downloading docker_pycreds-0.4.0-py2.py3-none-any.whl (9.0 kB)
Collecting pathtools (from wandb->-r requirements.txt (line 21))
  Downloading pathtools-0.1.2.tar.gz (11 kB)
  Preparing metadata (setup.py) ... done
Collecting setproctitle (from wandb->-r requirements.txt (line 21))
  Downloading setproctitle-1.3.3-cp310-cp310-manylinux_2_5_x86_64.manylinux1_x86_64.manylinux_2_17_x86_64.manylinux2014_x86_64.whl.metadata (9.9 kB)
Collecting appdirs>=1.4.3 (from wandb->-r requirements.txt (line 21))
  Downloading appdirs-1.4.4-py2.py3-none-any.whl (9.6 kB)
Collecting diskcache>=5.6.1 (from llama-cpp-python==0.2.11->-r requirements.txt (line 31))
  Downloading diskcache-5.6.3-py3-none-any.whl.metadata (20 kB)
Collecting rouge (from auto-gptq==0.4.2+cu121->-r requirements.txt (line 45))
  Downloading rouge-1.0.1-py3-none-any.whl (13 kB)
Collecting ninja (from exllamav2==0.0.6+cu121->-r requirements.txt (line 61))
  Downloading ninja-1.11.1.1-py2.py3-none-manylinux1_x86_64.manylinux_2_5_x86_64.whl.metadata (5.3 kB)
Collecting fastparquet (from exllamav2==0.0.6+cu121->-r requirements.txt (line 61))
  Downloading fastparquet-2023.8.0-cp310-cp310-manylinux_2_17_x86_64.manylinux2014_x86_64.whl.metadata (4.1 kB)
Collecting pygments (from exllamav2==0.0.6+cu121->-r requirements.txt (line 61))
  Downloading Pygments-2.16.1-py3-none-any.whl.metadata (2.5 kB)
Collecting py-cpuinfo<10.0.0,>=9.0.0 (from ctransformers==0.2.27+cu121->-r requirements.txt (line 86))
  Downloading py_cpuinfo-9.0.0-py3-none-any.whl (22 kB)
Collecting jsonschema>=3.0 (from altair<6.0,>=4.2.0->gradio==3.50.*->-r requirements.txt (line 6))
  Downloading jsonschema-4.19.1-py3-none-any.whl.metadata (7.9 kB)
Collecting toolz (from altair<6.0,>=4.2.0->gradio==3.50.*->-r requirements.txt (line 6))
  Downloading toolz-0.12.0-py3-none-any.whl (55 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 55.8/55.8 kB 8.2 MB/s eta 0:00:00
Collecting attrs>=17.3.0 (from aiohttp->datasets->-r requirements.txt (line 3))
  Downloading attrs-23.1.0-py3-none-any.whl (61 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 61.2/61.2 kB 8.3 MB/s eta 0:00:00
Collecting multidict<7.0,>=4.5 (from aiohttp->datasets->-r requirements.txt (line 3))
  Downloading multidict-6.0.4-cp310-cp310-manylinux_2_17_x86_64.manylinux2014_x86_64.whl (114 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 114.5/114.5 kB 17.5 MB/s eta 0:00:00
Collecting async-timeout<5.0,>=4.0.0a3 (from aiohttp->datasets->-r requirements.txt (line 3))
  Downloading async_timeout-4.0.3-py3-none-any.whl.metadata (4.2 kB)
Collecting yarl<2.0,>=1.0 (from aiohttp->datasets->-r requirements.txt (line 3))
  Downloading yarl-1.9.2-cp310-cp310-manylinux_2_17_x86_64.manylinux2014_x86_64.whl (268 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 268.8/268.8 kB 34.4 MB/s eta 0:00:00
Collecting frozenlist>=1.1.1 (from aiohttp->datasets->-r requirements.txt (line 3))
  Downloading frozenlist-1.4.0-cp310-cp310-manylinux_2_5_x86_64.manylinux1_x86_64.manylinux_2_17_x86_64.manylinux2014_x86_64.whl.metadata (5.2 kB)
Collecting aiosignal>=1.1.2 (from aiohttp->datasets->-r requirements.txt (line 3))
  Downloading aiosignal-1.3.1-py3-none-any.whl (7.6 kB)
Collecting gitdb<5,>=4.0.1 (from GitPython!=3.1.29,>=1.0.0->wandb->-r requirements.txt (line 21))
  Downloading gitdb-4.0.11-py3-none-any.whl.metadata (1.2 kB)
Collecting cachetools<6.0,>=2.0.0 (from google-auth<3,>=1.6.3->tensorboard->-r requirements.txt (line 18))
  Downloading cachetools-5.3.1-py3-none-any.whl.metadata (5.2 kB)
Collecting pyasn1-modules>=0.2.1 (from google-auth<3,>=1.6.3->tensorboard->-r requirements.txt (line 18))
  Downloading pyasn1_modules-0.3.0-py2.py3-none-any.whl (181 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 181.3/181.3 kB 25.5 MB/s eta 0:00:00
Collecting rsa<5,>=3.1.4 (from google-auth<3,>=1.6.3->tensorboard->-r requirements.txt (line 18))
  Downloading rsa-4.9-py3-none-any.whl (34 kB)
Collecting requests-oauthlib>=0.7.0 (from google-auth-oauthlib<2,>=0.5->tensorboard->-r requirements.txt (line 18))
  Downloading requests_oauthlib-1.3.1-py2.py3-none-any.whl (23 kB)
Collecting contourpy>=1.0.1 (from matplotlib~=3.0->gradio==3.50.*->-r requirements.txt (line 6))
  Downloading contourpy-1.1.1-cp310-cp310-manylinux_2_17_x86_64.manylinux2014_x86_64.whl.metadata (5.9 kB)
Collecting cycler>=0.10 (from matplotlib~=3.0->gradio==3.50.*->-r requirements.txt (line 6))
  Downloading cycler-0.12.1-py3-none-any.whl.metadata (3.8 kB)
Collecting fonttools>=4.22.0 (from matplotlib~=3.0->gradio==3.50.*->-r requirements.txt (line 6))
  Downloading fonttools-4.43.1-cp310-cp310-manylinux_2_17_x86_64.manylinux2014_x86_64.whl.metadata (152 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 152.4/152.4 kB 22.6 MB/s eta 0:00:00
Collecting kiwisolver>=1.0.1 (from matplotlib~=3.0->gradio==3.50.*->-r requirements.txt (line 6))
  Downloading kiwisolver-1.4.5-cp310-cp310-manylinux_2_12_x86_64.manylinux2010_x86_64.whl.metadata (6.4 kB)
Collecting pyparsing>=2.3.1 (from matplotlib~=3.0->gradio==3.50.*->-r requirements.txt (line 6))
  Downloading pyparsing-3.1.1-py3-none-any.whl.metadata (5.1 kB)
Collecting annotated-types>=0.4.0 (from pydantic!=1.8,!=1.8.1,!=2.0.0,!=2.0.1,<3.0.0,>=1.7.4->gradio==3.50.*->-r requirements.txt (line 6))
  Downloading annotated_types-0.6.0-py3-none-any.whl.metadata (12 kB)
Collecting pydantic-core==2.10.1 (from pydantic!=1.8,!=1.8.1,!=2.0.0,!=2.0.1,<3.0.0,>=1.7.4->gradio==3.50.*->-r requirements.txt (line 6))
  Downloading pydantic_core-2.10.1-cp310-cp310-manylinux_2_17_x86_64.manylinux2014_x86_64.whl.metadata (6.5 kB)
Collecting huggingface-hub (from accelerate==0.23.*->-r requirements.txt (line 1))
  Downloading huggingface_hub-0.17.3-py3-none-any.whl.metadata (13 kB)
Collecting networkx (from torch>=1.10.0->accelerate==0.23.*->-r requirements.txt (line 1))
  Downloading networkx-3.2-py3-none-any.whl.metadata (5.2 kB)
Collecting nvidia-cuda-nvrtc-cu12==12.1.105 (from torch>=1.10.0->accelerate==0.23.*->-r requirements.txt (line 1))
  Downloading nvidia_cuda_nvrtc_cu12-12.1.105-py3-none-manylinux1_x86_64.whl (23.7 MB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 23.7/23.7 MB 75.9 MB/s eta 0:00:00
Collecting nvidia-cuda-runtime-cu12==12.1.105 (from torch>=1.10.0->accelerate==0.23.*->-r requirements.txt (line 1))
  Downloading nvidia_cuda_runtime_cu12-12.1.105-py3-none-manylinux1_x86_64.whl (823 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 823.6/823.6 kB 73.2 MB/s eta 0:00:00
Collecting nvidia-cuda-cupti-cu12==12.1.105 (from torch>=1.10.0->accelerate==0.23.*->-r requirements.txt (line 1))
  Downloading nvidia_cuda_cupti_cu12-12.1.105-py3-none-manylinux1_x86_64.whl (14.1 MB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 14.1/14.1 MB 104.1 MB/s eta 0:00:00
Collecting nvidia-cudnn-cu12==8.9.2.26 (from torch>=1.10.0->accelerate==0.23.*->-r requirements.txt (line 1))
  Downloading nvidia_cudnn_cu12-8.9.2.26-py3-none-manylinux1_x86_64.whl.metadata (1.6 kB)
Collecting nvidia-cublas-cu12==12.1.3.1 (from torch>=1.10.0->accelerate==0.23.*->-r requirements.txt (line 1))
  Downloading nvidia_cublas_cu12-12.1.3.1-py3-none-manylinux1_x86_64.whl (410.6 MB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 410.6/410.6 MB 4.0 MB/s eta 0:00:00
Collecting nvidia-cufft-cu12==11.0.2.54 (from torch>=1.10.0->accelerate==0.23.*->-r requirements.txt (line 1))
  Downloading nvidia_cufft_cu12-11.0.2.54-py3-none-manylinux1_x86_64.whl (121.6 MB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 121.6/121.6 MB 17.6 MB/s eta 0:00:00
Collecting nvidia-curand-cu12==10.3.2.106 (from torch>=1.10.0->accelerate==0.23.*->-r requirements.txt (line 1))
  Downloading nvidia_curand_cu12-10.3.2.106-py3-none-manylinux1_x86_64.whl (56.5 MB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 56.5/56.5 MB 50.2 MB/s eta 0:00:00
Collecting nvidia-cusolver-cu12==11.4.5.107 (from torch>=1.10.0->accelerate==0.23.*->-r requirements.txt (line 1))
  Downloading nvidia_cusolver_cu12-11.4.5.107-py3-none-manylinux1_x86_64.whl (124.2 MB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 124.2/124.2 MB 24.1 MB/s eta 0:00:00
Collecting nvidia-cusparse-cu12==12.1.0.106 (from torch>=1.10.0->accelerate==0.23.*->-r requirements.txt (line 1))
  Downloading nvidia_cusparse_cu12-12.1.0.106-py3-none-manylinux1_x86_64.whl (196.0 MB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 196.0/196.0 MB 14.2 MB/s eta 0:00:00
Collecting nvidia-nccl-cu12==2.18.1 (from torch>=1.10.0->accelerate==0.23.*->-r requirements.txt (line 1))
  Downloading nvidia_nccl_cu12-2.18.1-py3-none-manylinux1_x86_64.whl (209.8 MB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 209.8/209.8 MB 7.5 MB/s eta 0:00:00
Collecting nvidia-nvtx-cu12==12.1.105 (from torch>=1.10.0->accelerate==0.23.*->-r requirements.txt (line 1))
  Downloading nvidia_nvtx_cu12-12.1.105-py3-none-manylinux1_x86_64.whl (99 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 99.1/99.1 kB 14.6 MB/s eta 0:00:00
Collecting triton==2.1.0 (from torch>=1.10.0->accelerate==0.23.*->-r requirements.txt (line 1))
  Downloading triton-2.1.0-0-cp310-cp310-manylinux2014_x86_64.manylinux_2_17_x86_64.whl.metadata (1.3 kB)
Collecting nvidia-nvjitlink-cu12 (from nvidia-cusolver-cu12==11.4.5.107->torch>=1.10.0->accelerate==0.23.*->-r requirements.txt (line 1))
  Downloading nvidia_nvjitlink_cu12-12.3.52-py3-none-manylinux1_x86_64.whl.metadata (1.5 kB)
Collecting h11>=0.8 (from uvicorn>=0.14.0->gradio==3.50.*->-r requirements.txt (line 6))
  Downloading h11-0.14.0-py3-none-any.whl (58 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 58.3/58.3 kB 8.8 MB/s eta 0:00:00
Collecting rootpath>=0.1.0 (from attributedict->autoawq==0.1.4->-r requirements.txt (line 87))
  Downloading rootpath-0.1.1-py3-none-any.whl (15 kB)
Collecting inspecta>=0.1.0 (from attributedict->autoawq==0.1.4->-r requirements.txt (line 87))
  Downloading inspecta-0.1.3-py3-none-any.whl (9.2 kB)
Collecting colour-runner>=0.0.5 (from attributedict->autoawq==0.1.4->-r requirements.txt (line 87))
  Downloading colour_runner-0.1.1-py2.py3-none-any.whl (3.7 kB)
Collecting deepdiff>=3.3.0 (from attributedict->autoawq==0.1.4->-r requirements.txt (line 87))
  Downloading deepdiff-6.6.1-py3-none-any.whl.metadata (6.3 kB)
Collecting tox>=3.0.0 (from attributedict->autoawq==0.1.4->-r requirements.txt (line 87))
  Downloading tox-4.11.3-py3-none-any.whl.metadata (5.0 kB)
Collecting coverage>=4.5.2 (from attributedict->autoawq==0.1.4->-r requirements.txt (line 87))
  Downloading coverage-7.3.2-cp310-cp310-manylinux_2_5_x86_64.manylinux1_x86_64.manylinux_2_17_x86_64.manylinux2014_x86_64.whl.metadata (8.1 kB)
Collecting codecov>=2.0.15 (from attributedict->autoawq==0.1.4->-r requirements.txt (line 87))
  Downloading codecov-2.1.13-py2.py3-none-any.whl (16 kB)
Collecting humanfriendly>=9.1 (from coloredlogs->optimum==1.13.1->-r requirements.txt (line 9))
  Downloading humanfriendly-10.0-py2.py3-none-any.whl (86 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 86.8/86.8 kB 13.2 MB/s eta 0:00:00
Collecting anyio<4.0.0,>=3.7.1 (from fastapi->gradio==3.50.*->-r requirements.txt (line 6))
  Downloading anyio-3.7.1-py3-none-any.whl.metadata (4.7 kB)
Collecting starlette<0.28.0,>=0.27.0 (from fastapi->gradio==3.50.*->-r requirements.txt (line 6))
  Downloading starlette-0.27.0-py3-none-any.whl.metadata (5.8 kB)
Collecting cramjam>=2.3 (from fastparquet->exllamav2==0.0.6+cu121->-r requirements.txt (line 61))
  Downloading cramjam-2.7.0-cp310-cp310-manylinux_2_17_x86_64.manylinux2014_x86_64.whl.metadata (4.0 kB)
Collecting httpcore<0.19.0,>=0.18.0 (from httpx->gradio==3.50.*->-r requirements.txt (line 6))
  Downloading httpcore-0.18.0-py3-none-any.whl.metadata (18 kB)
Collecting sniffio (from httpx->gradio==3.50.*->-r requirements.txt (line 6))
  Downloading sniffio-1.3.0-py3-none-any.whl (10 kB)
Collecting jsonlines (from lm-eval->autoawq==0.1.4->-r requirements.txt (line 87))
  Downloading jsonlines-4.0.0-py3-none-any.whl.metadata (1.6 kB)
Collecting numexpr (from lm-eval->autoawq==0.1.4->-r requirements.txt (line 87))
  Downloading numexpr-2.8.7-cp310-cp310-manylinux_2_17_x86_64.manylinux2014_x86_64.whl.metadata (8.7 kB)
Collecting openai>=0.6.4 (from lm-eval->autoawq==0.1.4->-r requirements.txt (line 87))
  Downloading openai-0.28.1-py3-none-any.whl.metadata (11 kB)
Collecting pybind11>=2.6.2 (from lm-eval->autoawq==0.1.4->-r requirements.txt (line 87))
  Downloading pybind11-2.11.1-py3-none-any.whl.metadata (9.5 kB)
Collecting pycountry (from lm-eval->autoawq==0.1.4->-r requirements.txt (line 87))
  Downloading pycountry-22.3.5.tar.gz (10.1 MB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 10.1/10.1 MB 124.6 MB/s eta 0:00:00
  Installing build dependencies ... done
  Getting requirements to build wheel ... done
  Preparing metadata (pyproject.toml) ... done
Collecting pytablewriter (from lm-eval->autoawq==0.1.4->-r requirements.txt (line 87))
  Downloading pytablewriter-1.2.0-py3-none-any.whl.metadata (37 kB)
Collecting rouge-score>=0.0.4 (from lm-eval->autoawq==0.1.4->-r requirements.txt (line 87))
  Downloading rouge_score-0.1.2.tar.gz (17 kB)
  Preparing metadata (setup.py) ... done
Collecting sacrebleu==1.5.0 (from lm-eval->autoawq==0.1.4->-r requirements.txt (line 87))
  Downloading sacrebleu-1.5.0-py3-none-any.whl (65 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 65.6/65.6 kB 510.4 kB/s eta 0:00:00
Collecting scikit-learn>=0.24.1 (from lm-eval->autoawq==0.1.4->-r requirements.txt (line 87))
  Downloading scikit_learn-1.3.2-cp310-cp310-manylinux_2_17_x86_64.manylinux2014_x86_64.whl.metadata (11 kB)
Collecting sqlitedict (from lm-eval->autoawq==0.1.4->-r requirements.txt (line 87))
  Downloading sqlitedict-2.1.0.tar.gz (21 kB)
  Preparing metadata (setup.py) ... done
Collecting tqdm-multiprocess (from lm-eval->autoawq==0.1.4->-r requirements.txt (line 87))
  Downloading tqdm_multiprocess-0.0.11-py3-none-any.whl (9.8 kB)
Collecting zstandard (from lm-eval->autoawq==0.1.4->-r requirements.txt (line 87))
  Downloading zstandard-0.21.0-cp310-cp310-manylinux_2_17_x86_64.manylinux2014_x86_64.whl (2.7 MB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 2.7/2.7 MB 18.9 MB/s eta 0:00:00
Collecting portalocker (from sacrebleu==1.5.0->lm-eval->autoawq==0.1.4->-r requirements.txt (line 87))
  Downloading portalocker-2.8.2-py3-none-any.whl.metadata (8.5 kB)
Collecting mpmath>=0.19 (from sympy->optimum==1.13.1->-r requirements.txt (line 9))
  Downloading mpmath-1.3.0-py3-none-any.whl (536 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 536.2/536.2 kB 4.5 MB/s eta 0:00:00
Collecting exceptiongroup (from anyio<4.0.0,>=3.7.1->fastapi->gradio==3.50.*->-r requirements.txt (line 6))
  Downloading exceptiongroup-1.1.3-py3-none-any.whl.metadata (6.1 kB)
Collecting blessings (from colour-runner>=0.0.5->attributedict->autoawq==0.1.4->-r requirements.txt (line 87))
  Downloading blessings-1.7-py3-none-any.whl (18 kB)
Collecting ordered-set<4.2.0,>=4.0.2 (from deepdiff>=3.3.0->attributedict->autoawq==0.1.4->-r requirements.txt (line 87))
  Downloading ordered_set-4.1.0-py3-none-any.whl (7.6 kB)
Collecting smmap<6,>=3.0.1 (from gitdb<5,>=4.0.1->GitPython!=3.1.29,>=1.0.0->wandb->-r requirements.txt (line 21))
  Downloading smmap-5.0.1-py3-none-any.whl.metadata (4.3 kB)
Collecting termcolor>=1.1.0 (from inspecta>=0.1.0->attributedict->autoawq==0.1.4->-r requirements.txt (line 87))
  Downloading termcolor-2.3.0-py3-none-any.whl (6.9 kB)
Collecting jsonschema-specifications>=2023.03.6 (from jsonschema>=3.0->altair<6.0,>=4.2.0->gradio==3.50.*->-r requirements.txt (line 6))
  Downloading jsonschema_specifications-2023.7.1-py3-none-any.whl.metadata (2.8 kB)
Collecting referencing>=0.28.4 (from jsonschema>=3.0->altair<6.0,>=4.2.0->gradio==3.50.*->-r requirements.txt (line 6))
  Downloading referencing-0.30.2-py3-none-any.whl.metadata (2.6 kB)
Collecting rpds-py>=0.7.1 (from jsonschema>=3.0->altair<6.0,>=4.2.0->gradio==3.50.*->-r requirements.txt (line 6))
  Downloading rpds_py-0.10.6-cp310-cp310-manylinux_2_17_x86_64.manylinux2014_x86_64.whl.metadata (3.7 kB)
Collecting pyasn1<0.6.0,>=0.4.6 (from pyasn1-modules>=0.2.1->google-auth<3,>=1.6.3->tensorboard->-r requirements.txt (line 18))
  Downloading pyasn1-0.5.0-py2.py3-none-any.whl (83 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 83.9/83.9 kB 11.9 MB/s eta 0:00:00
Collecting oauthlib>=3.0.0 (from requests-oauthlib>=0.7.0->google-auth-oauthlib<2,>=0.5->tensorboard->-r requirements.txt (line 18))
  Downloading oauthlib-3.2.2-py3-none-any.whl (151 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 151.7/151.7 kB 20.6 MB/s eta 0:00:00
Collecting nltk (from rouge-score>=0.0.4->lm-eval->autoawq==0.1.4->-r requirements.txt (line 87))
  Downloading nltk-3.8.1-py3-none-any.whl (1.5 MB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 1.5/1.5 MB 85.9 MB/s eta 0:00:00
Collecting joblib>=1.1.1 (from scikit-learn>=0.24.1->lm-eval->autoawq==0.1.4->-r requirements.txt (line 87))
  Downloading joblib-1.3.2-py3-none-any.whl.metadata (5.4 kB)
Collecting threadpoolctl>=2.0.0 (from scikit-learn>=0.24.1->lm-eval->autoawq==0.1.4->-r requirements.txt (line 87))
  Downloading threadpoolctl-3.2.0-py3-none-any.whl.metadata (10.0 kB)
Collecting chardet>=5.2 (from tox>=3.0.0->attributedict->autoawq==0.1.4->-r requirements.txt (line 87))
  Downloading chardet-5.2.0-py3-none-any.whl.metadata (3.4 kB)
Collecting platformdirs>=3.10 (from tox>=3.0.0->attributedict->autoawq==0.1.4->-r requirements.txt (line 87))
  Downloading platformdirs-3.11.0-py3-none-any.whl.metadata (11 kB)
Collecting pluggy>=1.3 (from tox>=3.0.0->attributedict->autoawq==0.1.4->-r requirements.txt (line 87))
  Downloading pluggy-1.3.0-py3-none-any.whl.metadata (4.3 kB)
Collecting pyproject-api>=1.6.1 (from tox>=3.0.0->attributedict->autoawq==0.1.4->-r requirements.txt (line 87))
  Downloading pyproject_api-1.6.1-py3-none-any.whl.metadata (2.8 kB)
Collecting tomli>=2.0.1 (from tox>=3.0.0->attributedict->autoawq==0.1.4->-r requirements.txt (line 87))
  Downloading tomli-2.0.1-py3-none-any.whl (12 kB)
Collecting virtualenv>=20.24.3 (from tox>=3.0.0->attributedict->autoawq==0.1.4->-r requirements.txt (line 87))
  Downloading virtualenv-20.24.6-py3-none-any.whl.metadata (4.5 kB)
Collecting DataProperty<2,>=1.0.1 (from pytablewriter->lm-eval->autoawq==0.1.4->-r requirements.txt (line 87))
  Downloading DataProperty-1.0.1-py3-none-any.whl.metadata (11 kB)
Collecting mbstrdecoder<2,>=1.0.0 (from pytablewriter->lm-eval->autoawq==0.1.4->-r requirements.txt (line 87))
  Downloading mbstrdecoder-1.1.3-py3-none-any.whl.metadata (4.0 kB)
Collecting pathvalidate<4,>=2.3.0 (from pytablewriter->lm-eval->autoawq==0.1.4->-r requirements.txt (line 87))
  Downloading pathvalidate-3.2.0-py3-none-any.whl.metadata (11 kB)
Collecting tabledata<2,>=1.3.1 (from pytablewriter->lm-eval->autoawq==0.1.4->-r requirements.txt (line 87))
  Downloading tabledata-1.3.3-py3-none-any.whl.metadata (3.7 kB)
Collecting tcolorpy<1,>=0.0.5 (from pytablewriter->lm-eval->autoawq==0.1.4->-r requirements.txt (line 87))
  Downloading tcolorpy-0.1.4-py3-none-any.whl.metadata (5.7 kB)
Collecting typepy<2,>=1.3.2 (from typepy[datetime]<2,>=1.3.2->pytablewriter->lm-eval->autoawq==0.1.4->-r requirements.txt (line 87))
  Downloading typepy-1.3.2-py3-none-any.whl.metadata (9.3 kB)
Collecting distlib<1,>=0.3.7 (from virtualenv>=20.24.3->tox>=3.0.0->attributedict->autoawq==0.1.4->-r requirements.txt (line 87))
  Downloading distlib-0.3.7-py2.py3-none-any.whl.metadata (5.1 kB)
Downloading accelerate-0.23.0-py3-none-any.whl (258 kB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 258.1/258.1 kB 28.9 MB/s eta 0:00:00
Downloading gradio-3.50.2-py3-none-any.whl (20.3 MB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 20.3/20.3 MB 86.6 MB/s eta 0:00:00
Downloading numpy-1.24.4-cp310-cp310-manylinux_2_17_x86_64.manylinux2014_x86_64.whl (17.3 MB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 17.3/17.3 MB 92.6 MB/s eta 0:00:00
Downloading optimum-1.13.1-py3-none-any.whl (396 kB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 396.1/396.1 kB 39.8 MB/s eta 0:00:00
Downloading peft-0.5.0-py3-none-any.whl (85 kB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 85.6/85.6 kB 13.2 MB/s eta 0:00:00
Downloading safetensors-0.4.0-cp310-cp310-manylinux_2_17_x86_64.manylinux2014_x86_64.whl (1.3 MB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 1.3/1.3 MB 81.9 MB/s eta 0:00:00
Downloading transformers-4.34.1-py3-none-any.whl (7.7 MB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 7.7/7.7 MB 130.8 MB/s eta 0:00:00
Downloading bitsandbytes-0.41.1-py3-none-any.whl (92.6 MB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 92.6/92.6 MB 30.8 MB/s eta 0:00:00
Downloading autoawq-0.1.4-cp310-cp310-manylinux2014_x86_64.whl (20.0 MB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 20.0/20.0 MB 91.2 MB/s eta 0:00:00
Downloading gradio_client-0.6.1-py3-none-any.whl (299 kB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 299.2/299.2 kB 34.5 MB/s eta 0:00:00
Downloading datasets-2.14.6-py3-none-any.whl (493 kB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 493.7/493.7 kB 49.8 MB/s eta 0:00:00
Downloading einops-0.7.0-py3-none-any.whl (44 kB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 44.6/44.6 kB 6.1 MB/s eta 0:00:00
Downloading Markdown-3.5-py3-none-any.whl (101 kB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 101.7/101.7 kB 14.5 MB/s eta 0:00:00
Downloading pandas-2.1.1-cp310-cp310-manylinux_2_17_x86_64.manylinux2014_x86_64.whl (12.3 MB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 12.3/12.3 MB 109.9 MB/s eta 0:00:00
Downloading Pillow-10.1.0-cp310-cp310-manylinux_2_28_x86_64.whl (3.6 MB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 3.6/3.6 MB 110.9 MB/s eta 0:00:00
Downloading PyYAML-6.0.1-cp310-cp310-manylinux_2_17_x86_64.manylinux2014_x86_64.whl (705 kB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 705.5/705.5 kB 60.6 MB/s eta 0:00:00
Downloading requests-2.31.0-py3-none-any.whl (62 kB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 62.6/62.6 kB 8.9 MB/s eta 0:00:00
Downloading scipy-1.11.3-cp310-cp310-manylinux_2_17_x86_64.manylinux2014_x86_64.whl (36.4 MB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 36.4/36.4 MB 47.0 MB/s eta 0:00:00
Downloading tensorboard-2.15.0-py3-none-any.whl (5.6 MB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 5.6/5.6 MB 126.2 MB/s eta 0:00:00
Downloading tqdm-4.66.1-py3-none-any.whl (78 kB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 78.3/78.3 kB 11.7 MB/s eta 0:00:00
Downloading wandb-0.15.12-py3-none-any.whl (2.1 MB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 2.1/2.1 MB 87.2 MB/s eta 0:00:00
Downloading absl_py-2.0.0-py3-none-any.whl (130 kB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 130.2/130.2 kB 18.5 MB/s eta 0:00:00
Downloading aiofiles-23.2.1-py3-none-any.whl (15 kB)
Downloading altair-5.1.2-py3-none-any.whl (516 kB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 516.2/516.2 kB 55.3 MB/s eta 0:00:00
Downloading certifi-2023.7.22-py3-none-any.whl (158 kB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 158.3/158.3 kB 21.3 MB/s eta 0:00:00
Downloading charset_normalizer-3.3.1-cp310-cp310-manylinux_2_17_x86_64.manylinux2014_x86_64.whl (139 kB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 139.2/139.2 kB 18.6 MB/s eta 0:00:00
Downloading click-8.1.7-py3-none-any.whl (97 kB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 97.9/97.9 kB 14.4 MB/s eta 0:00:00
Downloading dill-0.3.7-py3-none-any.whl (115 kB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 115.3/115.3 kB 17.0 MB/s eta 0:00:00
Downloading diskcache-5.6.3-py3-none-any.whl (45 kB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 45.5/45.5 kB 6.9 MB/s eta 0:00:00
Downloading fsspec-2023.10.0-py3-none-any.whl (166 kB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 166.4/166.4 kB 24.3 MB/s eta 0:00:00
Downloading aiohttp-3.8.6-cp310-cp310-manylinux_2_17_x86_64.manylinux2014_x86_64.whl (1.0 MB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 1.0/1.0 MB 80.8 MB/s eta 0:00:00
Downloading GitPython-3.1.40-py3-none-any.whl (190 kB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 190.6/190.6 kB 27.2 MB/s eta 0:00:00
Downloading google_auth-2.23.3-py2.py3-none-any.whl (182 kB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 182.3/182.3 kB 25.1 MB/s eta 0:00:00
Downloading google_auth_oauthlib-1.1.0-py2.py3-none-any.whl (19 kB)
Downloading grpcio-1.59.0-cp310-cp310-manylinux_2_17_x86_64.manylinux2014_x86_64.whl (5.3 MB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 5.3/5.3 MB 122.5 MB/s eta 0:00:00
Downloading importlib_resources-6.1.0-py3-none-any.whl (33 kB)
Downloading MarkupSafe-2.1.3-cp310-cp310-manylinux_2_17_x86_64.manylinux2014_x86_64.whl (25 kB)
Downloading matplotlib-3.8.0-cp310-cp310-manylinux_2_17_x86_64.manylinux2014_x86_64.whl (11.6 MB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 11.6/11.6 MB 114.6 MB/s eta 0:00:00
Downloading orjson-3.9.9-cp310-cp310-manylinux_2_17_x86_64.manylinux2014_x86_64.whl (138 kB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 138.7/138.7 kB 18.4 MB/s eta 0:00:00
Downloading packaging-23.2-py3-none-any.whl (53 kB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 53.0/53.0 kB 7.4 MB/s eta 0:00:00
Downloading protobuf-4.23.4-cp37-abi3-manylinux2014_x86_64.whl (304 kB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 304.5/304.5 kB 39.3 MB/s eta 0:00:00
Downloading psutil-5.9.6-cp36-abi3-manylinux_2_12_x86_64.manylinux2010_x86_64.manylinux_2_17_x86_64.manylinux2014_x86_64.whl (283 kB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 283.6/283.6 kB 36.4 MB/s eta 0:00:00
Downloading pyarrow-13.0.0-cp310-cp310-manylinux_2_28_x86_64.whl (40.0 MB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 40.0/40.0 MB 53.7 MB/s eta 0:00:00
Downloading pydantic-2.4.2-py3-none-any.whl (395 kB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 395.8/395.8 kB 45.9 MB/s eta 0:00:00
Downloading pydantic_core-2.10.1-cp310-cp310-manylinux_2_17_x86_64.manylinux2014_x86_64.whl (2.0 MB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 2.0/2.0 MB 97.5 MB/s eta 0:00:00
Downloading pytz-2023.3.post1-py2.py3-none-any.whl (502 kB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 502.5/502.5 kB 56.9 MB/s eta 0:00:00
Downloading regex-2023.10.3-cp310-cp310-manylinux_2_17_x86_64.manylinux2014_x86_64.whl (773 kB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 773.9/773.9 kB 70.2 MB/s eta 0:00:00
Downloading sentry_sdk-1.32.0-py2.py3-none-any.whl (240 kB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 241.0/241.0 kB 31.2 MB/s eta 0:00:00
Downloading tensorboard_data_server-0.7.2-py3-none-manylinux_2_31_x86_64.whl (6.6 MB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 6.6/6.6 MB 55.3 MB/s eta 0:00:00
Downloading tokenizers-0.14.1-cp310-cp310-manylinux_2_17_x86_64.manylinux2014_x86_64.whl (3.8 MB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 3.8/3.8 MB 118.1 MB/s eta 0:00:00
Downloading huggingface_hub-0.17.3-py3-none-any.whl (295 kB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 295.0/295.0 kB 29.2 MB/s eta 0:00:00
Downloading torch-2.1.0-cp310-cp310-manylinux1_x86_64.whl (670.2 MB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 670.2/670.2 MB 1.5 MB/s eta 0:00:00
Downloading nvidia_cudnn_cu12-8.9.2.26-py3-none-manylinux1_x86_64.whl (731.7 MB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 731.7/731.7 MB 1.2 MB/s eta 0:00:00
Downloading triton-2.1.0-0-cp310-cp310-manylinux2014_x86_64.manylinux_2_17_x86_64.whl (89.2 MB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 89.2/89.2 MB 31.2 MB/s eta 0:00:00
Downloading typing_extensions-4.8.0-py3-none-any.whl (31 kB)
Downloading urllib3-2.0.7-py3-none-any.whl (124 kB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 124.2/124.2 kB 18.4 MB/s eta 0:00:00
Downloading uvicorn-0.23.2-py3-none-any.whl (59 kB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 59.5/59.5 kB 8.2 MB/s eta 0:00:00
Downloading werkzeug-3.0.0-py3-none-any.whl (226 kB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 226.6/226.6 kB 30.9 MB/s eta 0:00:00
Downloading fastapi-0.104.0-py3-none-any.whl (92 kB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 92.9/92.9 kB 13.4 MB/s eta 0:00:00
Downloading fastparquet-2023.8.0-cp310-cp310-manylinux_2_17_x86_64.manylinux2014_x86_64.whl (1.7 MB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 1.7/1.7 MB 87.2 MB/s eta 0:00:00
Downloading filelock-3.12.4-py3-none-any.whl (11 kB)
Downloading httpx-0.25.0-py3-none-any.whl (75 kB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 75.7/75.7 kB 11.1 MB/s eta 0:00:00
Downloading multiprocess-0.70.15-py310-none-any.whl (134 kB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 134.8/134.8 kB 19.9 MB/s eta 0:00:00
Downloading ninja-1.11.1.1-py2.py3-none-manylinux1_x86_64.manylinux_2_5_x86_64.whl (307 kB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 307.2/307.2 kB 39.4 MB/s eta 0:00:00
Downloading Pygments-2.16.1-py3-none-any.whl (1.2 MB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 1.2/1.2 MB 81.7 MB/s eta 0:00:00
Downloading setproctitle-1.3.3-cp310-cp310-manylinux_2_5_x86_64.manylinux1_x86_64.manylinux_2_17_x86_64.manylinux2014_x86_64.whl (30 kB)
Downloading texttable-1.7.0-py2.py3-none-any.whl (10 kB)
Downloading torchvision-0.16.0-cp310-cp310-manylinux1_x86_64.whl (6.9 MB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 6.9/6.9 MB 116.1 MB/s eta 0:00:00
Downloading xxhash-3.4.1-cp310-cp310-manylinux_2_17_x86_64.manylinux2014_x86_64.whl (194 kB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 194.1/194.1 kB 23.5 MB/s eta 0:00:00
Downloading annotated_types-0.6.0-py3-none-any.whl (12 kB)
Downloading anyio-3.7.1-py3-none-any.whl (80 kB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 80.9/80.9 kB 11.8 MB/s eta 0:00:00
Downloading async_timeout-4.0.3-py3-none-any.whl (5.7 kB)
Downloading cachetools-5.3.1-py3-none-any.whl (9.3 kB)
Downloading contourpy-1.1.1-cp310-cp310-manylinux_2_17_x86_64.manylinux2014_x86_64.whl (301 kB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 301.7/301.7 kB 37.4 MB/s eta 0:00:00
Downloading coverage-7.3.2-cp310-cp310-manylinux_2_5_x86_64.manylinux1_x86_64.manylinux_2_17_x86_64.manylinux2014_x86_64.whl (227 kB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 227.5/227.5 kB 29.2 MB/s eta 0:00:00
Downloading cramjam-2.7.0-cp310-cp310-manylinux_2_17_x86_64.manylinux2014_x86_64.whl (1.6 MB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 1.6/1.6 MB 89.0 MB/s eta 0:00:00
Downloading cycler-0.12.1-py3-none-any.whl (8.3 kB)
Downloading deepdiff-6.6.1-py3-none-any.whl (73 kB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 73.6/73.6 kB 10.6 MB/s eta 0:00:00
Downloading fonttools-4.43.1-cp310-cp310-manylinux_2_17_x86_64.manylinux2014_x86_64.whl (4.5 MB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 4.5/4.5 MB 103.1 MB/s eta 0:00:00
Downloading frozenlist-1.4.0-cp310-cp310-manylinux_2_5_x86_64.manylinux1_x86_64.manylinux_2_17_x86_64.manylinux2014_x86_64.whl (225 kB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 225.7/225.7 kB 27.7 MB/s eta 0:00:00
Downloading gitdb-4.0.11-py3-none-any.whl (62 kB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 62.7/62.7 kB 7.9 MB/s eta 0:00:00
Downloading httpcore-0.18.0-py3-none-any.whl (76 kB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 76.0/76.0 kB 11.0 MB/s eta 0:00:00
Downloading jsonschema-4.19.1-py3-none-any.whl (83 kB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 83.3/83.3 kB 11.6 MB/s eta 0:00:00
Downloading kiwisolver-1.4.5-cp310-cp310-manylinux_2_12_x86_64.manylinux2010_x86_64.whl (1.6 MB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 1.6/1.6 MB 90.0 MB/s eta 0:00:00
Downloading openai-0.28.1-py3-none-any.whl (76 kB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 77.0/77.0 kB 11.6 MB/s eta 0:00:00
Downloading pybind11-2.11.1-py3-none-any.whl (227 kB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 227.7/227.7 kB 31.6 MB/s eta 0:00:00
Downloading pyparsing-3.1.1-py3-none-any.whl (103 kB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 103.1/103.1 kB 15.1 MB/s eta 0:00:00
Downloading scikit_learn-1.3.2-cp310-cp310-manylinux_2_17_x86_64.manylinux2014_x86_64.whl (10.8 MB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 10.8/10.8 MB 42.6 MB/s eta 0:00:00
Downloading starlette-0.27.0-py3-none-any.whl (66 kB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 67.0/67.0 kB 9.2 MB/s eta 0:00:00
Downloading tox-4.11.3-py3-none-any.whl (153 kB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 153.8/153.8 kB 19.7 MB/s eta 0:00:00
Downloading jsonlines-4.0.0-py3-none-any.whl (8.7 kB)
Downloading networkx-3.2-py3-none-any.whl (1.6 MB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 1.6/1.6 MB 88.8 MB/s eta 0:00:00
Downloading numexpr-2.8.7-cp310-cp310-manylinux_2_17_x86_64.manylinux2014_x86_64.whl (384 kB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 384.1/384.1 kB 42.8 MB/s eta 0:00:00
Downloading pytablewriter-1.2.0-py3-none-any.whl (111 kB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 111.1/111.1 kB 13.0 MB/s eta 0:00:00
Downloading chardet-5.2.0-py3-none-any.whl (199 kB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 199.4/199.4 kB 24.1 MB/s eta 0:00:00
Downloading DataProperty-1.0.1-py3-none-any.whl (27 kB)
Downloading joblib-1.3.2-py3-none-any.whl (302 kB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 302.2/302.2 kB 34.8 MB/s eta 0:00:00
Downloading jsonschema_specifications-2023.7.1-py3-none-any.whl (17 kB)
Downloading mbstrdecoder-1.1.3-py3-none-any.whl (7.8 kB)
Downloading pathvalidate-3.2.0-py3-none-any.whl (23 kB)
Downloading platformdirs-3.11.0-py3-none-any.whl (17 kB)
Downloading pluggy-1.3.0-py3-none-any.whl (18 kB)
Downloading pyproject_api-1.6.1-py3-none-any.whl (12 kB)
Downloading referencing-0.30.2-py3-none-any.whl (25 kB)
Downloading rpds_py-0.10.6-cp310-cp310-manylinux_2_17_x86_64.manylinux2014_x86_64.whl (1.2 MB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 1.2/1.2 MB 66.5 MB/s eta 0:00:00
Downloading smmap-5.0.1-py3-none-any.whl (24 kB)
Downloading tabledata-1.3.3-py3-none-any.whl (11 kB)
Downloading tcolorpy-0.1.4-py3-none-any.whl (7.9 kB)
Downloading threadpoolctl-3.2.0-py3-none-any.whl (15 kB)
Downloading typepy-1.3.2-py3-none-any.whl (31 kB)
Downloading virtualenv-20.24.6-py3-none-any.whl (3.8 MB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 3.8/3.8 MB 115.4 MB/s eta 0:00:00
Downloading exceptiongroup-1.1.3-py3-none-any.whl (14 kB)
Downloading nvidia_nvjitlink_cu12-12.3.52-py3-none-manylinux1_x86_64.whl (20.5 MB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 20.5/20.5 MB 76.8 MB/s eta 0:00:00
Downloading portalocker-2.8.2-py3-none-any.whl (17 kB)
Downloading distlib-0.3.7-py2.py3-none-any.whl (468 kB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 468.9/468.9 kB 48.4 MB/s eta 0:00:00
Building wheels for collected packages: torch-grammar, ffmpy, pathtools, rouge-score, pycountry, sqlitedict
  Building wheel for torch-grammar (pyproject.toml) ... done
  Created wheel for torch-grammar: filename=torch_grammar-0.3.3-py3-none-any.whl size=8254 sha256=b0ef8f0dabf2db1c32a6e0da65836e0d5fc7d6afca596517a39f0d6ea75954d8
  Stored in directory: /tmp/pip-ephem-wheel-cache-d4fcand8/wheels/dd/00/c9/08292a4496a8b7e174aefc6e0a8194cbb53977b7cbdd3006b7
  Building wheel for ffmpy (setup.py) ... done
  Created wheel for ffmpy: filename=ffmpy-0.3.1-py3-none-any.whl size=5579 sha256=46547e90b8b1ad21dfb03cc636c221e5e34e8af890a374595542b0281d538120
  Stored in directory: /home/gbike/.cache/pip/wheels/01/a6/d1/1c0828c304a4283b2c1639a09ad86f83d7c487ef34c6b4a1bf
  Building wheel for pathtools (setup.py) ... done
  Created wheel for pathtools: filename=pathtools-0.1.2-py3-none-any.whl size=8791 sha256=bebd86836812d862a05bfb3b05d78e6226f7757cb4cad980b43d86acb4970a99
  Stored in directory: /home/gbike/.cache/pip/wheels/e7/f3/22/152153d6eb222ee7a56ff8617d80ee5207207a8c00a7aab794
  Building wheel for rouge-score (setup.py) ... done
  Created wheel for rouge-score: filename=rouge_score-0.1.2-py3-none-any.whl size=24932 sha256=f3f0258e7cbf66106bfa6d7c9f1dc71ec9f46357e64b5568309555534ecadfa1
  Stored in directory: /home/gbike/.cache/pip/wheels/5f/dd/89/461065a73be61a532ff8599a28e9beef17985c9e9c31e541b4
  Building wheel for pycountry (pyproject.toml) ... done
  Created wheel for pycountry: filename=pycountry-22.3.5-py2.py3-none-any.whl size=10681833 sha256=e5524cf37341c8b408a13b62b0e3b3a9a58abba138db1113e57df583e9e04113
  Stored in directory: /home/gbike/.cache/pip/wheels/03/57/cc/290c5252ec97a6d78d36479a3c5e5ecc76318afcb241ad9dbe
  Building wheel for sqlitedict (setup.py) ... done
  Created wheel for sqlitedict: filename=sqlitedict-2.1.0-py3-none-any.whl size=16864 sha256=d668398e26a95ea6966ad81213b938b91fc3e7eb6d0b7e84d03c55c5cb0a5df1
  Stored in directory: /home/gbike/.cache/pip/wheels/79/d6/e7/304e0e6cb2221022c26d8161f7c23cd4f259a9e41e8bbcfabd
Successfully built torch-grammar ffmpy pathtools rouge-score pycountry sqlitedict
Installing collected packages: texttable, sqlitedict, sentencepiece, pytz, pydub, py-cpuinfo, pathtools, ninja, mpmath, gptq-for-llama, ffmpy, distlib, bitsandbytes, appdirs, zstandard, xxhash, websockets, urllib3, tzdata, typing-extensions, tqdm, toolz, tomli, toml, threadpoolctl, termcolor, tensorboard-data-server, tcolorpy, tabulate, sympy, sniffio, smmap, six, setproctitle, semantic-version, safetensors, rpds-py, regex, pyyaml, python-multipart, pyparsing, pygments, pycountry, pybind11, pyasn1, psutil, protobuf, portalocker, pluggy, platformdirs, Pillow, pathvalidate, packaging, orjson, ordered-set, oauthlib, nvidia-nvtx-cu12, nvidia-nvjitlink-cu12, nvidia-nccl-cu12, nvidia-curand-cu12, nvidia-cufft-cu12, nvidia-cuda-runtime-cu12, nvidia-cuda-nvrtc-cu12, nvidia-cuda-cupti-cu12, nvidia-cublas-cu12, numpy, networkx, multidict, markupsafe, markdown, kiwisolver, joblib, importlib-resources, idna, humanfriendly, h11, grpcio, fsspec, frozenlist, fonttools, filelock, exceptiongroup, einops, diskcache, dill, cycler, cramjam, coverage, colorama, Click, charset-normalizer, chardet, certifi, cachetools, attrs, async-timeout, annotated-types, aiofiles, absl-py, yarl, werkzeug, virtualenv, uvicorn, triton, tqdm-multiprocess, sentry-sdk, scipy, sacrebleu, rsa, rouge, requests, referencing, python-dateutil, pyproject-api, pydantic-core, pyasn1-modules, pyarrow, nvidia-cusparse-cu12, nvidia-cudnn-cu12, numexpr, nltk, multiprocess, mbstrdecoder, llama-cpp-python-cuda, llama-cpp-python, jsonlines, jinja2, gitdb, docker-pycreds, deepdiff, contourpy, coloredlogs, blessings, anyio, aiosignal, typepy, tox, starlette, scikit-learn, rouge-score, requests-oauthlib, pydantic, pandas, nvidia-cusolver-cu12, matplotlib, jsonschema-specifications, huggingface-hub, httpcore, google-auth, GitPython, colour-runner, codecov, aiohttp, wandb, torch, tokenizers, rootpath, openai, jsonschema, httpx, google-auth-oauthlib, fastparquet, fastapi, ctransformers, transformers, torchvision, tensorboard, inspecta, gradio-client, flash-attn, exllamav2, exllama, datasets, DataProperty, altair, accelerate, torch-grammar, tabledata, peft, gradio, attributedict, pytablewriter, optimum, auto-gptq, lm-eval, autoawq
Successfully installed Click-8.1.7 DataProperty-1.0.1 GitPython-3.1.40 Pillow-10.1.0 absl-py-2.0.0 accelerate-0.23.0 aiofiles-23.2.1 aiohttp-3.8.6 aiosignal-1.3.1 altair-5.1.2 annotated-types-0.6.0 anyio-3.7.1 appdirs-1.4.4 async-timeout-4.0.3 attributedict-0.3.0 attrs-23.1.0 auto-gptq-0.4.2+cu121 autoawq-0.1.4 bitsandbytes-0.41.1 blessings-1.7 cachetools-5.3.1 certifi-2023.7.22 chardet-5.2.0 charset-normalizer-3.3.1 codecov-2.1.13 colorama-0.4.6 coloredlogs-15.0.1 colour-runner-0.1.1 contourpy-1.1.1 coverage-7.3.2 cramjam-2.7.0 ctransformers-0.2.27+cu121 cycler-0.12.1 datasets-2.14.6 deepdiff-6.6.1 dill-0.3.7 diskcache-5.6.3 distlib-0.3.7 docker-pycreds-0.4.0 einops-0.7.0 exceptiongroup-1.1.3 exllama-0.0.18+cu121 exllamav2-0.0.6+cu121 fastapi-0.104.0 fastparquet-2023.8.0 ffmpy-0.3.1 filelock-3.12.4 flash-attn-2.3.2 fonttools-4.43.1 frozenlist-1.4.0 fsspec-2023.10.0 gitdb-4.0.11 google-auth-2.23.3 google-auth-oauthlib-1.1.0 gptq-for-llama-0.1.1+cu121 gradio-3.50.2 gradio-client-0.6.1 grpcio-1.59.0 h11-0.14.0 httpcore-0.18.0 httpx-0.25.0 huggingface-hub-0.17.3 humanfriendly-10.0 idna-3.4 importlib-resources-6.1.0 inspecta-0.1.3 jinja2-3.1.2 joblib-1.3.2 jsonlines-4.0.0 jsonschema-4.19.1 jsonschema-specifications-2023.7.1 kiwisolver-1.4.5 llama-cpp-python-0.2.11 llama-cpp-python-cuda-0.2.11+cu121 lm-eval-0.3.0 markdown-3.5 markupsafe-2.1.3 matplotlib-3.8.0 mbstrdecoder-1.1.3 mpmath-1.3.0 multidict-6.0.4 multiprocess-0.70.15 networkx-3.2 ninja-1.11.1.1 nltk-3.8.1 numexpr-2.8.7 numpy-1.24.4 nvidia-cublas-cu12-12.1.3.1 nvidia-cuda-cupti-cu12-12.1.105 nvidia-cuda-nvrtc-cu12-12.1.105 nvidia-cuda-runtime-cu12-12.1.105 nvidia-cudnn-cu12-8.9.2.26 nvidia-cufft-cu12-11.0.2.54 nvidia-curand-cu12-10.3.2.106 nvidia-cusolver-cu12-11.4.5.107 nvidia-cusparse-cu12-12.1.0.106 nvidia-nccl-cu12-2.18.1 nvidia-nvjitlink-cu12-12.3.52 nvidia-nvtx-cu12-12.1.105 oauthlib-3.2.2 openai-0.28.1 optimum-1.13.1 ordered-set-4.1.0 orjson-3.9.9 packaging-23.2 pandas-2.1.1 pathtools-0.1.2 pathvalidate-3.2.0 peft-0.5.0 platformdirs-3.11.0 pluggy-1.3.0 portalocker-2.8.2 protobuf-4.23.4 psutil-5.9.6 py-cpuinfo-9.0.0 pyarrow-13.0.0 pyasn1-0.5.0 pyasn1-modules-0.3.0 pybind11-2.11.1 pycountry-22.3.5 pydantic-2.4.2 pydantic-core-2.10.1 pydub-0.25.1 pygments-2.16.1 pyparsing-3.1.1 pyproject-api-1.6.1 pytablewriter-1.2.0 python-dateutil-2.8.2 python-multipart-0.0.6 pytz-2023.3.post1 pyyaml-6.0.1 referencing-0.30.2 regex-2023.10.3 requests-2.31.0 requests-oauthlib-1.3.1 rootpath-0.1.1 rouge-1.0.1 rouge-score-0.1.2 rpds-py-0.10.6 rsa-4.9 sacrebleu-1.5.0 safetensors-0.4.0 scikit-learn-1.3.2 scipy-1.11.3 semantic-version-2.10.0 sentencepiece-0.1.99 sentry-sdk-1.32.0 setproctitle-1.3.3 six-1.16.0 smmap-5.0.1 sniffio-1.3.0 sqlitedict-2.1.0 starlette-0.27.0 sympy-1.12 tabledata-1.3.3 tabulate-0.9.0 tcolorpy-0.1.4 tensorboard-2.15.0 tensorboard-data-server-0.7.2 termcolor-2.3.0 texttable-1.7.0 threadpoolctl-3.2.0 tokenizers-0.14.1 toml-0.10.2 tomli-2.0.1 toolz-0.12.0 torch-2.1.0 torch-grammar-0.3.3 torchvision-0.16.0 tox-4.11.3 tqdm-4.66.1 tqdm-multiprocess-0.0.11 transformers-4.34.1 triton-2.1.0 typepy-1.3.2 typing-extensions-4.8.0 tzdata-2023.3 urllib3-2.0.7 uvicorn-0.23.2 virtualenv-20.24.6 wandb-0.15.12 websockets-11.0.3 werkzeug-3.0.0 xxhash-3.4.1 yarl-1.9.2 zstandard-0.21.0

================================================================================
(textgen2) USER@192-168-0-1:~/AI_test/text-generation-webui$ python server.py
================================================================================

/home/gbike/anaconda3/envs/textgen2/lib/python3.10/site-packages/torch/cuda/__init__.py:611: UserWarning: Can't initialize NVML
  warnings.warn("Can't initialize NVML")
/home/gbike/anaconda3/envs/textgen2/lib/python3.10/site-packages/torch/cuda/__init__.py:740: UserWarning: CUDA initialization: The NVIDIA driver on your system is too old (found version 11070). Please update your GPU driver by downloading and installing a new version from the URL: http://www.nvidia.com/Download/index.aspx Alternatively, go to: https://pytorch.org to install a PyTorch version that has been compiled with your version of the CUDA driver. (Triggered internally at ../c10/cuda/CUDAFunctions.cpp:108.)
  return torch._C._cuda_getDeviceCount() if nvml_count < 0 else nvml_count
/home/gbike/anaconda3/envs/textgen2/lib/python3.10/site-packages/bitsandbytes/cextension.py:34: UserWarning: The installed version of bitsandbytes was compiled without GPU support. 8-bit optimizers, 8-bit multiplication, and GPU quantization are unavailable.
  warn("The installed version of bitsandbytes was compiled without GPU support. "
/home/gbike/anaconda3/envs/textgen2/lib/python3.10/site-packages/bitsandbytes/libbitsandbytes_cpu.so: undefined symbol: cadam32bit_grad_fp32
2023-10-24 14:27:58 INFO:Loading the extension "gallery"...
Running on local URL:  http://127.0.0.1:7860

To create a public link, set `share=True` in `launch()`.

================================================================================
(textgen2) USER@192-168-0-1:~/AI_test/text-generation-webui$ python server.py --listen
================================================================================

2023-10-25 07:55:30 WARNING:
You are potentially exposing the web UI to the entire internet without any access password.
You can create one with the "--gradio-auth" flag like this:

--gradio-auth username:password

Make sure to replace username:password with your own.
/home/gbike/anaconda3/envs/textgen2/lib/python3.10/site-packages/torch/cuda/__init__.py:611: UserWarning: Can't initialize NVML
  warnings.warn("Can't initialize NVML")
/home/gbike/anaconda3/envs/textgen2/lib/python3.10/site-packages/torch/cuda/__init__.py:740: UserWarning: CUDA initialization: The NVIDIA driver on your system is too old (found version 11070). Please update your GPU driver by downloading and installing a new version from the URL: http://www.nvidia.com/Download/index.aspx Alternatively, go to: https://pytorch.org to install a PyTorch version that has been compiled with your version of the CUDA driver. (Triggered internally at ../c10/cuda/CUDAFunctions.cpp:108.)
  return torch._C._cuda_getDeviceCount() if nvml_count < 0 else nvml_count
/home/gbike/anaconda3/envs/textgen2/lib/python3.10/site-packages/bitsandbytes/cextension.py:34: UserWarning: The installed version of bitsandbytes was compiled without GPU support. 8-bit optimizers, 8-bit multiplication, and GPU quantization are unavailable.
  warn("The installed version of bitsandbytes was compiled without GPU support. "
/home/gbike/anaconda3/envs/textgen2/lib/python3.10/site-packages/bitsandbytes/libbitsandbytes_cpu.so: undefined symbol: cadam32bit_grad_fp32
2023-10-25 07:55:34 INFO:Loading the extension "gallery"...
Running on local URL:  http://0.0.0.0:7860

To create a public link, set `share=True` in `launch()`.


================================================================================
(textgen2) USER@192-168-0-1:~/AI_test/text-generation-webui$ python server.py --share
================================================================================

2023-10-24 14:34:21 WARNING:The gradio "share link" feature uses a proprietary executable to create a reverse tunnel. Use it with care.
2023-10-24 14:34:21 WARNING:
You are potentially exposing the web UI to the entire internet without any access password.
You can create one with the "--gradio-auth" flag like this:

--gradio-auth username:password

Make sure to replace username:password with your own.
/home/gbike/anaconda3/envs/textgen2/lib/python3.10/site-packages/torch/cuda/__init__.py:611: UserWarning: Can't initialize NVML
  warnings.warn("Can't initialize NVML")
/home/gbike/anaconda3/envs/textgen2/lib/python3.10/site-packages/torch/cuda/__init__.py:740: UserWarning: CUDA initialization: The NVIDIA driver on your system is too old (found version 11070). Please update your GPU driver by downloading and installing a new version from the URL: http://www.nvidia.com/Download/index.aspx Alternatively, go to: https://pytorch.org to install a PyTorch version that has been compiled with your version of the CUDA driver. (Triggered internally at ../c10/cuda/CUDAFunctions.cpp:108.)
  return torch._C._cuda_getDeviceCount() if nvml_count < 0 else nvml_count
/home/gbike/anaconda3/envs/textgen2/lib/python3.10/site-packages/bitsandbytes/cextension.py:34: UserWarning: The installed version of bitsandbytes was compiled without GPU support. 8-bit optimizers, 8-bit multiplication, and GPU quantization are unavailable.
  warn("The installed version of bitsandbytes was compiled without GPU support. "
/home/gbike/anaconda3/envs/textgen2/lib/python3.10/site-packages/bitsandbytes/libbitsandbytes_cpu.so: undefined symbol: cadam32bit_grad_fp32
2023-10-24 14:34:24 INFO:Loading the extension "gallery"...
Running on local URL:  http://127.0.0.1:7860
Running on public URL: https://0c1cf9a498bc4dcff0.gradio.live

This share link expires in 72 hours. For free permanent hosting and GPU upgrades, run `gradio deploy` from Terminal to deploy to Spaces (https://huggingface.co/spaces)

Downloading the model to models/TheBloke_Llama-2-13B-Chat-fp16
100%|███████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████| 4.77k /4.77k  32.0MiB/s
100%|███████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████| 587   /587    6.50MiB/s
100%|███████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████| 132   /132    1.60MiB/s
100%|████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████| 33.4k /33.4k  146MiB/s
100%|███████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████| 411   /411    4.58MiB/s
100%|███████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████| 1.84M /1.84M  1.88MiB/s
100%|███████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████| 500k  /500k   48.4MiB/s
100%|███████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████| 727   /727    6.95MiB/s
100%|███████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████| 6.18G /6.18G  20.6MiB/s
100%|███████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████| 9.90G /9.90G  20.9MiB/s
100%|███████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████| 9.95G /9.95G  20.3MiB/s
 97%|█████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████▉     | 9.63G /9.95G  20.2MiB/s
100%|██████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████▉| 9.95G /9.95G  20.9MiB/s

================================================================================

[Web browser]

http://127.0.0.1:7860
(or)
http://192.168.0.1:7860
(or)
https://0c1cf9a498bc4dcff0.gradio.live/

[Menu tab] Model --> [Right side] Download model or LoRA --> [Type] TheBloke/Llama-2-13B-Chat-fp16 --> [Click] Download
(or)
[Menu tab] Model --> [Right side] Download model or LoRA --> [Type] TheBloke/Llama-2-7b-chat-fp16 --> [Click] Download
(or)
[Menu tab] Model --> [Right side] Download model or LoRA --> [Type] microsoft/DialoGPT-large --> [Click] Download (TEST)

[Left side] Refresh --> Model --> [Select] TheBloke_Llama-2-13B-Chat-fp16 --> [Click] Load --> [Wait few minutes]

[Menu tab] Session --> Mode --> [Select] chat --> [Click] Apply and restart

[Menu tab] Parameters --> [Right side] Chat parameters --> max_new_tokens --> [Mouse] 4096 --> [Right side] Main parameters

[Menu tab] Text generation --> [Input] Do you know Jesus? --> [Click] Generate

The settings for TheBloke_Llama-2-13B-Chat-fp16 have been updated.

Click on "Load" to load it.

[Menu tab] --> [Right side] --> [Check] cpu (if there is no GPU) 

================================================================================

[Issue] https://github.com/THUDM/ChatGLM2-6B/issues/429

/home/gbike/anaconda3/envs/textgen2/lib/python3.10/site-packages/gradio/components/dropdown.py:231: UserWarning: The value passed into gr.Dropdown() is not in the list of choices. Please update the list of choices to include: llama or set allow_custom_value=True.█████████████████████████████████████████████████████████████████████████████████████████▉| 9.95G /9.95G  20.9MiB/s
  warnings.warn(
2023-10-25 07:40:13 INFO:Loading TheBloke_Llama-2-13B-Chat-fp16...
Loading checkpoint shards:  33%|██████████████████████████████████████████▎                                                                                    | 1/3 [00:38<01:17, 38.67s/it]Killed
Killed
(textgen2) USER@192-168-0-1:~/AI_test/text-generation-webui$ du -sh
25G     .
(textgen2) USER@192-168-0-1:~/AI_test/text-generation-webui$

[Reason] Unsufficient memory size
When I look at the memory usage, it is maxed out until it gives up. (I only have 16GB of CPU Ram)

    PID USER      PR  NI    VIRT    RES    SHR S  %CPU  %MEM     TIME+ COMMAND
   1745 USER      20   0   14.3g  10.7g 149888 S  15.0  96.2   0:17.53 python

================================================================================
[NVIDIA GPU to use CUDA]
================================================================================
https://github.com/boanuge/sample-ai-keras-for-image-nlp-etc/blob/main/readme.txt
