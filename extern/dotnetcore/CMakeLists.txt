# Script to Download and Install MS dot net core webservices

project(dotnetcore)
include(${CMAKE_ROOT}/Modules/ExternalProject.cmake)
ExternalProject_Add(
	GIT_REPOSITORY https://github.com/dotnet/cli.git
	GIT_TAG "master"
	GIT_PROGRESS 1                                    #report clone progress
	#SOURCE_DIR 
)
