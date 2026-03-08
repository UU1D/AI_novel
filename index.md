# 小说库

欢迎来到小说阅读网站，这里为您收集精选网络小说。

<div style="text-align: center; margin: 20px 0;">
  <button id="likeBtn" style="
    background-color: #ff6b9d;
    color: white;
    border: none;
    padding: 12px 24px;
    font-size: 16px;
    border-radius: 5px;
    cursor: pointer;
    transition: all 0.3s ease;
  " onmouseover="this.style.backgroundColor='#ff5287'" onmouseout="this.style.backgroundColor='#ff6b9d'">
    👍 点赞 (<span id="likeCount">0</span>)
  </button>
</div>

<script>
  // 初始化点赞数
  function initLikes() {
    const likeCount = localStorage.getItem('novelPageLikes') || 0;
    document.getElementById('likeCount').textContent = likeCount;
  }
  
  // 点赞按钮事件
  document.getElementById('likeBtn').addEventListener('click', function() {
    let currentLikes = parseInt(localStorage.getItem('novelPageLikes') || 0);
    currentLikes++;
    localStorage.setItem('novelPageLikes', currentLikes);
    document.getElementById('likeCount').textContent = currentLikes;
    
    // 添加点击动画效果
    this.style.transform = 'scale(1.1)';
    setTimeout(() => {
      this.style.transform = 'scale(1)';
    }, 200);
  });
  
  // 页面加载时初始化
  initLikes();
</script>

---

## 📚 小说列表

### 1. 阿宾的都市情迷

| 信息 | 内容 |
|------|------|
| **分类** | 都市情感 |
| **大纲** | [查看大纲](阿宾的都市情迷/00-大纲.md) |
| **人物档案** | [查看人物档案](阿宾的都市情迷/01-人物档案.md) |

#### 章节列表

| 章节 | 链接 |
|------|------|
| 第1章 | [第01章](阿宾的都市情迷/第01章.md) |
| 第2章 | [第2章](阿宾的都市情迷/第2章.md) |
| 第3章 | [第3章](阿宾的都市情迷/第3章.md) |
| 第4章 | [第4章](阿宾的都市情迷/第4章.md) |
| 第5章 | [第5章](阿宾的都市情迷/第5章.md) |
| 第6章 | [第6章](阿宾的都市情迷/第6章.md) |
| 第7章 | [第7章](阿宾的都市情迷/第7章.md) |
| 第8章 | [第8章](阿宾的都市情迷/第8章.md) |
| 第9章 | [第9章](阿宾的都市情迷/第9章.md) |
| 第10章 | [第10章](阿宾的都市情迷/第10章.md) |
| 第11章 | [第11章](阿宾的都市情迷/第11章.md) |
| 第12章 | [第12章](阿宾的都市情迷/第12章.md) |
| 第13章 | [第13章](阿宾的都市情迷/第13章.md) |
| 第14章 | [第14章](阿宾的都市情迷/第14章.md) |
| 第15章 | [第15章](阿宾的都市情迷/第15章.md) |
| 第16章 | [第16章](阿宾的都市情迷/第16章.md) |
| 第17章 | [第17章](阿宾的都市情迷/第17章.md) |
| 第18章 | [第18章](阿宾的都市情迷/第18章.md) |
| 第19章 | [第19章](阿宾的都市情迷/第19章.md) |
| 第20章 | [第20章](阿宾的都市情迷/第20章.md) |

---

### 2. 无敌系统在神雕

| 信息 | 内容 |
|------|------|
| **分类** | 网络文学 |
| **大纲** | [查看大纲](无敌系统在神雕/00-大纲.md) |
| **人物档案** | [查看人物档案](无敌系统在神雕/01-人物档案.md) |

#### 章节列表

| 章节 | 链接 |
|------|------|
| 第1章 | [第01章](无敌系统在神雕/第01章.md) |
| 第2章 | [第02章](无敌系统在神雕/第02章.md) |
| 第3章 | [第03章](无敌系统在神雕/第03章.md) |
| 第4章 | [第04章](无敌系统在神雕/第04章.md) |
| 第5章 | [第05章](无敌系统在神雕/第05章.md) |
| 第6章 | [第06章](无敌系统在神雕/第06章.md) |
| 第7章 | [第07章](无敌系统在神雕/第07章.md) |
| 第8章 | [第08章](无敌系统在神雕/第08章.md) |
| 第9章 | [第09章](无敌系统在神雕/第09章.md) |
| 第10章 | [第10章](无敌系统在神雕/第10章.md) |
| 第11章 | [第11章](无敌系统在神雕/第11章.md) |

---

## 🔧 使用说明

- 点击上方表格中的章节链接可直接阅读正文
- 点击"大纲"和"人物档案"可了解故事背景
- 建议按顺序阅读章节以获得最佳阅读体验
