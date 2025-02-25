# Fine-Tuning-Local

- Clone the repository en la carpeta Home
- Abrir la terminal y ejecutar el siguiente comando:

```bash
cd Fine-Tuning-Local
```

- Dar permisos de ejecución al script:

```bash
chmod +x setup-works-python11.sh
```

- Ejecutar el script:

```bash
./setup-works-python11.sh
```

- Una vez finalizado el proceso, ejecutar el siguiente comando:

```bash
source ~/.bashrc
```

- Comprobar que se ha instalado correctamente CUDA:

```bash
nvidia-smi
vcc --version
```

- Si no se ha instalado correctamente, ejecutar el siguiente comando:

```bash
sudo apt-get install nvidia-cuda-toolkit
```

- Si no esta, entrar en el entono virtual:

```bash
source venv/bin/activate
```

- Ejecutar el script de entrenamiento:

```bash
./scripts/train-small-gpu.py
```

