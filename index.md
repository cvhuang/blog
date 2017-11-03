## 学习 Markdown 手记
### 标题字号
* # 一级标题
* ## 二级标题
* ......
* #### 四级标题
### 列表
* 用 * + - 等
* 数字标 数字加.

* test
* test

1. test
2. test

### 引用
> A year from now you will wish you had started today.

### 粗体斜体
*test*  **test** 

### 表格
1 | 2 | 3
----|------|----
d | 23%  | 23%
d | 23%  | 23%
d | 23%  | 23%

### 链接
[blog](http://www.cnblogs.com/penguins/)

### 插入图片
* 首先将图片上传到Github
* 然后 ![image] (https://github.com/cvhuang/blog/blob/master/20170524173833525516.png)
示例
![image](https://github.com/cvhuang/blog/blob/master/20170524173833525516.png)

### 插入代码

`image = cv::imresize( image, 300, 300 );`

```python
     logits1 = fully_connected(expanded_output, dim_dec, 'dec_fc', group_id=1)
     logits1 = nonlinear(logits1, 'tanh')
     logits1 = dropout(logits1, 0.5, is_train)  
 ```
 ### 插入公式
 用 latex online 生产图片, 导入Github

