cmake_minimum_required(VERSION 3.0)
project(SPHINX_TEST)

add_custom_target(doc ALL COMMAND sphinx-build -b html . html)
