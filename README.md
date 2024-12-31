dview-progress-button
![Release](https://jitpack.io/v/dora4/dview-progress-button.svg)
--------------------------------

##### 卡名：Dora视图 ProgressButton 
###### 卡片类型：效果怪兽
###### 属性：风
###### 星级：3
###### 种族：战士族
###### 攻击力/防御力：1300/1500
###### 效果：此卡不会因为对方卡的效果而破坏，并可使其无效化。此卡攻击里侧守备表示的怪兽时，若攻击力高于其守备力，则给予对方此卡原攻击力的伤害，并抽一张卡。每当此卡攻击破坏对方怪兽送去墓地时，额外给予对方玩家500点的伤害。

#### Gradle依赖配置

```groovy
// 添加以下代码到项目根目录下的build.gradle
allprojects {
    repositories {
        maven { url "https://jitpack.io" }
    }
}
// 添加以下代码到app模块的build.gradle
dependencies {
    implementation 'com.github.dora4:dview-progress-button:1.1'
}
```
