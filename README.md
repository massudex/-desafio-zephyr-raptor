# Desafio ZephyrOS + QEMU

Projeto de sistema embarcado simulado utilizando ZephyrOS no ambiente de virtualização QEMU.

## Como executar

1. Pré-requisitos:
   - Zephyr SDK instalado
   - QEMU
   - Ambiente configurado conforme [Zephyr Docs](https://docs.zephyrproject.org/latest/getting_started/index.html)

2. Clone este repositório:
   ```bash
   git clone https://github.com/massudex/desafio-zephyr-raptor.git
   ```

3. Compile e execute:
   ```bash
   west build -b qemu_x86 ./src
   west build -t run
   ```

## Estrutura do Projeto
- `src/`: Código fonte do projeto
- `docs/`: Documentação e relatório técnico
- `CMakeLists.txt`: Configuração de build
- `prj.conf`: Configurações do projeto

## Autor
[Gabriel Alves Massuda](https://github.com/massudex)
