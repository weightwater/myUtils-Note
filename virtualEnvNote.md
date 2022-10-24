#### 虚拟环境配置笔记
- 查看包
    
    conda list

- 查看当前虚拟环境

    conda env list
    conda info -e

- 检查当前更新

    conda update conda 

- Python创建虚拟环境

    conda create -n your_env_name python=x.x

- 激活或者切换虚拟环境

    Linux: source activate your_env_name
    Windows: activate your_env_name

- 关闭虚拟环境

    deactivate env_name
    Linux: source deactivate

- 删除虚拟环境

    conda remove -n your_env_name --all
    
- 删除环境中的包

    conda remove --anme $your_env_name $package_name

- 添加清华源

    conda config --add channels mirrors.tuna.tsinghua.edu.cn...

