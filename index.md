
layout: defaulttitle: Danh Sách Truyện
Website Truyện Chữ
Chào mừng bạn đến với bộ sưu tập truyện chữ của chúng tôi!
Danh sách truyện
{% for story in site.stories %}

[{{ story.title }}]({{ story.url }}){{ story.description }}{% endfor %}
