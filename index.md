---
title: Ana Sayfa
---

# 📄 Teknik Dokümantasyon Sitesi

Bu site **GitHub Pages** ve **Jekyll** kullanılarak oluşturulmuştur.
Markdown dosyaları otomatik olarak HTML'e dönüştürülür.

## 🚀 Başlangıç
- Soldaki/üstteki başlıktan sayfalar arasında gezinebilirsiniz.
- Kod örnekleri syntax highlight ile gösterilir.

```python
def hello():
    print("Merhaba Dünya!")
```

## 📅 Son Yazılar
{% for post in site.posts limit:10 %}
- [{{ post.title }}]({{ post.url | relative_url }}) — {{ post.date | date: "%Y-%m-%d" }}
{% endfor %}
