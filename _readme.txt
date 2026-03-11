根据豆包回答的
# ollama ， install
curl -fsSL https://ollama.com/install.sh | bash

# 最优选择：Gemma-3-270m（推荐学习用）  实际上 Gema-3-270 下载了 291M,
ollama run gemma3:270m

# 进阶选择：DeepSeek-R1 1.5B（中文更友好） 实际上下载了 1.1GB,
ollama run deepseek-r1:1.5b

# 个人分析
/?  帮助
/show modelfile  显示文件在哪里
/show info

# openclaw配置，支持tool才行.. 下载1.3G
ollama run llama3.2:1b
# 极致省资源：qwen2.5:1.5b 或 llama3.2:1b
qwen2.5:1.5b  // 986MB

