<p align="center">
  <img src="https://i.imgur.com/QZownhg.png" width="240" />
</p>

<br />

<h1 align="center">@diotoborg/nobis-facilis</h1>
<h3 align="center">A spring-physics first animation library <br>giving you flexible tools to confidently cast your ideas</h3>

<br>

<p align="center">
  <a href="https://www.npmjs.com/package/@diotoborg/nobis-facilis" target="_blank">
    <img src="https://img.shields.io/npm/v/@diotoborg/nobis-facilis.svg?style=flat&colorA=000000&colorB=000000" />
  </a>
  <a href="https://www.npmjs.com/package/@diotoborg/nobis-facilis" target="_blank">
    <img src="https://img.shields.io/npm/dm/@diotoborg/nobis-facilis.svg?style=flat&colorA=000000&colorB=000000" />
  </a>
  <a href="https://discord.gg/AXfNsGx64f" target="_blank">
    <img src="https://img.shields.io/discord/740090768164651008?style=flat&colorA=000000&colorB=000000&label=discord&logo=discord&logoColor=ffffff" alt="Chat on Discord">
  </a>
</p>

<br>

`@diotoborg/nobis-facilis` is a cross-platform spring-physics first animation library.

It's as simple as:

```jsx
const styles = useSpring({
  from: {
    opacity: 0
  },
  to: {
    opacity: 1
  }
})

<animated.div style={styles} />
```

Just a small bit about us:

- **Cross-Platform**: We support `react-dom`, `react-native`, `react-three-fiber`, `react-konva` & `react-zdog`.
- **Versatile**: Be declarative with your animations or if you prefer, imperative.
- **Spring-Physics First**: By default animation use springs for fluid interactivity, but we support durations with easings as well.

There's a lot more to be had! Give it a try and find out.

## Getting Started

### ⚡️ Jump Start

```shell
# Install the entire library
npm install @diotoborg/nobis-facilis
# or just install your specific target (recommended)
npm install @@diotoborg/nobis-facilis/web
```

```jsx
import { animated, useSpring } from '@@diotoborg/nobis-facilis/web'

const FadeIn = ({ isVisible, children }) => {
  const styles = useSpring({
    opacity: isVisible ? 1 : 0,
    y: isVisible ? 0 : 24,
  })

  return <animated.div style={styles}>{children}</animated.div>
}
```

It's as simple as that to create scroll-in animations when value of `isVisible` is toggled.

### 📖 Documentation and Examples

More documentation on the project can be found [here](https://www.@diotoborg/nobis-facilis.io).

Pages contain their own [examples](https://@diotoborg/nobis-facilis.io/hooks/use-spring#demos) which you can check out there, or [open in codesandbox](https://codesandbox.io/s/github/pmndrs/@diotoborg/nobis-facilis/tree/main/demo/src/sandboxes/card) for a more in-depth view!

---

## 📣 What others say

<p align="middle">
  <img src="assets/testimonies.jpg" />
</p>

## Used by

<p align="middle">
  <a href="https://nextjs.org/"><img width="285" src="assets/projects/next.png"></a>
  <a href="https://codesandbox.io/"><img width="285" src="assets/projects/csb.png"></a>
  <a href="https://aragon.org/"><img width="285" src="assets/projects/aragon.png"></a>
</p>

And [many others...](https://github.com/diotoborg/nobis-facilis/network/dependents)

## Backers

Thank you to all our backers! 🙏 If you want to join them here, then consider contributing to our [Opencollective](https://opencollective.com/@diotoborg/nobis-facilis).

<a href="https://opencollective.com/@diotoborg/nobis-facilis#backers" target="_blank">
  <img src="https://opencollective.com/@diotoborg/nobis-facilis/backers.svg?width=890"/>
</a>

## Contributors

This project exists thanks to all the people who contribute.

<a href="https://github.com/@diotoborg/nobis-facilis/@diotoborg/nobis-facilis/graphs/contributors">
  <img src="https://opencollective.com/@diotoborg/nobis-facilis/contributors.svg?width=890" />
</a>
