cmake_minimum_required(VERSION 3.4.1)

set(LIB_DIR ${PROJECT_SOURCE_DIR}/lib/${ANDROID_ABI})

# 项目信息
#project (vtk)

add_library(vtk-common-color STATIC IMPORTED)
set_target_properties(vtk-common-color
        PROPERTIES IMPORTED_LOCATION
        ${PROJECT_SOURCE_DIR}/lib/libvtkCommonColor-8.2.a)

add_library(vtk-common-computational-geometry STATIC IMPORTED)
set_target_properties(vtk-common-computational-geometry
        PROPERTIES IMPORTED_LOCATION
        ${PROJECT_SOURCE_DIR}/lib/libvtkCommonComputationalGeometry-8.2.a)

add_library(vtk-common-core STATIC IMPORTED)
set_target_properties(vtk-common-core
        PROPERTIES IMPORTED_LOCATION
        ${PROJECT_SOURCE_DIR}/lib/libvtkCommonCore-8.2.a)

add_library(vtk-common-data-model STATIC IMPORTED)
set_target_properties(vtk-common-data-model
        PROPERTIES IMPORTED_LOCATION
        ${PROJECT_SOURCE_DIR}/lib/libvtkCommonDataModel-8.2.a)

add_library(vtk-common-execution-model STATIC IMPORTED)
set_target_properties(vtk-common-execution-model
        PROPERTIES IMPORTED_LOCATION
        ${PROJECT_SOURCE_DIR}/lib/libvtkCommonExecutionModel-8.2.a)

add_library(vtk-common-math STATIC IMPORTED)
set_target_properties(vtk-common-math
        PROPERTIES IMPORTED_LOCATION
        ${PROJECT_SOURCE_DIR}/lib/libvtkCommonMath-8.2.a)

add_library(vtk-common-misc STATIC IMPORTED)
set_target_properties(vtk-common-misc
        PROPERTIES IMPORTED_LOCATION
        ${PROJECT_SOURCE_DIR}/lib/libvtkCommonMisc-8.2.a)

add_library(vtk-common-system STATIC IMPORTED)
set_target_properties(vtk-common-system
        PROPERTIES IMPORTED_LOCATION
        ${PROJECT_SOURCE_DIR}/lib/libvtkCommonSystem-8.2.a)

add_library(vtk-common-transforms STATIC IMPORTED)
set_target_properties(vtk-common-transforms
        PROPERTIES IMPORTED_LOCATION
        ${PROJECT_SOURCE_DIR}/lib/libvtkCommonTransforms-8.2.a)

add_library(vtk-dicom-parser STATIC IMPORTED)
set_target_properties(vtk-dicom-parser
        PROPERTIES IMPORTED_LOCATION
        ${PROJECT_SOURCE_DIR}/lib/libvtkDICOMParser-8.2.a)

add_library(vtk-double-conversion STATIC IMPORTED)
set_target_properties(vtk-double-conversion
        PROPERTIES IMPORTED_LOCATION
        ${PROJECT_SOURCE_DIR}/lib/libvtkdoubleconversion-8.2.a)

add_library(vtk-expat STATIC IMPORTED)
set_target_properties(vtk-expat
        PROPERTIES IMPORTED_LOCATION
        ${PROJECT_SOURCE_DIR}/lib/libvtkexpat-8.2.a)

add_library(vtk-filters-core STATIC IMPORTED)
set_target_properties(vtk-filters-core
        PROPERTIES IMPORTED_LOCATION
        ${PROJECT_SOURCE_DIR}/lib/libvtkFiltersCore-8.2.a)

add_library(vtk-filters-extraction STATIC IMPORTED)
set_target_properties(vtk-filters-extraction
        PROPERTIES IMPORTED_LOCATION
        ${PROJECT_SOURCE_DIR}/lib/libvtkFiltersExtraction-8.2.a)

add_library(vtk-filters-general STATIC IMPORTED)
set_target_properties(vtk-filters-general
        PROPERTIES IMPORTED_LOCATION
        ${PROJECT_SOURCE_DIR}/lib/libvtkFiltersGeneral-8.2.a)

add_library(vtk-filters-geometry STATIC IMPORTED)
set_target_properties(vtk-filters-geometry
        PROPERTIES IMPORTED_LOCATION
        ${PROJECT_SOURCE_DIR}/lib/libvtkFiltersGeometry-8.2.a)

add_library(vtk-filters-modeling STATIC IMPORTED)
set_target_properties(vtk-filters-modeling
        PROPERTIES IMPORTED_LOCATION
        ${PROJECT_SOURCE_DIR}/lib/libvtkFiltersModeling-8.2.a)

add_library(vtk-filters-sources STATIC IMPORTED)
set_target_properties(vtk-filters-sources
        PROPERTIES IMPORTED_LOCATION
        ${PROJECT_SOURCE_DIR}/lib/libvtkFiltersSources-8.2.a)

