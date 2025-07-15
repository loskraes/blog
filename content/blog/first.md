+++
title = "Mon premier article"
#slug = "first"
date = 2025-07-14
update = 2025-07-15
description = "Description de mon premier article"
#path = "asdf.html"
#aliases = []
authors = ["LoskrAES"]
[extra]
license = "CC-BY-4.0"
snippets_license = "CC-BY-NC-SA-4.0"
+++
# A first-level heading

## A second-level heading

### A third-level heading

**Bold** **bold**

*Italic* *italic*

~~Baré~~ ~Baré~

***bold-italic***
***bold-italic***
***bold-italic***
***bold-italic***

asdf <sub>sub</sub><sup>sup</sup>

H~2~O
X^2^

<ins>sousligné</ins>

> Test that is a quote

```
git status
git add
git commit
```

```sh
git status
git add
git commit
```

```rust,linenos,name=main.rs,hl_lines=1 3-5 9
fn main() -> Result<()> {
  let s = String::new("Albert");
  println!("Bonjour, {s}");
  Ok(())
}
fn main2() -> Result<()> {
  let s = String::new("Albert");
  println!("Bonjour, {s}");
  Ok(())
}
fn main3() -> Result<()> {
  let s = String::new("Albert");
  println!("Bonjour, {s}");
  Ok(())
}
fn main4() -> Result<()> {
  let s = String::new("Albert");
  println!("Bonjour, {s}");
  Ok(())
}
```

[link](example.com)

<http://example.com>

Image: ![Screenshot of a comment on a GitHub issue showing an image, added in the Markdown, of an Octocat smiling and raising a tentacle.](https://myoctocat.com/assets/images/base-octocat.svg)

List:

- Abc
- Bcd
- Cde

1. A
1. B
1. C

asdf

==important thing==

1. First
   - second-level
     - third

A foot[^1].

[^1]: My reference with link <http://example.com>

Task:

- [ ] A
- [x] B

:+1: :joy:

> [!NOTE]
> A note about ...

> [!TIP]
> A tip about ...

> [!IMPORTANT]
> A tip about ...

> [!WARNING]
> A warn about ...

> [!CAUTION]
> A warn about ...

\*not bold\*

`code`

| Syntax | Description |
| ----------- | ----------- |
| Header | Title |
| Paragraph | Text |

| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |

asdf

---

$ a^2 + b^2 = c^3 $

$$
a^2 + b^2 = c^2
$$

```diff
## git diff a/test.txt b/test.txt
diff --git a/a/test.txt b/b/test.txt
index 309ee57..c995021 100644
--- a/a/test.txt
+++ b/b/test.txt
@@ -1,8 +1,6 @@
-The quick brown fox jumps over the lazy dog
+The quick brown fox jumps over the lazy cat

 a
-b
 c
 d
-e
 f
```

Mon text <kbd>cmd + shift + p</kbd>

<details>
  <summary>Markdown</summary>

  mon contenut

</details>

asdf

***

asdf

___

qwer

term
: definition
