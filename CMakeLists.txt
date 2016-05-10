cmake_minimum_required(VERSION 2.8.3)
project(canbus_interface_2)

find_package(catkin REQUIRED COMPONENTS message_generation)

add_message_files(DIRECTORY msg FILES CanFrame3.msg)
generate_messages()

catkin_package()

