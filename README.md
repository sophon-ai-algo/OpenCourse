# 开放课程作业共享仓库

**一、介绍**

本仓库为算能与各高校、科研机构合作的深度学习开放课程作业共享仓库，欢迎各位同学和开发者共建参与。我们将遴选优秀的作业放在仓库首页展示介绍。

**二、提交方式**

1. Fork本仓库到您自己的repository；
2. 克隆您fork的仓库到您的本地，后续及时更新确保Fork版本与最新版同步；
3. 本地修改代码，在contrib目录下对应的机构名称文件夹下新建您个人用户的文件夹，将您的代码按照作业要求组织；
4. 提交您的本地修改到您个人的仓库；
5. 登录github个人仓库，点击Pull request按钮，提交PR申请。

**三、注意事项**

1. 您的个人文件夹根目录下应当包括关于作业内容详情或您对作业理解的README文档；
2. 若您的代码中包含或引用了其他开源仓库的代码，请您按照源仓库或代码的开源license要求添加好License声明及源仓库的链接或作者信息；

**四、License规则**

1. 若引用参考源项目的文件，且源项目已包含License文件则必须拷贝引用，否则在模型顶层目录下添加使用的深度学习框架或其他组件的必要的License；
2. 每个复制或修改于源项目的文件，都需要在源文件开头附上源项目的License头部声明，并在其下追加新增完整算能License声明

```
# ...... 源项目的License头部声明 ......
# ============================================================================
# Copyright 2022 Sophgo Technologies Co., Ltd
#
# Licensed under the Apache License, Version 2.0 (the "License");
# you may not use this file except in compliance with the License.
# You may obtain a copy of the License at
#
#     http://www.apache.org/licenses/LICENSE-2.0
#
# Unless required by applicable law or agreed to in writing, software
# distributed under the License is distributed on an "AS IS" BASIS,
# WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
# See the License for the specific language governing permissions and
# limitations under the License.
```

2、每个自己新编写的文件，都需要在源文件开头添加算能License声明

```
# Copyright 2022 Sophgo Technologies Co., Ltd
#
# Licensed under the Apache License, Version 2.0 (the "License");
# you may not use this file except in compliance with the License.
# You may obtain a copy of the License at
#
#     http://www.apache.org/licenses/LICENSE-2.0
#
# Unless required by applicable law or agreed to in writing, software
# distributed under the License is distributed on an "AS IS" BASIS,
# WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
# See the License for the specific language governing permissions and
# limitations under the License.
```

> 关于License声明时间，应注意：
>
> 1. 2021年新建的文件，应该是Copyright 2021 Sophgo Technologies Co.
> 2. Python文件的行注释符号为`#`，C/CPP文件中的注释符号为`//`

**五、编程规范**

- 规范标准

1. C++代码遵循google编程规范：[Google C++风格指南](https://zh-google-styleguide.readthedocs.io/en/latest/google-cpp-styleguide)([Google C++ Coding Guidelines](https://google.github.io/styleguide/cppguide.html))；单元测试遵循规范： [Googletest Primer](https://google.github.io/googletest/primer.html)。
2. Python代码遵循PEP8规范：[Python PEP 8 Coding Style](https://www.python.org/dev/peps/pep-0008/)；单元测试遵循规范：[pytest](https://docs.pytest.org/en/stable/)
3. Shell脚本遵循google编程规范：[Google Shell风格指南](https://zh-google-styleguide.readthedocs.io/en/latest/google-shell-styleguide/contents/)([Google Shell Style Guide](https://google.github.io/styleguide/shellguide.html))
4. git commit信息遵循规范：[Angular规范](https://docs.google.com/document/d/1QrDFcIiPjSLDn3EL15IJygNPiHORgU1_OOAqWjiDU5Y/edit#)

- 备注

1. C++代码中禁止使用printf，一律使用cout；
2. 内存管理尽量使用智能指针；
3. 控制第三方库依赖，如果引入第三方依赖，则需要提供第三方依赖安装和使用指导书；
4. 一律使用英文注释，注释率30%--40%，鼓励自注释；
5. 函数头必须有注释，说明函数作用，入参、出参；
6. 统一错误码，通过错误码可以确认那个分支返回错误；
7. 禁止出现打印一堆无影响的错误级别的日志。