add_library(vtk-filters-statistics STATIC IMPORTED)
set_target_properties(vtk-filters-statistics
        PROPERTIES IMPORTED_LOCATION
        ${PROJECT_SOURCE_DIR}/lib/libvtkFiltersStatistics-8.2.a)

add_library(vtk-free-type STATIC IMPORTED)
set_target_properties(vtk-free-type
        PROPERTIES IMPORTED_LOCATION
        ${PROJECT_SOURCE_DIR}/lib/libvtkfreetype-8.2.a)

add_library(vtk-glwe STATIC IMPORTED)
set_target_properties(vtk-glwe
        PROPERTIES IMPORTED_LOCATION
        ${PROJECT_SOURCE_DIR}/lib/libvtkglew-8.2.a)

add_library(vtk-imaging-core STATIC IMPORTED)
set_target_properties(vtk-imaging-core
        PROPERTIES IMPORTED_LOCATION
        ${PROJECT_SOURCE_DIR}/lib/libvtkImagingCore-8.2.a)

add_library(vtk-imaging-fourier STATIC IMPORTED)
set_target_properties(vtk-imaging-fourier
        PROPERTIES IMPORTED_LOCATION
        ${PROJECT_SOURCE_DIR}/lib/libvtkImagingFourier-8.2.a)

add_library(vtk-imaging-math STATIC IMPORTED)
set_target_properties(vtk-imaging-math
        PROPERTIES IMPORTED_LOCATION
        ${PROJECT_SOURCE_DIR}/lib/libvtkImagingMath-8.2.a)

add_library(vtk-infovis-core STATIC IMPORTED)
set_target_properties(vtk-infovis-core
        PROPERTIES IMPORTED_LOCATION
        ${PROJECT_SOURCE_DIR}/lib/libvtkInfovisCore-8.2.a)

add_library(vtk-interaction-style STATIC IMPORTED)
set_target_properties(vtk-interaction-style
        PROPERTIES IMPORTED_LOCATION
        ${PROJECT_SOURCE_DIR}/lib/libvtkInteractionStyle-8.2.a)

add_library(vtk-io-core STATIC IMPORTED)
set_target_properties(vtk-io-core
        PROPERTIES IMPORTED_LOCATION
        ${PROJECT_SOURCE_DIR}/lib/libvtkIOCore-8.2.a)

add_library(vtk-io-geometry STATIC IMPORTED)
set_target_properties(vtk-io-geometry
        PROPERTIES IMPORTED_LOCATION
        ${PROJECT_SOURCE_DIR}/lib/libvtkIOGeometry-8.2.a)

add_library(vtk-io-image STATIC IMPORTED)
set_target_properties(vtk-io-image
        PROPERTIES IMPORTED_LOCATION
        ${PROJECT_SOURCE_DIR}/lib/libvtkIOImage-8.2.a)

add_library(vtk-io-infovis STATIC IMPORTED)
set_target_properties(vtk-io-infovis
        PROPERTIES IMPORTED_LOCATION
        ${PROJECT_SOURCE_DIR}/lib/libvtkIOInfovis-8.2.a)

add_library(vtk-io-legacy STATIC IMPORTED)
set_target_properties(vtk-io-legacy
        PROPERTIES IMPORTED_LOCATION
        ${PROJECT_SOURCE_DIR}/lib/libvtkIOLegacy-8.2.a)

add_library(vtk-io-ply STATIC IMPORTED)
set_target_properties(vtk-io-ply
        PROPERTIES IMPORTED_LOCATION
        ${PROJECT_SOURCE_DIR}/lib/libvtkIOPLY-8.2.a)

add_library(vtk-io-xml STATIC IMPORTED)
set_target_properties(vtk-io-xml
        PROPERTIES IMPORTED_LOCATION
        ${PROJECT_SOURCE_DIR}/lib/libvtkIOXML-8.2.a)

add_library(vtk-io-xml-parser STATIC IMPORTED)
set_target_properties(vtk-io-xml-parser
        PROPERTIES IMPORTED_LOCATION
        ${PROJECT_SOURCE_DIR}/lib/libvtkIOXMLParser-8.2.a)

add_library(vtk-jpeg STATIC IMPORTED)
set_target_properties(vtk-jpeg
        PROPERTIES IMPORTED_LOCATION
        ${PROJECT_SOURCE_DIR}/lib/libvtkjpeg-8.2.a)

add_library(vtk-libxml2 STATIC IMPORTED)
set_target_properties(vtk-libxml2
        PROPERTIES IMPORTED_LOCATION
        ${PROJECT_SOURCE_DIR}/lib/libvtklibxml2-8.2.a)

add_library(vtk-lz4 STATIC IMPORTED)
set_target_properties(vtk-lz4
        PROPERTIES IMPORTED_LOCATION
        ${PROJECT_SOURCE_DIR}/lib/libvtklz4-8.2.a)

add_library(vtk-lzma STATIC IMPORTED)
set_target_properties(vtk-lzma
        PROPERTIES IMPORTED_LOCATION
        ${PROJECT_SOURCE_DIR}/lib/libvtklzma-8.2.a)

