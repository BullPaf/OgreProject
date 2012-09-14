noinst_HEADERS= AdvancedOgreFramework.hpp AppState.hpp AppStateManager.hpp MenuState.hpp GameState.hpp PauseState.hpp DemoApp.hpp DotSceneLoader.hpp rapidxml.hpp
 
bin_PROGRAMS= OgreApp
 OgreApp_CPPFLAGS= -I$(top_srcdir)
 OgreApp_SOURCES= AdvancedOgreFramework.cpp AppStateManager.cpp MenuState.cpp GameState.cpp PauseState.cpp DemoApp.cpp DotSceneLoader.cpp main.cpp
 OgreApp_CXXFLAGS= $(OGRE_CFLAGS) $(OIS_CFLAGS) $(OGRE_TERRAIN_CFLAGS)
 OgreApp_LDADD= $(OGRE_LIBS) $(OIS_LIBS) $(OGRE_TERRAIN_LIBS)
 
 EXTRA_DIST = bootstrap
 AUTOMAKE_OPTIONS = foreign
