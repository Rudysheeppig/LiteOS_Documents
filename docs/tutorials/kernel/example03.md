# 范例03（Task）

为了解决上面的问题，将独占for循环延时，修改为vTaskDelay，该函数会在延时期间释放cpu，让低优先级任务运行