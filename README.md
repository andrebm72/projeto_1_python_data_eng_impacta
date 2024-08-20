### PROJETO 01 
#### DECIFRANDO CÓDIGO MORSE

Imagine que você é um agente especial que possui a missão de interceptar mensagens secretas. Por meio da sua rede de informantes você descobre que tais mensagens estão sendo transmitidas por meio de uma frequência de rádio não utilizada em código morse.

<img src="../../imgs/projetos/missao_morse.png" style="max-width:500px; "/>


Sua missão é:
- Interceptar estas mensagens;
- Decodificar, sabendo que as letras estão espaçadas por um espaço;
- Salvar as mensagens em um arquivo em texto claro;
- Salvar o datetime da decodificação da mensagem;

<img src="../../imgs/projetos/morse.png" style="max-width:300px; "/>

Para cumprir sua missão sem levantar suspeitas você deverá realizar a decodificação através de uma ou mais funções que :
- Recebe a mensagem como argumento;
- O "de-para morse" não deve estar hard coded;
- Path do arquivo não deve estar hard coded;
- Messagem deve ser passada através do keyboard.

### Como utilizar:

1. Clone o repositório
```
git clone https://github.com/GCAntunes/projeto_1_python_data_eng_impacta.git
```
2. Entra na pasta do repositório
```
cd projeto_1_python_data_eng_impacta/
```
3. Crie um ambiente virtual
```
python -m venv .
```
4. Ative o ambiente virtual
```
source bin/activate
```
5. Instale o requirements 
```
pip install -r requirements.txt
```
6. Coloque as frases em código morse no arquivo frases.txt

7. Execute o script e veja as imagens decodificadas na tela
```
python decode_morse.py
```

----

#### AGORA É COM VOCÊ
Altere o projeto para receber um texto, ou seja, mais de uma palavra, sendo que:
- As letras devem ser separadas por um espaço
- As palavras devem ser separadas por dois espaços
- Executar com pelo menos 3 cenários diferentes, ou seja, 3 textos
- Você deve criar estes textos /frases de input