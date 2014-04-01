---
layout: default
title: jMonkey Wiki
---

Testing Markdown code tags.

```java
public void rotateGeometry(final Geometry geo, final Quaternion rot) {
    mainApp.enqueue(new Callable() {
        public Spatial call() throws Exception {
            return geo.rotate(rot);
        }
    });
}
```

End of test.
