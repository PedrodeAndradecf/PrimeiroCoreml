# Baixa a imagem oficial do Swift
FROM swift:5.9

# Instala dependências adicionais se necessário
RUN apt-get update && apt-get install -y \
    libssl-dev \
    libsqlite3-dev \
    libz-dev \
    curl \
    git \
    && rm -rf /var/lib/apt/lists/*

# Define o diretório de trabalho
WORKDIR /workspace
