---

# Page settings
layout: default
keywords:
comments: false

# Hero section
title: Shadow
description: A modifier used for applying a shadow to a composable
buttons:
  - icon: github
    content: View in Playground
    url: "https://github.com/hitherejoe/ComposeAcademy-Playground/blob/master/app/src/main/java/co/joebirch/composeplayground/core/shadow.kt"
    external_url: true

# Micro navigation
micro_nav: false

---

## Constructors

```kotlin
Modifier.drawShadow(12.dp, RectangleShape)
```

  * **elevation** - the elevation to be applied when drawing the shadow

  * **shape** - the shape to be applied when drawing the shadow

  * **clipToOutline** - whether or not the shadow should be clipped to the outline  of the shape

  * **opacity** - the opacity to be applied when drawing the shadow

## Examples

```kotlin
Box(
    modifier = Modifier.preferredSize(100.dp, 100.dp).drawShadow(12.dp, RectangleShape),
    backgroundColor = Color.Green
)
```

![Shadow](/academy/core/media/shadow.png)
