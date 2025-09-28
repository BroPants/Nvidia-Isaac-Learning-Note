# Experiment Log

2025.09.28 测试 00_sim/spawn_prims.py 时，发现物体移动的时候有残影。尝试修改GPU和Thread参数后，无法运行Isaac python脚本，但可以单独启动isaacsim。尝试重装Isaacsim.重装conda环境和isaaclab后，可以正常启动。渲染残影问题依然有，但通过转动视角好像可以缓解。