---
title: "쥔장에게 연락하기 Contact"
permalink: "/contact.html"
---

<form action="https://formspree.io/{{site.email}}" method="POST">    
<p class="mb-4">문의사항을 아래 양식에 작성해 주시면 {{site.name}}에게 메일이 갑니다. 최대한 빨리 답변드릴게요!</p>
<div class="form-group row">
<div class="col-md-6">
<input class="form-control" type="text" name="name" placeholder="이름 Name*" required>
</div>
<div class="col-md-6">
<input class="form-control" type="email" name="_replyto" placeholder="이메일 E-mail Address*" required>
</div>
</div>
<textarea rows="8" class="form-control mb-3" name="message" placeholder="내용 Message*" required></textarea>    
<input class="btn btn-success" type="submit" value="발송 Send">
</form>
