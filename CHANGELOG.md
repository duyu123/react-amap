# 更新日志

## 0.2.3    - 2017-03-22

### 新增

* 新增 [MouseTool](https://elemefe.github.io/react-amap/components/mousetool) 鼠标工具插件；通过该插件，可进行鼠标画标记点、线、多边形、矩形、圆、距离量测、面积量测、拉框放大、拉框缩小等功能。

---

## 0.2.3-0  - 2017-03-16

### 修复

* 因为 React 框架的限制，`key` 属性另有所用，所以定义高德的 Key 时统一为 `amapkey`。详见[关于 key](https://elemefe.github.io/react-amap/articles/start#关于-key)

---

## 0.2.2 - 2017-03-16

### 新增

* Marker 组件新增可以定义 render 静态属性渲染外观；也在高德 Marker 实例挂载 render 方法动态渲染外观。

---

## 0.2.1 - 2017-03-15

### 优化

* 重新设计 Markers 接口，对标记的外观控制更灵活；本次更新不向下兼容。

---

## 0.2.0  - 2017-03-14

### 优化

* 所有组件接口（除 Markers）重新设计，开发者可以通过绑定事件获得高德原生实例。

---

## 0.0.1-rc.1 - 2017-02-23

### react-amap 发布