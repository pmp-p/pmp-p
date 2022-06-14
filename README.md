### Hi there 👋

- For those coming here to *use* Panda3D/CPython on android and browser, you need to clone PyDK and trigger the Github action CI
to get the artifacts for all android architectures ( ~400 MiB download ).

Once done with that you can seek for help on #Panda3D on libera irc (quick answer) or discord ( ymmv ).

Note : *all* pip modules compiled via pydk are ABI compatible with P4A from Kivy / Beeware packaging because it's CPython out of the box too.
 ** But you'll have to figure out how to load them by yourself and how to deal with API levels baseline differences. **

PyDK is for everyone and that means starting at API19 for me, keep and use your old tablets for education !

- For others well everything here is very experimental, async, unthreaded and Python centric.


- Looking for collaboration on C-Python ® for WebAssembly, or alternatives

Come and share  ! 
https://gitter.im/Wasm-Python/community

----

Already collaborated on :
* [Light and Versatile Graphics Library][lvgl] Micropython simulator


----

Currently porting pygame to Webassembly https://github.com/pygame/pygame/issues/718

Admin of http://github.com/pygame-web 

Creator of pygbag https://pypi.org/project/pygbag

----


[Brave Tip shortcut][tip]

[Direct support patreon][pat]


[tip]: https://github.com/pmp-p/pmp-p/issues/1
[pat]: https://www.patreon.com/pmpp
[lvgl]: https://sim.lvgl.io/v7/micropython/ports/javascript/bundle_out/index.html



