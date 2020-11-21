cmake_minimum_required(VERSION 2.8.3)
project(nova_robot)

find_package(catkin REQUIRED)

catkin_package()

###########
## Build ##
###########

# include_directories()

#############
## Install ##
#############

# install(DIRECTORY launch
#     DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION}
# )

install(DIRECTORY meshes
   DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION}
)

# install(DIRECTORY params
#     DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION}
# )

install(DIRECTORY xacro
    DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION}
)
