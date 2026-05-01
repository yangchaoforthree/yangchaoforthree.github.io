---
show: true
width: 4
date: 2021-09-12 00:01:00 +0800
height: 295px
images:
- src: /assets/images/showcases/3:4.jpg
  title: 3/4 front lat spread
  # desc: Description 1.
  # link: https://picsum.photos/
- src: /assets/images/showcases/front-1.jpg
  title: Front chest spread
  # desc: Description 1.
  # link: https://picsum.photos/
- src: /assets/images/showcases/front-2.jpg
  title: Front chest spread
  # desc: Description 2

---

{% include widgets/carousel.html id=page.id images=page.images height=page.height %}
