# 队列

操作受限制线性表，先进先出(FIFO - first in first out),只允许在后端(rear)插入，前端(top)删除。

类似于排队买票，先来先买，后来的只能排在末尾，不允许插队。

## 常用方法

- add 增加一个元索  如果队列已满，则抛出一个IIIegaISlabEepeplian异常
- remove 移除并返回队列头部的元素 如果队列为空，则抛出一个NoSuchElementException异常
- element 返回队列头部的元素 如果队列为空，则抛出一个NoSuchElementException异常
- offer 添加一个元素并返回true 如果队列已满，则返回false
- poll 移除并返问队列头部的元素 如果队列为空，则返回null
- peek 返回队列头部的元素 如果队列为空，则返回null
- put 添加一个元素 如果队列满，则阻塞
- take 移除并返回队列头部的元素 如果队列为空，则阻塞

## 应用

### 顺序队列

### 循环队列

### 阻塞队列

### 并发队列

### 优先级队列
