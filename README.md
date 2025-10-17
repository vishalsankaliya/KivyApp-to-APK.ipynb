!pip install buildozer
     

!pip install cython==0.29.19
     

!sudo apt-get install -y \
    python3-pip \
    build-essential \
    git \
    python3 \
    python3-dev \
    ffmpeg \
    libsdl2-dev \
    libsdl2-image-dev \
    libsdl2-mixer-dev \
    libsdl2-ttf-dev \
    libportmidi-dev \
    libswscale-dev \
    libavformat-dev \
    libavcodec-dev \
    zlib1g-dev
     

!sudo apt-get install -y \
    libgstreamer1.0 \
    gstreamer1.0-plugins-base \
    gstreamer1.0-plugins-good
     

!sudo apt-get install build-essential libsqlite3-dev sqlite3 bzip2 libbz2-dev zlib1g-dev libssl-dev openssl libgdbm-dev libgdbm-compat-dev liblzma-dev libreadline-dev libncursesw5-dev libffi-dev uuid-dev libffi6
     

!sudo apt-get install libffi-dev
     

!buildozer init
     

!buildozer -v android debug
     

!buildozer android clean


# Command failed: /usr/bin/python3 -m pythonforandroid.toolchain create --dist_name=myapp --bootstrap=sdl2 --requirements=python3,kivy --arch armeabi-v7a --copy-libs --color=always --storage-dir="/content/.buildozer/android/platform/build-armeabi-v7a" --ndk-api=21
# ENVIRONMENT:
#     CUDNN_VERSION = '8.0.4.30'
#     PYDEVD_USE_FRAME_EVAL = 'NO'
#     LD_LIBRARY_PATH = '/usr/local/nvidia/lib:/usr/local/nvidia/lib64'
#     CLOUDSDK_PYTHON = 'python3'
#     LANG = 'en_US.UTF-8'
#     HOSTNAME = '16a6415b7369'
#     OLDPWD = '/'
#     CLOUDSDK_CONFIG = '/content/.config'
#     NVIDIA_VISIBLE_DEVICES = 'all'
#     DATALAB_SETTINGS_OVERRIDES = '{"kernelManagerProxyPort":6000,"kernelManagerProxyHost":"172.28.0.3","jupyterArgs":["--ip=\\"172.28.0.2\\""],"debugAdapterMultiplexerPath":"/usr/local/bin/dap_multiplexer"}'
#     ENV = '/root/.bashrc'
#     PAGER = 'cat'
#     NCCL_VERSION = '2.7.8'
#     TF_FORCE_GPU_ALLOW_GROWTH = 'true'
#     JPY_PARENT_PID = '47'
#     NO_GCE_CHECK = 'True'
#     PWD = '/content'
#     HOME = '/root'
#     LAST_FORCED_REBUILD = '20210504'
#     CLICOLOR = '1'
#     DEBIAN_FRONTEND = 'noninteractive'
#     LIBRARY_PATH = '/usr/local/cuda/lib64/stubs'
#     GCE_METADATA_TIMEOUT = '0'
#     GLIBCPP_FORCE_NEW = '1'
#     TBE_CREDS_ADDR = '172.28.0.1:8008'
#     TERM = 'xterm-color'
#     SHELL = '/bin/bash'
#     GCS_READ_CACHE_BLOCK_SIZE_MB = '16'
#     PYTHONWARNINGS = 'ignore:::pip._internal.cli.base_command'
#     MPLBACKEND = 'module://ipykernel.pylab.backend_inline'
#     CUDA_VERSION = '11.0.3'
#     NVIDIA_DRIVER_CAPABILITIES = 'compute,utility'
#     SHLVL = '1'
#     PYTHONPATH = '/env/python'
#     NVIDIA_REQUIRE_CUDA = ('cuda>=11.0 brand=tesla,driver>=418,driver<419 '
 'brand=tesla,driver>=440,driver<441 brand=tesla,driver>=450,driver<451')
