# CMakeList.txt: проект CMake для HomeWorkBasic-10-2; включите исходный код и определения,
# укажите здесь логику для конкретного проекта.
#

# Добавьте источник в исполняемый файл этого проекта.
add_executable (HomeWorkBasic-10-2 "HomeWorkBasic-10-2.cpp" "HomeWorkBasic-10-2.h" "Figure.cpp" "Figure.h" "Triangle.cpp" "Triangle.h" "RightTriangle.cpp" "RightTriangle.h" "IsoscelesTriangle.cpp"
                "IsoscelesTriangle.h" "EquilateralTriangle.cpp" "EquilateralTriangle.h" "Quadrangle.cpp" "Quadrangle.h" "Parallelogram.cpp" "Parallelogram.h" "Rectangle.cpp" "Rectangle.h"
                "Rhomb.cpp" "Rhomb.h" "Square.cpp" "Square.h")

if (CMAKE_VERSION VERSION_GREATER 3.12)
  set_property(TARGET HomeWorkBasic-10-2 PROPERTY CXX_STANDARD 20)
endif()

# TODO: Добавьте тесты и целевые объекты, если это необходимо.
