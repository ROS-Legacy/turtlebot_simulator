FROM osrf/ros:kinetic-desktop-full-xenial

RUN apt-get update && \
    apt-get install -y ros-kinetic-turtlebot-simulator && \
    rm -rf /var/lib/apt/lists/*

CMD ["roscore"]
