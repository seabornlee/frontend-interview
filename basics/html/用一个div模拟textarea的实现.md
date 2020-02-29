**首先，为什么要这么做？textarea 有什么不足？**
textarea 默认不能根据内容自适应高度。
textarea 通过 `cols` 和 `rows` 控制显示，内容超出时会显示滚动条。
只能通过 JavaScript 来实现。

**那 div 怎么模拟 textarea 呢？**
需要解决如下几个问题：
* 怎么可编辑
* 怎么显示得像文本框
* 怎么获取内容

1. 用 div 用 `contenteditable=true` 即可模拟多行文本框，也可以设为 `plaintext-only`；
2. 默认高度只有一行文本的高度，并且不像输入框。需要添加样式 `min-height` 使其拥有默认的高度；
3. 要用 `innerText` 而不是 `innerHTML` 来获取输入的内容，因为输入回车时，实际上 DOM 里是生成了 `div` 节点，可以自己试一下。

<iframe
     src="https://codesandbox.io/embed/suspicious-frog-dfquv?fontsize=14&hidenavigation=1&theme=dark"
     style="width:100%; height:500px; border:0; border-radius: 4px; overflow:hidden;"
     title="suspicious-frog-dfquv"
     allow="geolocation; microphone; camera; midi; vr; accelerometer; gyroscope; payment; ambient-light-sensor; encrypted-media; usb"
     sandbox="allow-modals allow-forms allow-popups allow-scripts allow-same-origin"></iframe>

