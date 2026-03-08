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

1. [阿宾的都市情迷](阿宾的都市情迷.md)
2. [无敌系统在神雕](无敌系统在神雕.md)
3. [第三本小说](第三本小说.md)

---

> 点击书名进入详情页面，阅读章节与背景内容。