#     COLAB_GPU = '0'
#     GLIBCXX_FORCE_NEW = '1'
#     PATH = '/root/.buildozer/android/platform/apache-ant-1.9.4/bin:/usr/local/nvidia/bin:/usr/local/cuda/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin:/tools/node/bin:/tools/google-cloud-sdk/bin:/opt/bin'
#     LD_PRELOAD = '/usr/lib/x86_64-linux-gnu/libtcmalloc.so.4'
#     GIT_PAGER = 'cat'
#     _ = '/usr/local/bin/buildozer'
#     PACKAGES_PATH = '/root/.buildozer/android/packages'
#     ANDROIDSDK = '/root/.buildozer/android/platform/android-sdk'
#     ANDROIDNDK = '/root/.buildozer/android/platform/android-ndk-r19c'
#     ANDROIDAPI = '27'
#     ANDROIDMINAPI = '21'
# 
# Buildozer failed to execute the last command
# The error might be hidden in the log above this error
# Please read the full log, and search for it before
# raising an issue with buildozer itself.
# In case of a bug report, please add a full log with log_level = 2
@BootsManOut
BootsManOut commented on Aug 5, 2021 • 
Excuse me, how can I use this file to create a work flow from it please?
Can I just copy and paste the raw version of it?

@kaustubhgupta
Author
kaustubhgupta commented on Aug 5, 2021 • 
Excuse me, how can I use this file to create a work flow from it please?
Can I just copy and paste the raw version of it?

On the top of the file, you have the option to open the file in Colab.

Qs: By workflow you mean GitHub workflow or general workflow?

@BootsManOut
BootsManOut commented on Aug 7, 2021 • 
Hi yes I mean Github Workflow.

For now I don't know how to import my own python main file to the google collab file...

@BootsManOut
BootsManOut commented on Aug 18, 2021
May I just ask where I have to place the python file that I want to package into APK so that your script automatically uses it when I run it?

@kaustubhgupta
Author
kaustubhgupta commented on Aug 18, 2021
@BootsManOut

Hi yes I mean Github Workflow.

For now I don't know how to import my own python main file to the google collab file...

For this, you can refer to already existing solution by KivyMD devs: https://github.com/ArtemSBulgakov/buildozer-action

May I just ask where I have to place the python file that I want to package into APK so that your script automatically uses it when I run it?

As soon as you open a Google Colab instance, you will get the option to upload your files in that particular session.

PS: Refer this article for details: https://towardsdatascience.com/3-ways-to-convert-python-app-into-apk-77f4c9cd55af

@Rafawastaken
Rafawastaken commented on Dec 18, 2022
Excuse me, how can I use this file to create a work flow from it please? Can I just copy and paste the raw version of it?

just copy and past it

@richie-amo
richie-amo commented on Jun 24, 2023
IN THE 5 CODE i get this error:
Reading package lists... Done
Building dependency tree
Reading state information... Done
E: Unable to locate package libffi6

helppp mee!!1 pliss

@TaruSama
TaruSama commented on Jul 6, 2023
Change the 6 to 7 at the end of the command

ghost commented on Jul 24, 2023 • 
Hi

In my code i use tkinter button to call some sounds in mp3 format, stored in a sound folder, which i call inside my programme using the path of the sound folder (C:/users/...). How can i make it still work ? When i execute the apk converter on google collab i got :

TDERR:

