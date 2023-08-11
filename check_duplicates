def check_duplicates(lst):
    duplicates = []
    seen = set()
    
    for item in lst:
        if item in seen:
            duplicates.append(item)
        else:
            seen.add(item)
    
    return duplicates

# 示例用法
my_list = [1, 2, 3, 4, 2, 5, 3, 6, 7, 8, 7]
result = check_duplicates(my_list)
print("重复元素：", result)
