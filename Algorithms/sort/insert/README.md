# 插入排序

1. 只含有一个元素的序列，本身就是被排序好了的。
1. 对长度为n的序列进行n-1次循环，第i次循环从a[i]元素开始，i∈[1,n-1]。
1. 第i次循环时，a[i+1]元素不停地与前一个元素进行比较，如果比前一个元素小，就两者互换，否则循环结束。
1. 可知，在第i次循环前，a[:i]子序列是排序好的。第i次循环后，a[:i+1]子序列也是排序好了的。n-1次循环结束后。整个序列就排序完毕了。