Command failed: ['/usr/bin/python3', '-m', 'pythonforandroid.toolchain', 'create', '--dist_name=myapp', '--bootstrap=sdl2', '--requirements=python3,kivy=2.0.0,kivymd,pillow', '--arch=arm64-v8a', '--arch=armeabi-v7a', '--copy-libs', '--color=always', '--storage-dir=/content/.buildozer/android/platform/build-arm64-v8a_armeabi-v7a', '--ndk-api=21', '--ignore-setup-py', '--debug']
ENVIRONMENT:
SHELL = '/bin/bash'
NV_LIBCUBLAS_VERSION = '11.11.3.6-1'
NVIDIA_VISIBLE_DEVICES = 'all'
COLAB_JUPYTER_TRANSPORT = 'ipc'
NV_NVML_DEV_VERSION = '11.8.86-1'
NV_CUDNN_PACKAGE_NAME = 'libcudnn8'
CGROUP_MEMORY_EVENTS = '/sys/fs/cgroup/memory.events /var/colab/cgroup/jupyter-children/memory.events'
NV_LIBNCCL_DEV_PACKAGE = 'libnccl-dev=2.15.5-1+cuda11.8'
NV_LIBNCCL_DEV_PACKAGE_VERSION = '2.15.5-1'
VM_GCE_METADATA_HOST = '169.254.169.253'
HOSTNAME = 'e216d1b65ac4'
TBE_RUNTIME_ADDR = '172.28.0.1:8011'
GCE_METADATA_TIMEOUT = '3'
NVIDIA_REQUIRE_CUDA = ('cuda>=11.8 brand=tesla,driver>=450,driver<451 '
'brand=tesla,driver>=470,driver<471 brand=unknown,driver>=470,driver<471 '
'brand=nvidia,driver>=470,driver<471 brand=nvidiartx,driver>=470,driver<471 '
'brand=geforce,driver>=470,driver<471 brand=geforcertx,driver>=470,driver<471 '
'brand=quadro,driver>=470,driver<471 brand=quadrortx,driver>=470,driver<471 '
'brand=titan,driver>=470,driver<471 brand=titanrtx,driver>=470,driver<471 '
'brand=tesla,driver>=510,driver<511 brand=unknown,driver>=510,driver<511 '
'brand=nvidia,driver>=510,driver<511 brand=nvidiartx,driver>=510,driver<511 '
'brand=geforce,driver>=510,driver<511 brand=geforcertx,driver>=510,driver<511 '
'brand=quadro,driver>=510,driver<511 brand=quadrortx,driver>=510,driver<511 '
'brand=titan,driver>=510,driver<511 brand=titanrtx,driver>=510,driver<511 '
'brand=tesla,driver>=515,driver<516 brand=unknown,driver>=515,driver<516 '
'brand=nvidia,driver>=515,driver<516 brand=nvidiartx,driver>=515,driver<516 '
'brand=geforce,driver>=515,driver<516 brand=geforcertx,driver>=515,driver<516 '
'brand=quadro,driver>=515,driver<516 brand=quadrortx,driver>=515,driver<516 '
'brand=titan,driver>=515,driver<516 brand=titanrtx,driver>=515,driver<516')

NV_LIBCUBLAS_DEV_PACKAGE = 'libcublas-dev-11-8=11.11.3.6-1'
NV_NVTX_VERSION = '11.8.86-1'
COLAB_JUPYTER_IP = '172.28.0.12'
NV_CUDA_CUDART_DEV_VERSION = '11.8.89-1'
NV_LIBCUSPARSE_VERSION = '11.7.5.86-1'
COLAB_LANGUAGE_SERVER_PROXY_ROOT_URL = 'http://172.28.0.1:8013/'
NV_LIBNPP_VERSION = '11.8.0.86-1'
NCCL_VERSION = '2.15.5-1'
KMP_LISTEN_PORT = '6000'
TF_FORCE_GPU_ALLOW_GROWTH = 'true'
ENV = '/root/.bashrc'
PWD = '/content'
TBE_EPHEM_CREDS_ADDR = '172.28.0.1:8009'
COLAB_LANGUAGE_SERVER_PROXY_REQUEST_TIMEOUT = '30s'
TBE_CREDS_ADDR = '172.28.0.1:8008'
NV_CUDNN_PACKAGE = 'libcudnn8=8.9.0.131-1+cuda11.8'
NVIDIA_DRIVER_CAPABILITIES = 'compute,utility'
COLAB_JUPYTER_TOKEN = ''
LAST_FORCED_REBUILD = '20230711'
NV_NVPROF_DEV_PACKAGE = 'cuda-nvprof-11-8=11.8.87-1'
NV_LIBNPP_PACKAGE = 'libnpp-11-8=11.8.0.86-1'
NV_LIBNCCL_DEV_PACKAGE_NAME = 'libnccl-dev'
TCLLIBPATH = '/usr/share/tcltk/tcllib1.20'
NV_LIBCUBLAS_DEV_VERSION = '11.11.3.6-1'
COLAB_KERNEL_MANAGER_PROXY_HOST = '172.28.0.12'
NVIDIA_PRODUCT_NAME = 'CUDA'
NV_LIBCUBLAS_DEV_PACKAGE_NAME = 'libcublas-dev-11-8'
USE_AUTH_EPHEM = '1'
NV_CUDA_CUDART_VERSION = '11.8.89-1'
HOME = '/root'
LANG = 'en_US.UTF-8'
CUDA_VERSION = '11.8.0'
CLOUDSDK_CONFIG = '/content/.config'
NV_LIBCUBLAS_PACKAGE = 'libcublas-11-8=11.11.3.6-1'
NV_CUDA_NSIGHT_COMPUTE_DEV_PACKAGE = 'cuda-nsight-compute-11-8=11.8.0-1'
COLAB_RELEASE_TAG = 'release-colab-20230720-060118-RC00'
PYDEVD_USE_FRAME_EVAL = 'NO'
KMP_TARGET_PORT = '9000'
CLICOLOR = '1'
KMP_EXTRA_ARGS = ('--logtostderr --listen_host=172.28.0.12 --target_host=172.28.0.12 '
'--tunnel_background_save_url=https://colab.research.google.com/tun/m/cc48301118ce562b961b3c22d803539adc1e0c19/m-s-1b4nw0ncel4dn '
'--tunnel_background_save_delay=10s '
'--tunnel_periodic_background_save_frequency=30m0s '
'--enable_output_coalescing=true --output_coalescing_required=true')

