remake_find_package(
  Qt5 REQUIRED
  COMPONENTS Widgets
  RESULT_VAR Qt5_FOUND
)

remake_add_executables(LINK seekthermal Qt5::Widgets)