add_library(vtk-metaio STATIC IMPORTED)
set_target_properties(vtk-metaio
        PROPERTIES IMPORTED_LOCATION
        ${PROJECT_SOURCE_DIR}/lib/libvtkmetaio-8.2.a)

add_library(vtk-parallel-core STATIC IMPORTED)
set_target_properties(vtk-parallel-core
        PROPERTIES IMPORTED_LOCATION
        ${PROJECT_SOURCE_DIR}/lib/libvtkParallelCore-8.2.a)

add_library(vtk-png STATIC IMPORTED)
set_target_properties(vtk-png
        PROPERTIES IMPORTED_LOCATION
        ${PROJECT_SOURCE_DIR}/lib/libvtkpng-8.2.a)

add_library(vtk-rendering-core STATIC IMPORTED)
set_target_properties(vtk-rendering-core
        PROPERTIES IMPORTED_LOCATION
        ${PROJECT_SOURCE_DIR}/lib/libvtkRenderingCore-8.2.a)

add_library(vtk-rendering-freetype STATIC IMPORTED)
set_target_properties(vtk-rendering-freetype
        PROPERTIES IMPORTED_LOCATION
        ${PROJECT_SOURCE_DIR}/lib/libvtkRenderingFreeType-8.2.a)

add_library(vtk-rendering-opengl2 STATIC IMPORTED)
set_target_properties(vtk-rendering-opengl2
        PROPERTIES IMPORTED_LOCATION
        ${PROJECT_SOURCE_DIR}/lib/libvtkRenderingOpenGL2-8.2.a)

add_library(vtk-rendering-volume STATIC IMPORTED)
set_target_properties(vtk-rendering-volume
        PROPERTIES IMPORTED_LOCATION
        ${PROJECT_SOURCE_DIR}/lib/libvtkRenderingVolume-8.2.a)

add_library(vtk-rendering-volume-opengl2 STATIC IMPORTED)
set_target_properties(vtk-rendering-volume-opengl2
        PROPERTIES IMPORTED_LOCATION
        ${PROJECT_SOURCE_DIR}/lib/libvtkRenderingVolumeOpenGL2-8.2.a)

add_library(vtk-sys STATIC IMPORTED)
set_target_properties(vtk-sys
        PROPERTIES IMPORTED_LOCATION
        ${PROJECT_SOURCE_DIR}/lib/libvtksys-8.2.a)

add_library(vtk-texting-rendering STATIC IMPORTED)
set_target_properties(vtk-texting-rendering
        PROPERTIES IMPORTED_LOCATION
        ${PROJECT_SOURCE_DIR}/lib/libvtkTestingRendering-8.2.a)

add_library(vtk-tiff STATIC IMPORTED)
set_target_properties(vtk-tiff
        PROPERTIES IMPORTED_LOCATION
        ${PROJECT_SOURCE_DIR}/lib/libvtktiff-8.2.a)


add_library(vtk-zlib STATIC IMPORTED)
set_target_properties(vtk-zlib
        PROPERTIES IMPORTED_LOCATION
        ${PROJECT_SOURCE_DIR}/lib/libvtkzlib-8.2.a)
#53 more libraries from lib folder

add_library(vtk-lib
        SHARED
        ${PROJECT_SOURCE_DIR}/vtk-lib.cpp)

# 日志库
find_library(log-lib log)

#引用頭文件
target_include_directories(vtk-lib
        PRIVATE
        ${PROJECT_SOURCE_DIR}/include/vtk-8.2)

target_link_libraries(
        vtk-lib
        -Wl,--start-group -L ${TARGET_OUT}
        vtk-common-color
        vtk-common-computational-geometry
        vtk-common-core
        vtk-common-data-model
        vtk-common-execution-model
        vtk-common-math
        vtk-common-misc
        vtk-common-system
        vtk-common-transforms
        vtk-dicom-parser
        vtk-double-conversion
        vtk-expat
        vtk-filters-core
        vtk-filters-extraction
        vtk-filters-general
        vtk-filters-geometry
        vtk-filters-modeling
        vtk-filters-sources
        vtk-filters-statistics
        vtk-free-type
        vtk-glwe
        vtk-imaging-core
        vtk-imaging-fourier
        vtk-imaging-math
        vtk-infovis-core
        vtk-interaction-style
        vtk-io-core
        vtk-io-geometry
        vtk-io-image
        vtk-io-infovis
        vtk-io-legacy
        vtk-io-ply
        vtk-io-xml
        vtk-io-xml-parser
        vtk-jpeg
        vtk-libxml2
        vtk-lz4
        vtk-lzma
        vtk-metaio
        vtk-parallel-core
        vtk-png
        vtk-rendering-core
        vtk-rendering-freetype
        vtk-rendering-opengl2
        vtk-rendering-volume
        vtk-rendering-volume-opengl2
        vtk-sys
        vtk-texting-rendering
        vtk-tiff
        vtk-zlib
        #53 more libraries names
        -Wl,--end-group
        ${log-lib}
)