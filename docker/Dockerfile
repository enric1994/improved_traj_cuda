FROM nvidia/cuda:8.0-cudnn7-devel-ubuntu16.04

RUN apt update
RUN apt install -y software-properties-common
RUN add-apt-repository --yes ppa:jeff250/opencv

RUN apt update
RUN apt install -y libopencv-nonfree-dev

RUN apt install -y ffmpeg libopencv-dev libavdevice-dev 


# RUN apt install -y git && git clone https://github.com/enric1994/improved_traj_cuda.git

# RUN cd improved_traj_cuda && make
