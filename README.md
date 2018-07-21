# install-cuda-cuDNN-etc
- 动机
  安装tensorflow-gpu前需要先安装cuda,cuDNN，而这一过程可能产生很多问题，新手不一定能够很快就能配置好自己的深度学习环境，配置环境这一步可以很简单，不必浪费时间。
 
- 实现
  tensorflow的版本需要和cuda,cuDNN等的版本相匹配，本脚本运行完毕就可以安装tensorflow1.8.0版本，如果要安装tensorflow其他版本，则需要提前知道所需要的cuda,cuDNN，cuda-command-line-tools版本，然后修改脚本即可。

注：本机环境 ubuntu16.04, tensorflow1.8.0.
