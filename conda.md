# Install conda python env on AWS EC2
- Update the package on EC2
  - ```sudo yum update -y```
  - ```sudo yum install -y wget bzip2```
- Download and install Miniconda
  - ```wget https://repo.anaconda.com/miniconda/Miniconda3-latest-Linux-x86_64.sh```
  - ```bash Miniconda3-latest-Linux-x86_64.sh```
- Source the changes to your `.bashrc` file:
  - `source ~/.bashrc`
- Update Conda to the latest version
  - `conda update -n base -c defaults conda`
- Create a new Conda environment with Python 3.10
  - `conda create -n py310 python=3.10` 
- Activate the new environment
  - `conda activate py310` 
- To exit the 'py310' Conda environment, use the following command
  - `conda deactivate`

# Install conda python env on M3
- mkdir -p ~/miniconda3
- curl https://repo.anaconda.com/miniconda/Miniconda3-latest-MacOSX-arm64.sh -o ~/miniconda3/miniconda.sh
- bash ~/miniconda3/miniconda.sh -b -u -p ~/miniconda3
- rm ~/miniconda3/miniconda.sh
