# Leetcode Top150

## 前言

本文对Leetcode Top150进行重新分类，按照算法思想或者数据结构进行分类，包含了每个题目的题解和分析，全部使用**Python**进行实现。

## How to test
```python
# Function to test the Solution class with various test cases
def test_solution(your_function: str):
    # List of test cases
    test_cases = [
        (input, expected),
        (input, expected)
    ]

    # Create an instance of Solution class
    solution = Solution()

    # Test each case
    for i, (input, expected) in enumerate(test_cases):
        result = getattr(solution, your_function)(s, wordDict)
        print(f"Test Case {i+1}: {'Passed' if result == expected else 'Failed'}")
        print(f"  Input: {s, wordDict}")
        print(f"  Expected: {expected}")
        print(f"  Got: {result}")
        print()
```

## 算法思想

- [双指针]
- [排序]
- [贪心思想]
- [二分查找]
- [分治]
- [动态规划]

## 数据结构相关

- [链表]
- [树]
- [栈和队列]
- [哈希表]
- [字符串]
- [数组与矩阵]

## 参考资料

- Leetcode
