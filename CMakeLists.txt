# Copyright (C) 2007-2012 LuaDist.
# Created by Peter Drahoš
# Redistribution and use of this file is allowed according to the terms of the MIT license.
# For details see the COPYRIGHT file distributed with LuaDist.
# Please note that the package source code is licensed under its own license.

project ( versium NONE )
cmake_minimum_required ( VERSION 2.8)
include ( cmake/dist.cmake )
include ( lua )

install_lua_module ( versium.errors lua/versium/errors.lua )
install_lua_module ( versium.filedir lua/versium/filedir.lua )
install_lua_module ( versium.util lua/versium/util.lua )
install_lua_module ( versium.virtual lua/versium/virtual.lua )
install_doc ( doc/ )
install_data ( LICENSE.txt )
