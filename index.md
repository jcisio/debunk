Đối với dịch bệnh Covid-19, có không ít những quan điểm "trái chiều", ban đầu là câu hỏi về một dịch bệnh được phóng đại hóa, sau đó là hoài nghi về vắc-xin. Chúng ta luôn cần hoài nghi, trang thông tin này sẽ cố gắng phân tích các nhận định về Covid-19 dựa trên các luận cứ khoa học và các số liệu được công bố rộng rãi.

# Dịch Covid-19

{% for page in site.covid -%}
* [{{ page.title }}]({{ page.url }})
{% endfor %}

# Vắc-xin

{% for page in site.vac-xin -%}
* [{{ page.title }}]({{ page.url }})
{% endfor %}

# Bệnh tật

{% for page in site.benh-tat -%}
* [{{ page.title }}]({{ page.url }})
{% endfor %}
