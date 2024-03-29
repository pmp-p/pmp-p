### Hi there !

NOTE : pydk for python+webassembly is getting obsoleted by pygbag which will allow soon to load pygame/Harfang3D/Panda3d/raylib CPython wheels directly from http servers. pygbag wasm modules are compatible with WASM 1.0 (mvp) to support older browsers ( as old as Android 4.4/Chrome 81 ), unlike pyodide's ones.


- For those coming here to *use* Panda3D/CPython on android and browser, you need to clone PyDK and trigger the Github action CI
to get the artifacts for all android architectures ( ~400 MiB download ).

Once done with that you can seek for help on #Panda3D discord.

Note : *all* pip modules compiled via pydk are ABI compatible with P4A from Kivy / Beeware packaging because it's CPython out of the box too.
 ** But you'll have to figure out how to load them by yourself and how to deal with API levels baseline differences. **

PyDK is for everyone and that means starting at API19 ( Android Kitkat 4.4) for me, keep and use your old tablets for education and DIY !

If you only want to support recent Android and their store then use Kivy/Beeware/Chaquopy instead.

- Everything here is very experimental, async, unthreaded and Python centric.

- I'm not interested in concurrency except when it leads to better handling of parallelism (subinterpreters-multicore/distributed computing).

- Looking for collaboration on CPython for WebAssembly, or soft-realtime Python alternatives (including trasnpilation).

Come and share (French/English)  ! 
https://gitter.im/Wasm-Python/community

----

Already collaborated on :
* [Light and Versatile Graphics Library][lvgl] Micropython simulator


----

Currently porting pygame-ce to Webassembly : https://github.com/pygame-community/pygame-ce/issues/540

Currently porting Harfang3D to Webassembly : https://github.com/harfang3d/harfang-wasm

Admin of http://github.com/pygame-web 

Creator of pygbag https://pypi.org/project/pygbag

----

![Profile Stats](https://github-readme-stats.vercel.app/api?username=pmp-p&theme=dark&hide_border=1&show_icons=true)


<a href="https://paypal.me/pmpp" target="_blank"><img src="https://img.shields.io/static/v1?logo=paypal&label=&message=donate&color=slategrey"></a> for 🍻 🍺

[opencollective][oc] for long run porting effort, not only wasm but native too !


[Direct support patreon][pat] if you want support for educative tools

[Brave Tip shortcut][tip] if you'd like to see some Web3+python someday


[tip]: https://github.com/pmp-p/pmp-p/issues/1
[pat]: https://www.patreon.com/pmpp
[oc]:https://opencollective.com/pythonseverywhere
[lvgl]: https://sim.lvgl.io/v7/micropython/ports/javascript/bundle_out/index.html



