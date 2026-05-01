---
show: true
width: 4
date: 2021-09-12 00:02:00 +0800
height: 295px
images:
- src: /assets/images/showcases/basketball-0.jpg
  title: Dong Dan
  # desc: Description 1.
  # link: https://picsum.photos/
- src: /assets/images/showcases/basketball-1.jpg
  title: Shotting
  # desc: Description 1.
  # link: https://picsum.photos/
- src: /assets/images/showcases/basketball-2.jpg
  title: Shotting
  # desc: Description 1.
  # link: https://picsum.photos/
- src: /assets/images/showcases/basketball-3.jpg
  title: Passing
  # desc: Description 2

---

{% include widgets/carousel.html id=page.id images=page.images height=page.height %}
