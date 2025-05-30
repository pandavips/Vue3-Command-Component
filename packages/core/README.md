
[文档网站](https://pandavips.github.io/Vue3-Command-Component/)

## 安装

通过你项目使用的包管理器进行安装

::: code-group

```bash [npm]
$ npm install vue3-command-component
```

```bash [yarn]
$ yarn add vue3-command-component
```

```bash [pnpm]
$ pnpm add vue3-command-component
```

```bash [bun]
$ bun add vue3-command-component
```

:::


多嘴一句,建议你使用`Anthony Fu`的[`@antfu/ni`](https://www.npmjs.com/package/@antfu/ni)

```bash
npm i -g @antfu/ni
```

然后你就可以无视包管理器差异了
```bash
ni vue3-command-component
```


## 使用

现在你可以直接使用了。

```jsx
import { useElementPlusDialog } from "vue3-command-component";

const CommandDialog=useElementPlusDialog()

const Content=defineComponent({
  render(){
    return <div>弹窗内容</div>
  }
})

CommandDialog(<Content />)
```
更多示例请参见[示例](https://pandavips.github.io/Vue3-Command-Component/example/)
