## 题目描述

整数数组 nums 按升序排列，数组中的值 互不相同 。

在传递给函数之前，nums 在预先未知的某个下标 k（0 <= k < nums.length）上进行了 旋转，使数组变为 [nums[k], nums[k+1], ..., nums[n-1], nums[0], nums[1],
..., nums[k-1]]（下标 从 0 开始 计数）。例如， [0,1,2,4,5,6,7] 在下标 3 处经旋转后可能变为 [4,5,6,7,0,1,2] 。

给你 旋转后 的数组 nums 和一个整数 target ，如果 nums 中存在这个目标值 target ，则返回它的下标，否则返回 -1 。

 

示例 1：
<br>输入：nums = [4,5,6,7,0,1,2], target = 0
<br>输出：4

示例 2：
<br>输入：nums = [4,5,6,7,0,1,2], target = 3
<br>输出：-1

示例 3：
<br>输入：nums = [1], target = 0
<br>输出：-1

提示：
<br>1 <= nums.length <= 5000
<br>-10^4 <= nums[i] <= 10^4
<br>nums 中的每个值都 独一无二
<br>题目数据保证 nums 在预先未知的某个下标上进行了旋转
<br>-10^4 <= target <= 10^4

## 解法

[==>SOLUTION<==](https://leetcode-cn.com/problems/search-in-rotated-sorted-array/solution/sou-suo-xuan-zhuan-pai-xu-shu-zu-by-leetcode-solut/)

## 代码

[Search.java](https://github.com/Marshal7cc/leetcode-java/blob/master/src/binarysearch/Search.java)
