FROM nvidia/cuda:6.5-devel-ubuntu14.04

RUN apt update
RUN apt install -y software-properties-common
RUN add-apt-repository --yes ppa:philip5/extra

RUN apt update
RUN apt install -y libopencv-nonfree-dev
#2.4.8+dfsg1-2ubuntu1xqms1~trusty1

RUN add-apt-repository --yes ppa:mc3man/trusty-media
RUN apt update
RUN apt install -y ffmpeg libopencv-dev libavdevice-dev 


# RUN apt install -y git && git clone https://github.com/enric1994/improved_traj_cuda.git

# RUN cd improved_traj_cuda && make
