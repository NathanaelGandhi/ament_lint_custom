# ament_lint_custom
ROS2 package to include most of ament_lint_common (excludes uncrustify which doesnt play nicely with clang-format). Also adds gtest and deps.

## How do I use this?
1. clone into ros2_ws ```git clone https://github.com/NathanaelGandhi/ament_lint_custom.git```
2. add ```<test_depend>ament_lint_custom</test_depend>``` to your package.xml
