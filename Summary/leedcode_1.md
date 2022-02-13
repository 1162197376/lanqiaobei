# 该题的python编程漏洞
1. 对于python版本的输入输出是什么样的格式标准不清楚。

(```)
class Solution:
    def twoSum(self, nums: List[int], target: int) -> List[int]:
        for i in range(len(nums)):
            j = i+1
            for j in range(j, len(nums)):
                if nums[i]+nums[j]==target:
                    return [i,j]
        return t
(```)

注意：要注意蓝桥杯的输入输出格式

2. return
   - 是否能中断程序的运行
   - 为什么最后那个t标准程序上是[]？
3. range的用法模糊
4. 怎样获取列表的长度
   - len(nums)
