# 第一天学习检查清单

## ✅ 完成状态确认

### 环境搭建（30分钟）
- [x] Python安装完成（版本3.10+）
- [x] VS Code安装完成
- [x] Python插件安装完成
- [x] 可以在命令行运行`python --version`
- [x] 可以进入Python交互模式

### 基础语法学习（1小时）
- [x] 理解4种基本数据类型（int, float, str, bool）
- [x] 掌握变量赋值和命名规则
- [x] 理解并使用基本运算符（算术、比较、逻辑）
- [x] 掌握字符串的基本操作（拼接、重复、切片）

### LeetCode刷题（1.5小时）
- [x] 完成第1题：两数之和（暴力解法和优化解法）

  ```
  # 暴力算法
  nums = [2, 7, 11, 15]
  # target = 9
  #
  #
  # def twosum(nums, target):
  #     for i in range(len(nums)):
  #         for j in range(i + 1, len(nums)):
  #             if nums[i] + nums[j] == target:
  #                 return [i, j]
  #
  #
  # su = twosum(nums, target)
  # print(su)
  ```

  ```
  #优化代码
  nums = [2,7,11,15]
  target = 9
  hap = {}
  
  
  def sum_1(nums, target):
      for key,value in enumerate(nums):
          hap[key] = value
      for i,num in enumerate(nums):
          j = hap.get(target-num)
          if j is not None and j != i:
              return [i, j]
  ```

  

- [ ] 完成第26题：删除有序数组中的重复项

- [ ] 完成第27题：移除元素

- [ ] 理解每道题的解题思路

### 代码实践（30分钟）
- [ ] 运行day1_python_basics.py文件
- [ ] 理解每段代码的输出结果
- [ ] 尝试修改代码参数，观察输出变化

## 📝 今日学习笔记

### 重要概念记录
- 变量命名规则：只能包含字母、数字、下划线，不能以数字开头
- 字符串切片：左闭右开，支持负数索引
- LeetCode双指针思想：一个快指针遍历，一个慢指针记录有效位置

### 疑问记录
- （在此记录学习中遇到的问题）

## 🎯 明日预习内容
- 列表的进阶操作（列表推导式、常用方法）
- 字典的基本操作
- 异常处理基础

## 💪 学习心得
（在此记录今天的学习收获和感受）