# border-height
通过css 控制边框的高度
注意示例中右边边框是没有定边的
# 示例代码
```
      .container  {
        display: inline-block;
        background: #efefef;
        height: 32px;
        width:200px;
        position: absolute;
      }
      .split::after{
        content: " ";
        border-left: 1px solid #000000;
        display: inline-block;
        height: 16px;
        position: absolute;
        top: 50%;
        right: 0px;
        margin-top: -8px;
      }
```
# 示例
![image](https://github.com/SelfDown/border-height/assets/22128775/1baa58d1-2c85-4922-883b-ddb28ea400ac)
![image](https://github.com/user-attachments/assets/c9a011e1-d1e7-4eb8-8e21-049465f95fca)