NV_LIBNPP_DEV_PACKAGE = 'libnpp-dev-11-8=11.8.0.86-1'
NV_LIBCUBLAS_PACKAGE_NAME = 'libcublas-11-8'
COLAB_KERNEL_MANAGER_PROXY_PORT = '6000'
CLOUDSDK_PYTHON = 'python3'
NV_LIBNPP_DEV_VERSION = '11.8.0.86-1'
ENABLE_DIRECTORYPREFETCHER = '1'
NO_GCE_CHECK = 'False'
JPY_PARENT_PID = '78'
PYTHONPATH = '/env/python'
TERM = 'xterm-color'
NV_LIBCUSPARSE_DEV_VERSION = '11.7.5.86-1'
GIT_PAGER = 'cat'
LIBRARY_PATH = '/usr/local/cuda/lib64/stubs'
NV_CUDNN_VERSION = '8.9.0.131'
SHLVL = '0'
PAGER = 'cat'
COLAB_LANGUAGE_SERVER_PROXY = '/usr/colab/bin/language_service'
NV_CUDA_LIB_VERSION = '11.8.0-1'
NVARCH = 'x86_64'
NV_CUDNN_PACKAGE_DEV = 'libcudnn8-dev=8.9.0.131-1+cuda11.8'
NV_CUDA_COMPAT_PACKAGE = 'cuda-compat-11-8'
MPLBACKEND = 'module://ipykernel.pylab.backend_inline'
NV_LIBNCCL_PACKAGE = 'libnccl2=2.15.5-1+cuda11.8'
LD_LIBRARY_PATH = '/usr/local/nvidia/lib:/usr/local/nvidia/lib64'
COLAB_GPU = ''
GCS_READ_CACHE_BLOCK_SIZE_MB = '16'
NV_CUDA_NSIGHT_COMPUTE_VERSION = '11.8.0-1'
NV_NVPROF_VERSION = '11.8.87-1'
COLAB_FILE_HANDLER_ADDR = 'localhost:3453'
PATH = '/root/.buildozer/android/platform/apache-ant-1.9.4/bin:/opt/bin:/usr/local/nvidia/bin:/usr/local/cuda/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin:/tools/node/bin:/tools/google-cloud-sdk/bin'
NV_LIBNCCL_PACKAGE_NAME = 'libnccl2'
COLAB_DEBUG_ADAPTER_MUX_PATH = '/usr/local/bin/dap_multiplexer'
NV_LIBNCCL_PACKAGE_VERSION = '2.15.5-1'
PYTHONWARNINGS = 'ignore:::pip._internal.cli.base_command'
DEBIAN_FRONTEND = 'noninteractive'
COLAB_BACKEND_VERSION = 'next'
OLDPWD = '/'
_ = '/usr/local/bin/buildozer'
PACKAGES_PATH = '/root/.buildozer/android/packages'
ANDROIDSDK = '/root/.buildozer/android/platform/android-sdk'
ANDROIDNDK = '/root/.buildozer/android/platform/android-ndk-r25b'
ANDROIDAPI = '31'
ANDROIDMINAPI = '21'
Buildozer failed to execute the last command
The error might be hidden in the log above this error
Please read the full log, and search for it before
raising an issue with buildozer itself.
In case of a bug report, please add a full log with log_level = 2
@domm-hub
domm-hub commented on Aug 14, 2023
this is bad the same error you have , i also have it

