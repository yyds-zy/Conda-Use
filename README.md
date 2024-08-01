## Conda Use
- conda env list 查看虚拟环境列表
- conda env remove --name <虚拟环境名>  删除虚拟环境
- conda activate <虚拟环境名>  激活进入虚拟环境
- conda create -n <虚拟环境名>  创建环境


## MLC-LLM Build
- 创建mlc-llm环境
```
conda create -n mlc-chat-venv -c conda-forge \
"cmake>=3.14" \
rust \
git \
python=3.11
```
- 激活进入环境
```
conda activate mlc-chat-venv
```

