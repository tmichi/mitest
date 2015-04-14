SET ( include_files TestCase.hpp TestSuite.hpp )
INSTALL ( FILES ${include_files}
          DESTINATION include/mi
          PERMISSIONS OWNER_READ GROUP_READ WORLD_READ )

