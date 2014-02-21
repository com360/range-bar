RangeBar
=======
RangeBar是类似于增强版的SeekBar,可以不用SeekBar. RangeBar提供选择范围的值，而不是就单个值。值的选择范围通过标尺标示；thumb会跳到离的最近的标尺。 

开发者可以自定义如下属性（可以通过xml或者编码的方式）：

- bar color
- bar thickness
- tick height
- number of ticks
- connecting line thickness
- connecting line color
- thumb normal image
- thumb pressed image

如果下面的几个属性被指定，thumb图片将被忽略掉，被换成一个圆形的颜色区域：

- thumb radius
- thumb normal color
- thumb pressed color

最后，如下的属性必须编码的方式实现，而不能通过XML：
- thumb indices (thumb在RangeBar的位置)

支持 API Level 7 和以上.

如需更多信息，请点击下面的链接查看Github Wiki页面.

https://github.com/edmodo/range-bar/wiki

![ScreenShot](http://i.imgur.com/q85GhRjl.png)

License
=======
Copyright 2013, Edmodo, Inc. 

Licensed under the Apache License, Version 2.0 (the "License"); you may not use this work except in compliance with the License.
You may obtain a copy of the License in the LICENSE file, or at:

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.

贡献力量
=======

我们非常欢迎大家参与我们的项目开发。在我们接受你的pull request之前，请同意我们独有的贡献协议。这个简短的形式包括了我们岁基本的要求，同时它也有助于你成为一个优秀的贡献者。谢谢大家！

http://goo.gl/gfj6Mb
