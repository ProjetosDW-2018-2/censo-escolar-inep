### Projeto de Data Warehousing & Business Intelligence (2018.2)
> (Python + SQL + Pentaho) <br>
> Sistemas de Informação - UFRPE <br>

### Índice
* [1) Objetivos
* [2) Instalação e configuração de ambiente
* [3) Consultas e resultados
* [4) Equipe

### Objetivos

- [X] Aplicar os conceitos e ferramentas utilizados durante a disciplina em uma base de dados abertos do INEP;
- [X] Criar consultas, apresentadas através de gráficos e um mapa de calor;

### Instalação e configuração de ambiente

* 1.1) Primeiramente é necessário ter instalado no seu sistema os seguintes itens:
- [x] [Anaconda](https://www.anaconda.com/download/)
* 1.1.1) Após a instalação, verificar se o Anaconda foi corretamente instalado através do terminal, ou cmd, usando o do comando:

```
$ conda --version
```
* 1.2) Através do terminal, ou cmd, instale os pacotes do Pandas e Folium com os comandos:

```
$ conda install -c anaconda pandas
```

```
$ conda install -c conda-forge folium
```
* 1.2.1) Alguns dados usados no processo de geração dos mapas de calor são muito grandes, por isso deixamos eles disponíveis no drive abaixo. Basta baixá-los e colocar todos, sem alterar nenhuma informação, na past "plot" do repositório.

- [x] [arquivos](https://drive.google.com/open?id=1fUoPaMbR2p52E1ipEZza8P_d7xvThuzB)

* 1.3) Agora com os pacotes instalados e os arquivos baixados é necessário iniciar o Jupyter. No terminal - ou cmd - digite o comando:

```
$ jupyter-notebook
```

* 1.4) Após o serviço do Jupyter ser iniciado navegue através do mesmo até a pasta "plot" dentro do local onde o repositório repositório foi baixado.

* 1.4.1) Dentro desta pasta consta o notebook "escolacenso_heat_map.ipynb", somente clicando nele através do Jupyter ele será iniciado.

* 1.4.2) Dentro do notebook existem blocos que chamamos de células. É necesśario executar cada célula na ordem já definida dentro do notebook para evitar erros. Cada célula possui comentários que explicam o que cada bloco está fazendo para construir os mapas de calor.

### Consultas e resultados



### Equipe
- [Francisco Queiroga](https://github.com/chicoqueiroga)<br>
- [Rafael Douglas](https://github.com/rafaeldougllas)<br>
- [Everton Veloso](https://github.com/everton-nv)<br>
- [Jadiel Eudes](https://github.com/Eudess)<br>
