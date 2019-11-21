# -*- coding: utf-8 -*-
import io
import sys
import random
# 改变标准输出的默认编码
sys.stdout = io.TextIOWrapper(sys.stdout.buffer, encoding='utf-8')

# 方法一：直接用已有模块
code_list = random.sample(range(1000,10000),200)

# 方法二：生成随机数列
# 先生成一个初始数列
code_list = [random.randint(1000,10000) for i in range(200)]
# 去重
code_list = list(set(code_list))
# 补充新的随机数到列表
while len(code_list)<200:
    add_number = random.randint(1000,10000)
    if add_number not in code_list:
        code_list.append(add_number)
print(code_list)
