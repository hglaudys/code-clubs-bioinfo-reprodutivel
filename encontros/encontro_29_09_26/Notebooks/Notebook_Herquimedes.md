## 18/09/2026
### Criação do Codespace e configuração ambiente virtual

conda init bash
conda create --name ambiente_virtual_buscador_ori

Ao tentar ativar o ambiente virtual obtive o seguinte erro
```
conda activate ambiente_virtual_buscador_ori

CondaError: Run 'conda init' before 'conda activate'
```

O erro foi solucionado com os seguintes comandos:
```
conda init bash
source ~/.bashrc
```

Explicação em: https://www.ansiblepilot.com/articles/solving-the-conda-activation-error

pip install biopython
