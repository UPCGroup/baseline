# GAIL 代码复现
所需要依赖环境（包括 Jupyter）已经填写到 requirements.txt 里。
执行
```bash
pip install requirements.txt
```
完成依赖环境的安装。

# 常见问题
请确保 gym==0.25.2，否则代码
```python
return_list = train_on_policy_agent(env, ppo_agent, num_episodes)
```
会出现错误。