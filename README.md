Function to push data to stack:
def push(data):
    global head_pointer, stack
    if head_pointer == len(stack)-1:
        print("Stack Overflow!")
    else:
        head_pointer += 1
        stack[head_pointer] = data
        print("Data pushed successfully")
