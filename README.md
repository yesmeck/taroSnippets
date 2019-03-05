# taroSnippets

taroSnippets 是一款快速生成 taro 页面结构的用户代码片段插件

效果图:

![图片](./images/taroSnippets.gif)

> taropage

```javascript
import Taro from '@tarojs/taro';
import { View, Button } from '@tarojs/components';

export default class Index extends Taro.Component {
  constructor() {
    super(...arguments);
  }
  componentWillMount() {}
  render() {
    return (
      <View>
        <Button>template</Button>
      </View>
    );
  }
}
```
