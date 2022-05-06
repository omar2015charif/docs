![68747470733a2f2f73332e616d617a6f6e6177732e636f6d2f776174747061642d6d656469612d736572766963652f53746f7279496d6167652f32656545496637776e4568726e673d3d2d3736383139303539342e31356238316461323135613264343536333239323734313030372e706e67](https://user-images.githubusercontent.com/104700249/167209422-725f9760-cc1b-4228-8ee1-d0c0b74fe185.png)
---
slug: /blocks
hide_table_of_contents: true
---

# TurboWarp Blocks

TurboWarp has a section of blocks that allows you to use certain features previously not accessible to Scratch projects.

## is compiled? and is TurboWarp? {#is-compiled}

![is compiled?](./assets/is-compiled.svg)

See https://scratch.mit.edu/projects/414716080/

These blocks are "compatible" with Scratch because they're actually just modified argument reporters.

:::warning
Every block beyond this warning is **incompatible** with Scratch. Projects that using them **can not** be uploaded to the Scratch website. If you don't use any TurboWarp-exclusive blocks, then there should be no issue with making your project in TurboWarp and uploading it to Scratch.

**We do not recommend using these blocks. No new blocks will be added in the forseeable future**.
:::

## last key pressed {#last-key-pressed}

![last key pressed](./assets/last-key-pressed.svg)

It tells you the last key that was pressed. It's intended to be used something like this:

![when any key pressed, do something with last key pressed](./assets/how-to-use-last-key-pressed.svg)

## mouse button down? {#mouse-button-down}

![primary mouse button down?](./assets/mouse-button-down.svg)

It's like "mouse down?" but lets you check each individual button. Keep in mind that due to how Scratch interprets mouse input, it's possible for a block like "is primary mouse button down?" to report true while the standard "mouse down?" reports false.

 * (0) primary is usually left
 * (1) middle is usually scroll wheel
 * (2) secondary is usually right (running this block once will disable right click on the stage)
