add_library(graph SHARED 
    analyse.c
    cobject3d.c
    color.c
    contour.c
    draw2dgraph.c
    draw3dcontour.c
    draw3dgraph.c
    fftn.c
    graph.c
    koord.c
    koord2d.c
    koord3d.c
    menu.c
    mydraw.c
    mydraw_2d.c
    mygraph.c
    myprog.c
    myrand.c
    neuzeichnen.c
    objects3d.c
    tfield.c
    ufield.c
    vector.c
    view3d.c
)
target_link_libraries(graph X11)
