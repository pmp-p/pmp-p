### Hi there !

NOTE : pydk for python+webassembly is getting obsoleted by pygbag which will allow soon to load pygame/Harfang3D/Panda3d/raylib CPython wheels directly from http servers.

- For those coming here to *use* Panda3D/CPython on android and browser, you need to clone PyDK and trigger the Github action CI
to get the artifacts for all android architectures ( ~400 MiB download ).

Once done with that you can seek for help on #Panda3D discord.

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

Currently porting pygame to Webassembly : https://github.com/pygame/pygame/issues/718

Currently porting Harfang3D to Webassembly : https://github.com/harfang3d/harfang-wasm

Admin of http://github.com/pygame-web 

Creator of pygbag https://pypi.org/project/pygbag

----

![Profile Stats](https://github-readme-stats.vercel.app/api?username=pmp-p&theme=dark&hide_border=1&show_icons=true)


[Brave Tip shortcut][tip]

[Direct support patreon][pat]

[opencollective][oc]

[tip]: https://github.com/pmp-p/pmp-p/issues/1
[pat]: https://www.patreon.com/pmpp
[oc]:https://opencollective.com/pythonseverywhere
[lvgl]: https://sim.lvgl.io/v7/micropython/ports/javascript/bundle_out/index.html



