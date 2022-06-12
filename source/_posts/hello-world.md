---
title: Hello World
tags:
  - 总结
  - blog
categories:
  - blog
keywords: "hello，总结"
cover: https://cdn.jsdelivr.net/gh/HCLonely/hclonely.github.io/img/Butterfly/006.webp
toc: True
abbrlink: 520520
---
Welcome to [Hexo](https://hexo.io/)! This is your very first post. Check [documentation](https://hexo.io/docs/) for more info. If you get any problems when using Hexo, you can find the answer in [troubleshooting](https://hexo.io/docs/troubleshooting.html) or you can ask me on [GitHub](https://github.com/hexojs/hexo/issues).

## Quick Start

### Create a new post

``` bash
$ hexo new "My New Post"
```

More info: [Writing](https://hexo.io/docs/writing.html)

### Run server

``` bash
$ hexo server
```

More info: [Server](https://hexo.io/docs/server.html)

### Generate static files

``` bash
$ hexo generate
```

More info: [Generating](https://hexo.io/docs/generating.html)

### Deploy to remote sites

``` bash
$ hexo deploy
```

### C++ CODE

```c
#include <iostream>
using namespace std;

class CConst {
public:
	
	bool compare(const int a_t, const int b_t)
	{
		return a_t < b_t;
	}

	const int func() const
	{
		//a += 1;
		return a + b;
	}


private:
	int a;
	int b;
};

int main()
{
	CConst c;
	int a = 4;
	int b = 2;
	cout << c.compare(a, b) << endl;
	return 0;
}
```

### C# CODE

```C#
using System.Collections;
using System.Collections.Generic;
using UnityEngine;

[CreateAssetMenu(fileName = "New Item", menuName = "Inventory/New Item")]
public class Item : ScriptableObject
{
    [Tooltip("ID")]
    public uint m_id; //ID
    [Tooltip("道具名")]
    public string m_name;
    [Tooltip("道具描述")]
    [TextArea]
    public string m_desc;
    [Tooltip("获取方式")]
    [TextArea]
    public string m_getMethodDes;
    [Tooltip("道具稀有等级")]
    public uint m_level;
    [Tooltip("道具类型")]
    public int m_typeNum;
    [Tooltip("道具数目")]
    public uint m_countNum;
    [Tooltip("地板颜色")]
    public string m_bgColorStr;
    [Tooltip("提示界面颜色参数")]
    public string m_tipBgColorStr;

    public uint ID
    {
        get { return m_id; }
        set { m_id = value; }
    }

    public string Name
    {
        get { return m_name; }
        set { m_name = value; }
    }

    public string DescStr
    {
        get { return m_desc; }
        set { m_desc = value; }
    }

    public string GetMethodDesStr
    {
        get { return m_getMethodDes; }
        set { m_getMethodDes = value; }
    }
    public uint Level
    {
        get { return m_level; }
        set { m_level = value; }
    }
    public int TypeNum
    {
        get { return m_typeNum; }
        set { m_typeNum = value; }
    }
    public uint CountNum
    {
        get { return m_countNum; }
        set { m_countNum = value; }
    }

    public string BgColorStr
    {
        get { return m_bgColorStr; }
        set { m_bgColorStr = value; }
    }

    public string TipBgColorStr
    {
        get { return m_tipBgColorStr; }
        set { m_tipBgColorStr = value; }
    }

}
```

More info: [Deployment](https://hexo.io/docs/one-command-deployment.html)

![](http://rdcib7cq1.hn-bkt.clouddn.com/paiDaXing.jpeg)
