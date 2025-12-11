# Samsung PIT Viewer

A tool to view Samsung PIT (Partition Information Table) files.

## Compilation / Compilação

### Prerequisites / Pré-requisitos

- **C compiler**: `clang` or `gcc`
- **Make**: Build automation tool

**English:**
- Linux/macOS: Usually pre-installed or available via package manager
- Windows: Install via MinGW, Cygwin, or WSL

**Português:**
- Linux/macOS: Geralmente pré-instalado ou disponível via gerenciador de pacotes
- Windows: Instalar via MinGW, Cygwin, ou WSL

### Building / Compilando

**English:**

1. Clone the repository:
```bash
git clone https://github.com/m52xq/SamsungPITViewer.git
cd SamsungPITViewer
```

2. Compile the project:
```bash
make
```

This will generate the `spv` executable.

**Português:**

1. Clone o repositório:
```bash
git clone https://github.com/m52xq/SamsungPITViewer.git
cd SamsungPITViewer
```

2. Compile o projeto:
```bash
make
```

Isso irá gerar o executável `spv`.

### Using a different compiler / Usando um compilador diferente

**English:**

If you prefer to use `gcc` instead of `clang`:
```bash
make CC=gcc
```

**Português:**

Se preferir usar `gcc` ao invés de `clang`:
```bash
make CC=gcc
```

## Usage / Uso

**English:**
```bash
./spv [-his] <pit file>
```

Options:
- `-h`: Print PIT header info
- `-i`: Print PIT partitions info
- `-s`: Print Samsung signer info

Example:
```bash
./spv -his my_device.pit
```

**Português:**
```bash
./spv [-his] <arquivo pit>
```

Opções:
- `-h`: Imprimir informações do cabeçalho PIT
- `-i`: Imprimir informações das partições PIT
- `-s`: Imprimir informações do assinador Samsung

Exemplo:
```bash
./spv -his meu_dispositivo.pit
```

## License / Licença

@BlackMesa123, 2024
