Etapas para gerar o executável:

    Instale o PyInstaller:
        No terminal, execute: pip install pyinstaller

    Navegue até o diretório do seu script Python:
        Utilize o comando cd para ir ao diretório que contém o script.

    Crie o executável:

        Execute o seguinte comando, substituindo "script.py" pelo nome do seu script:

        pyinstaller --onefile script.py

Opções adicionais:

    --onefile: cria um único arquivo executável.
    --windowed: executa o programa em uma janela.
    Após a execução do comando, um diretório chamado dist será criado
