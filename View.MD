# View

## Views

### ImageView

1. [PhotoView](https://github.com/Baseflow/PhotoView) 支持缩放手势, ViewPager
2. [PhotoDraweeView](https://github.com/ongakuer/PhotoDraweeView) 同上, Fresco专用
3. [subsampling-scale-image-view](https://github.com/davemorrissey/subsampling-scale-image-view) 同1, 但支持旋转, 建议大图专用, 二次采样, 支持 ViewPager, 虽然没写支持 ViewPager2, 但是个人实测支持且不冲突
4. [BigImageViewer](https://github.com/Piasy/BigImageViewer) 大图浏览, 支持GIF, 支持共享元素变换动画, 支持 Picasso/Glide/Fresco
5. [bm-x/PhotoView](https://github.com/bm-x/PhotoView) 中文文档, 支持放大旋转, 共享元素动画, 但是库已经年代久远缺乏更新了
6. [BigImageViewPager](https://github.com/SherlockGougou/BigImageViewPager) 中文文档, 支持超大超长图, 实现是 Viewpager

---

### Util Views

1. [ShapeOfView](https://github.com/florent37/ShapeOfView) 易上手的`自定义形状`的 view, 支持自定义 path
2. [Motion-ShapeOfView](https://github.com/florent37/Motion-ShapeOfView) 关于如何让上面那个库配合 MotionLayout 动起来这件事
3. [EnFloatingView](https://github.com/leotyndale/EnFloatingView) 应用内`浮窗`实现, 无需权限
4. [material-dialogs](https://github.com/afollestad/material-dialogs) 简单省心的 `MaterialDialog` 要这一个就足够了

## Navigation

### 较为个性的

1. [ExpandableBottomBar](https://github.com/st235/ExpandableBottomBar) 支持NavController, Coordinator Layout

    ```groovy
    implementation 'com.github.st235:expandablebottombar:X.X'
    ```

    ![ExpandableBottomBar](https://cdn.jsdelivr.net/gh/zsqw123/cdn@master/picCDN/20210222233658.gif)
2. [BubbleTabBar](https://github.com/akshay2211/BubbleTabBar)  效果同上, 支持NavController
3. [AnimatedBottomBar](https://github.com/Droppers/AnimatedBottomBar)  适配 ViewPager/ViewPager2 极为方便, 支持动态增删及禁用部分

    ```groovy
    implementation 'nl.joery.animatedbottombar:library:1.0.9'
    ```

    ![AnimatedBottomBar](https://cdn.jsdelivr.net/gh/zsqw123/cdn@master/picCDN/20210222235248.gif)
4. [SmoothBottomBar](https://github.com/ibrahimsn98/SmoothBottomBar)

    ```groovy
    // maven { url 'https://jitpack.io' }
    implementation 'com.github.ibrahimsn98:SmoothBottomBar:1.7.6'
    ```

   ![SmoothBottomBar](https://cdn.jsdelivr.net/gh/zsqw123/cdn@master/picCDN/20210222235738.gif)
5. [Morph Bottom Navigation](https://github.com/tommybuonomo/morph-bottom-navigation)

    ```groovy
    implementation 'com.tbuonomo:morph-bottom-navigation:1.0.1'
    ```

    ![Morph Bottom Navigation](https://cdn.jsdelivr.net/gh/zsqw123/cdn@master/picCDN/20210222235005.gif)

---

### 普普通通的

这种都是遵循 md, 没啥新意不做展示, 我个人看腻了, 不喜欢awa, 前两个有中文介绍.

1. [PagerBottomTabStrip](https://github.com/tyzlmjj/PagerBottomTabStrip)
2. [BottomNavigationViewEx](https://github.com/ittianyu/BottomNavigationViewEx)
3. [BottomNavigation](https://github.com/Ashok-Varma/BottomNavigation)
4. [ahbottomnavigation](https://github.com/aurelhubert/ahbottomnavigation)
5. [Material-BottomNavigation](https://github.com/sephiroth74/Material-BottomNavigation)
