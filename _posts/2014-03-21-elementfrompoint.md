---
layout: default
title: elementfrompoint���ӳټ����е�����
---

### �ӿ���Ϣ

```C++
partial interface Document {
  Element? elementFromPoint(double x, double y);
  sequence<Element> elementsFromPoint(double x, double y);
  CaretPosition? caretPositionFromPoint(double x, double y);
};
```

### ��ȡ����

`elementFromePoint(x, y)`������ȡ��Ԫ�ص������ǣ�

- ����Ϊ�Ǹ���
- x, y ���� viewport ��
- û��һ�� viewport �������������� phantomJS ��ִ�г���

����ִ�к������� null��

### ��ȡ��ʽ

- ���� viewport �ڵ���һ�� box��������Ⱦ˳���������һ�� box ��ʼѰ�ң�֪�� viewport �ĵײ���
- ����ĵ��и�Ԫ�أ����Ҷ����е����һ��Ԫ�ز��Ǹ�Ԫ�أ��������Ԫ�ء�

### DEMO

[Full Screen](http://jsfiddle.net/barretlee/Ldtj7/embedded/result/)
