# reproducibility-tutorial
Malaria


testing

testing nano

    1  la
    2  ls
    3  cd /scratch
    4  ls
    5  git clone https://github.com/crestre/FOSS-Spring-2021-Group-5-Captsone-I.git
    6  wget https://repo.anaconda.com/miniconda/Miniconda3-latest-Linux-x86_64.sh
    7  bash Miniconda3-latest-Linux-x86_64.sh -b -p /opt/conda
    8  ln -s /opt/conda/pkgs/*/bin/* /bin
    9  ln -s /opt/conda/pkgs/*/lib/* /usr/lib
   10  /opt/conda/bin/conda install -c conda-forge -y jupyterlab=1.2.3
   11  /opt/conda/bin/conda install -c conda-forge -y nodejs=10.13.0
   12  /opt/conda/bin/pip install bash_kernel
   13  /opt/conda/bin/pip install ipykernel
   14  /opt/conda/bin/python3 -m bash_kernel.install
   15  conda searchjupyterlab
   16  conda <searchjupyterlab>
   17  conda search <jupyterlab>
   18  conda search jupyterlab=1.2.3
   19  /opt/conda/bin/jupyter lab --no-browser --allow-root --ip=0.0.0.0 --NotebookApp.token='' --NotebookApp.password='' --notebook-dir='/scratch/reproducibility-tutorial/'
   20  ls
   21  git clone https://github.com/crestre/reproducibility-tutorial.git
   22  ls
   23  /opt/conda/bin/jupyter lab --no-browser --allow-root --ip=0.0.0.0 --NotebookApp.token='' --NotebookApp.password='' --notebook-dir='/scratch/reproducibility-tutorial/'
   24  /opt/conda/bin/conda search -c bioconda snakemake
   25  /opt/conda/bin/conda install -c bioconda -c conda-forge -y snakemake=5.8.1
   26  wget https://repo.anaconda.com/miniconda/Miniconda3-latest-Linux-x86_64.sh
   27  bash Miniconda3-latest-Linux-x86_64.sh -b -p /opt/conda
   28  ln -s /opt/conda/pkgs/*/bin/* /bin
   29  /opt/conda/bin/conda search -c bioconda snakemake
   30  /opt/conda/bin/conda install -c bioconda -c conda-forge -y snakemake=5.8.1
   31  conda config --set channel_priority false
   32  conda install -c spyder-ide spyder-unittest
   33  /opt/conda/bin/conda search -c bioconda snakemake
   34  /opt/conda/bin/conda install -c bioconda -c conda-forge -y snakemake=5.8.1
   35  ln -s /opt/conda/bin/* /bin
   36  ln -s /opt/conda/lib/* /usr/lib
   37  snakemake --version
   38  apt install snakemake
   39  snakemake --version
   40  sudo apt-get update
   41  sudo apt-get install -y apt-transport-https ca-certificates curl gnupg-agent software-properties-common
   42  curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -
   43  sudo add-apt-repository "deb [arch=amd64] https://download.docker.com/linux/ubuntu \
   44  $(lsb_release -cs) \
   45  stable"
   46  sudo apt-get update
   47  sudo apt-get install -y docker-ce docker-ce-cli containerd.io
   48  docker run hello-world
   49  cd /scratch/reproducibility-tutorial/
   50  ls
   51  history >>README.md
   52  nano README.md
   53  cd /scratch
   54  ls
   55  df -h
   56  git clone https://github.com/crestre/reproducibility-tutorial.git
   57  wget https://repo.anaconda.com/miniconda/Miniconda3-latest-Linux-x86_64.sh
   58  ls
   59  bash Miniconda3-latest-Linux-x86_64.sh -b -p /opt/conda
   60  ln -s /opt/conda/pkgs/*/bin/* /bin
   61  ln -s /opt/conda/pkgs/*/lib/* /usr/lib
   62  /opt/conda/bin/jupyter lab --no-browser --allow-root --ip=0.0.0.0 --NotebookApp.token='' --NotebookApp.password='' --notebook-dir='/scratch/reproducibility-tutorial/'
   63  cd /scratch
   64  /opt/conda/bin/conda search -c bioconda snakemake
   65  /opt/conda/bin/conda install -c bioconda -c conda-forge -y snakemake=5.8.1
   66  s
   67  ls
   68  snakemake --version
   69  sudo apt-get update
   70  sudo apt-get install -y apt-transport-https ca-certificates curl gnupg-agent software-properties-common
   71  curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -
   72  sudo add-apt-repository  "deb [arch=amd64] https://download.docker.com/linux/ubuntu \
 $(lsb_release -cs) \
 stable"
   73  sudo apt-get update
   74  sudo apt-get install -y docker-ce docker-ce-cli containerd.io
   75  docker run hello-world
   76  cd /scratch/reproducibility-tutorial/
   77  ls
   78  history >>README.md
