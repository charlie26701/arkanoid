FROM paiatech/mlgame:10.5.1-slim

# 安裝基本開發工具
RUN apt-get update && apt-get install -y \
    git \
    curl \
    wget \
    vim \
    fontconfig \
    libfontconfig1 \
    libx11-dev \
    libxext-dev \
    libxrender-dev \
    libxinerama-dev \
    libxi-dev \
    x11-apps \
    x11-utils \
    x11-xserver-utils \
    libsdl2-dev \
    libsdl2-image-dev \
    libsdl2-mixer-dev \
    libsdl2-ttf-dev \
    && rm -rf /var/lib/apt/lists/*

# 設置工作目錄
WORKDIR /workspace

# 設置預設命令
CMD ["bash"] 