@vikashnitk
vikashnitk commented on Nov 14, 2023 • 
Just follow the instructions given here https://buildozer.readthedocs.io/en/latest/installation.html in Google colab. It will work perfectly without any error.

@vikashnitk
vikashnitk commented on Nov 14, 2023
Just follow the instructions given here https://buildozer.readthedocs.io/en/latest/installation.html in Google colab. It will work perfectly without any error.

!pip3 install --upgrade buildozer
!sudo apt update
!sudo apt install -y git zip unzip openjdk-17-jdk python3-pip autoconf libtool pkg-config zlib1g-dev libncurses5-dev libncursesw5-dev libtinfo5 cmake libffi-dev libssl-dev
!pip3 install --user --upgrade Cython==0.29.33 virtualenv # the --user should be removed if you do this in a venv
!export PATH=$PATH:~/.local/bin/
!buildozer init
!buildozer -v android debug

@darksward27
darksward27 commented on Mar 10, 2024
ImportError: dlopen failed: "/data/data/org.test.myapp/files/app/_python_bundle/site-packages/materialyoucolor/quantize/celebi.so" is for EM_X86_64 (62) instead of EM_AARCH64 (183)

encountered this error after building it and running it any solutions?

@soroush-babaei
soroush-babaei commented on Sep 15, 2024 • 
when i want debug my projector it give me this error `# Command failed: ['/usr/bin/python3', '-m', 'pythonforandroid.toolchain', 'create', '--dist_name=myapp', '--bootstrap=sdl2', '--requirements=python3,kivy==2.3.0,mendeleev==0.17.0', '--arch=arm64-v8a', '--arch=armeabi-v7a', '--copy-libs', '--color=always', '--storage-dir=/content/.buildozer/android/platform/build-arm64-v8a_armeabi-v7a', '--ndk-api=21', '--ignore-setup-py', '--debug']

ENVIRONMENT:
SHELL = '/bin/bash'
NV_LIBCUBLAS_VERSION = '12.2.5.6-1'
NVIDIA_VISIBLE_DEVICES = 'all'
COLAB_JUPYTER_TRANSPORT = 'ipc'
NV_NVML_DEV_VERSION = '12.2.140-1'
NV_CUDNN_PACKAGE_NAME = 'libcudnn8'
CGROUP_MEMORY_EVENTS = '/sys/fs/cgroup/memory.events /var/colab/cgroup/jupyter-children/memory.events'
NV_LIBNCCL_DEV_PACKAGE = 'libnccl-dev=2.19.3-1+cuda12.2'
NV_LIBNCCL_DEV_PACKAGE_VERSION = '2.19.3-1'
VM_GCE_METADATA_HOST = '169.254.169.253'
HOSTNAME = '2b190805bfcb'
LANGUAGE = 'en_US'
TBE_RUNTIME_ADDR = '172.28.0.1:8011'
COLAB_TPU_1VM = ''
GCE_METADATA_TIMEOUT = '3'
NVIDIA_REQUIRE_CUDA = ('cuda>=12.2 brand=tesla,driver>=470,driver<471 '
'brand=unknown,driver>=470,driver<471 brand=nvidia,driver>=470,driver<471 '
'brand=nvidiartx,driver>=470,driver<471 brand=geforce,driver>=470,driver<471 '
'brand=geforcertx,driver>=470,driver<471 brand=quadro,driver>=470,driver<471 '
'brand=quadrortx,driver>=470,driver<471 brand=titan,driver>=470,driver<471 '
'brand=titanrtx,driver>=470,driver<471 brand=tesla,driver>=525,driver<526 '
'brand=unknown,driver>=525,driver<526 brand=nvidia,driver>=525,driver<526 '
'brand=nvidiartx,driver>=525,driver<526 brand=geforce,driver>=525,driver<526 '
'brand=geforcertx,driver>=525,driver<526 brand=quadro,driver>=525,driver<526 '
'brand=quadrortx,driver>=525,driver<526 brand=titan,driver>=525,driver<526 '
'brand=titanrtx,driver>=525,driver<526')

NV_LIBCUBLAS_DEV_PACKAGE = 'libcublas-dev-12-2=12.2.5.6-1'
NV_NVTX_VERSION = '12.2.140-1'
COLAB_JUPYTER_IP = '172.28.0.12'
NV_CUDA_CUDART_DEV_VERSION = '12.2.140-1'
NV_LIBCUSPARSE_VERSION = '12.1.2.141-1'
COLAB_LANGUAGE_SERVER_PROXY_ROOT_URL = 'http://172.28.0.1:8013/'
NV_LIBNPP_VERSION = '12.2.1.4-1'
NCCL_VERSION = '2.19.3-1'
KMP_LISTEN_PORT = '6000'
TF_FORCE_GPU_ALLOW_GROWTH = 'true'
ENV = '/root/.bashrc'
PWD = '/content'
COLAB_LANGUAGE_SERVER_PROXY_REQUEST_TIMEOUT = '30s'
TBE_EPHEM_CREDS_ADDR = '172.28.0.1:8009'
TBE_CREDS_ADDR = '172.28.0.1:8008'
NV_CUDNN_PACKAGE = 'libcudnn8=8.9.6.50-1+cuda12.2'
NVIDIA_DRIVER_CAPABILITIES = 'compute,utility'
COLAB_JUPYTER_TOKEN = ''
LAST_FORCED_REBUILD = '20240627'
NV_NVPROF_DEV_PACKAGE = 'cuda-nvprof-12-2=12.2.142-1'
NV_LIBNPP_PACKAGE = 'libnpp-12-2=12.2.1.4-1'
NV_LIBNCCL_DEV_PACKAGE_NAME = 'libnccl-dev'
TCLLIBPATH = '/usr/share/tcltk/tcllib1.20'
NV_LIBCUBLAS_DEV_VERSION = '12.2.5.6-1'
COLAB_KERNEL_MANAGER_PROXY_HOST = '172.28.0.12'
NVIDIA_PRODUCT_NAME = 'CUDA'
NV_LIBCUBLAS_DEV_PACKAGE_NAME = 'libcublas-dev-12-2'
USE_AUTH_EPHEM = '1'
NV_CUDA_CUDART_VERSION = '12.2.140-1'
COLAB_WARMUP_DEFAULTS = '1'
HOME = '/root'
LANG = 'en_US.UTF-8'
COLUMNS = '100'
CUDA_VERSION = '12.2.2'
CLOUDSDK_CONFIG = '/content/.config'
NV_LIBCUBLAS_PACKAGE = 'libcublas-12-2=12.2.5.6-1'
NV_CUDA_NSIGHT_COMPUTE_DEV_PACKAGE = 'cuda-nsight-compute-12-2=12.2.2-1'
COLAB_RELEASE_TAG = 'release-colab_20240912-060302_RC00'
PYDEVD_USE_FRAME_EVAL = 'NO'
KMP_TARGET_PORT = '9000'
CLICOLOR = '1'
KMP_EXTRA_ARGS = ('--logtostderr --listen_host=172.28.0.12 --target_host=172.28.0.12 '
'--tunnel_background_save_url=https://colab.research.google.com/tun/m/cc48301118ce562b961b3c22d803539adc1e0c19/m-s-2pkx37g53jqx7 '
'--tunnel_background_save_delay=10s '
'--tunnel_periodic_background_save_frequency=30m0s '
'--enable_output_coalescing=true --output_coalescing_required=true '
'--log_code_content')

NV_LIBNPP_DEV_PACKAGE = 'libnpp-dev-12-2=12.2.1.4-1'
COLAB_LANGUAGE_SERVER_PROXY_LSP_DIRS = '/datalab/web/pyright/typeshed-fallback/stdlib,/usr/local/lib/python3.10/dist-packages'
NV_LIBCUBLAS_PACKAGE_NAME = 'libcublas-12-2'
COLAB_KERNEL_MANAGER_PROXY_PORT = '6000'
CLOUDSDK_PYTHON = 'python3'
NV_LIBNPP_DEV_VERSION = '12.2.1.4-1'
ENABLE_DIRECTORYPREFETCHER = '1'
NO_GCE_CHECK = 'False'
JPY_PARENT_PID = '95'
PYTHONPATH = '/env/python'
TERM = 'xterm-color'
NV_LIBCUSPARSE_DEV_VERSION = '12.1.2.141-1'
GIT_PAGER = 'cat'
LIBRARY_PATH = '/usr/local/cuda/lib64/stubs'
NV_CUDNN_VERSION = '8.9.6.50'
SHLVL = '0'
PAGER = 'cat'
COLAB_LANGUAGE_SERVER_PROXY = '/usr/colab/bin/language_service'
NV_CUDA_LIB_VERSION = '12.2.2-1'
NVARCH = 'x86_64'
NV_CUDNN_PACKAGE_DEV = 'libcudnn8-dev=8.9.6.50-1+cuda12.2'
NV_CUDA_COMPAT_PACKAGE = 'cuda-compat-12-2'
MPLBACKEND = 'module://ipykernel.pylab.backend_inline'
NV_LIBNCCL_PACKAGE = 'libnccl2=2.19.3-1+cuda12.2'
LD_LIBRARY_PATH = '/usr/local/nvidia/lib:/usr/local/nvidia/lib64'
COLAB_GPU = ''
GCS_READ_CACHE_BLOCK_SIZE_MB = '16'
NV_CUDA_NSIGHT_COMPUTE_VERSION = '12.2.2-1'
NV_NVPROF_VERSION = '12.2.142-1'
LC_ALL = 'en_US.UTF-8'
COLAB_FILE_HANDLER_ADDR = 'localhost:3453'
PATH = '/root/.buildozer/android/platform/apache-ant-1.9.4/bin:/opt/bin:/usr/local/nvidia/bin:/usr/local/cuda/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin:/tools/node/bin:/tools/google-cloud-sdk/bin'
NV_LIBNCCL_PACKAGE_NAME = 'libnccl2'
COLAB_DEBUG_ADAPTER_MUX_PATH = '/usr/local/bin/dap_multiplexer'
NV_LIBNCCL_PACKAGE_VERSION = '2.19.3-1'
PYTHONWARNINGS = 'ignore:::pip._internal.cli.base_command'
DEBIAN_FRONTEND = 'noninteractive'
COLAB_BACKEND_VERSION = 'next'
OLDPWD = '/'
_ = '/usr/local/bin/buildozer'
PACKAGES_PATH = '/root/.buildozer/android/packages'
ANDROIDSDK = '/root/.buildozer/android/platform/android-sdk'
ANDROIDNDK = '/root/.buildozer/android/platform/android-ndk-r25b'
ANDROIDAPI = '31'
ANDROIDMINAPI = '21'
Buildozer failed to execute the last command
The error might be hidden in the log above this error
Please read the full log, and search for it before
raising an issue with buildozer itself.
In case of a bug report, please add a full log with log_level = 2`
@ParsapythonLv
ParsapythonLv commented on Jan 23
i get log error like other, what should i do?

@vishalsankaliya
Comme
     


     
