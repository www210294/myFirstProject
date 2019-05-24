初始化

componentWillMount 初始化调用，只调用一次render 渲染页面
componentDidMount 第一次渲染后调用

更新

componentWillReceireProps 接收新的props时调用
shouldComponentUpdate state或props改变时调用
componentWillUpdate 将要更新时调用，可改变state的值render
componentDidUpdate 更新后调用

卸载

componentWillUnMount

作者：星冉
链接：https://juejin.im/post/5c734eaaf265da2d9262e957
来源：掘金
著作权归作者所有。商业转载请联系作者获得授权，非商业转载请注明出处。
