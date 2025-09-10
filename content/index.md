---
title: DeepRead
---

| 📖 书籍名称 | 🔗 宏观蓝图 | 📊 节点数 | ✨ 特色 |
|------------|------------|----------|-------|
| 《三体》 | [[三体/三体-宏观蓝图]] | 99 | 科幻史诗巨著 |
| 《三国演义》 | [[三国演义/三国演义-宏观蓝图]] | 94 | 人物关系图谱 |
| 《红楼梦》 | [[红楼梦/红楼梦-宏观蓝图]] | 73 | 家族脉络分析 |
| 《西游记》 | [[西游记/西游记-宏观蓝图]] | 192 | 取经路线图 |
| 《水浒传》 | [[水浒传/水浒传-宏观蓝图]] | 95 | 英雄谱系统 |
| 《百年孤独》 | [[百年孤独/百年孤独-宏观蓝图]] | 48 | 魔幻现实主义 |
| 《中国历代政治得失》 | [[中国历代政治得失/中国历代政治得失-宏观蓝图]] | 68 | 政治制度分析 |
| 《做哲学》 | [[做哲学/做哲学-宏观蓝图]] | 164 | 哲学概念体系 |
| 《哥德尔艾舍尔巴赫》 | [[哥德尔艾舍尔巴赫集异璧之大成/哥德尔、艾舍尔、巴赫——集异璧之大成-宏观蓝图]] | 60 | 认知科学经典 |
| 《我们赖以生存的隐喻》 | [[我们赖以生存的隐喻/我们赖以生存的隐喻-宏观蓝图]] | 75 | 语言认知科学 |
| 《乌合之众-群体心理学》 | [[乌合之众-群体心理学/乌合之众-群体心理学-宏观蓝图]] | 44 | 群体心理分析 |
| 《资本论第一册》 | [[资本论第一册/资本论第一册-宏观蓝图]] | 62 | 政治经济学 |
| 《资本论第二册》 | [[资本论第二册/资本论第二册-宏观蓝图]] | 55 | 流通过程分析 |
| 《资本论第三册》 | [[资本论第三册/资本论第三册-宏观蓝图]] | 51 | 总过程分析 |
| 《动物农场》 | [[动物农场/动物农场-宏观蓝图]] | 33 | 政治寓言经典 |
| 《小镇喧嚣》 | [[小镇喧嚣-一个乡镇政治运作的演绎与阐释/小镇喧嚣-一个乡镇政治运作的演绎与阐释-宏观蓝图]] | 58 | 乡镇政治研究 |
| 《孙子兵法》 | [[孙子兵法/孙子兵法-宏观蓝图]] | 64 | 孙子兵法解析 |
| 《城乡中国》 | [[城乡中国/城乡中国-宏观蓝图]] | 49 | 城乡发展研究 |
| 《置身事内-中国政府与经济发展》 | [[置身事内-中国政府与经济发展/置身事内-宏观蓝图]] | 37 | 政府经济政策 |
| 《乡土中国》 | [[乡土中国/乡土中国-宏观蓝图]] | 53 | 中国乡土社会研究 |
| 《语言哲学》 | [[语言哲学/语言哲学讲义-宏观蓝图]] | 49 | 语言哲学体系 |
| 《何为良好生活》 | [[何为良好生活/何为良好生活-宏观蓝图]] | 43 | 伦理学思辨 |
| 《哲学·科学·常识》 | [[哲学·科学·常识/哲学·科学·常识-宏观蓝图]] | 67 | 科学哲学史 |
| 《感知•理知•自我认知》 | [[感知•理知•自我认知/感知•理知•自我认知-宏观蓝图]] | 51 | 认知哲学论述 |
| 《走出唯一真理观》 | [[走出唯一真理观/走出唯一真理观-宏观蓝图]] | 48 | 哲学思辨批判 |
| 《说理》 | [[说理/说理-宏观蓝图]] | 44 | 论理方法论 |


---

<div class="action-buttons">
  <a href="网站介绍" class="action-button primary">
    <span class="icon">📝</span>
    网站介绍
  </a>
  <a href="https://github.com/liujuntao123/DeepRead" class="action-button secondary" target="_blank">
    <span class="icon">🐱</span>
    GitHub 源码
  </a>
  <a href="AI驱动的书籍知识图谱制作完整指南" class="action-button success">
    <span class="icon">📖</span>
    制作教程
  </a>
  <button onclick="openFeedbackModal()" class="action-button feedback">
    <span class="icon">💬</span>
    建议和反馈
  </button>
</div>

<!-- 反馈弹窗 -->
<div id="feedbackModal" class="modal">
  <div class="modal-content">
    <div class="modal-header">
      <h3>建议和反馈</h3>
    </div>
    <div class="modal-body">
      <p class="feedback-text">扫描下方二维码，加入交流群或提供宝贵建议</p>
      <img src="/static/feedback-qr.png" alt="反馈二维码" class="qr-code" />
      <p class="feedback-text">感谢您的支持和建议！</p>
    </div>
    <div class="modal-footer">
      <button onclick="closeFeedbackModal()" class="close-btn">关闭</button>
    </div>
  </div>
</div>

<script>
function openFeedbackModal() {
  document.getElementById('feedbackModal').classList.add('show');
  document.body.style.overflow = 'hidden';
}

function closeFeedbackModal() {
  document.getElementById('feedbackModal').classList.remove('show');
  document.body.style.overflow = 'auto';
}

// 点击弹窗外部区域关闭弹窗
document.getElementById('feedbackModal').addEventListener('click', function(e) {
  if (e.target === this) {
    closeFeedbackModal();
  }
});

// ESC键关闭弹窗
document.addEventListener('keydown', function(e) {
  if (e.key === 'Escape') {
    closeFeedbackModal();
  }
});
</script>