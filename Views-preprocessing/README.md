```
-> beforeRender demo_1
-> beforeRender demo_0
-> beforeRender demo_2
-> Render demo_0
-> Render demo_2
-> Render demo_1
-> Render demo_0
-> afterRender demo_0
-> afterRender demo_2
-> afterRender demo_1

-----------------------------------------------------------------------------------------------------------
[time:000007674] [memory:000035444] {main} (/var/www/PHP-code-snippets/Views-preprocessing/index.php)
[time:000003803] [memory:000016020]  └── Controller::prepareViews (/var/www/PHP-code-snippets/Views-preprocessing/index.php)
[time:000002709] [memory:000008824]  |    └── Controller::prepareView (/var/www/PHP-code-snippets/Views-preprocessing/index.php)
[time:000000127] [memory:000000000]  |    |    └── in_array (/var/www/PHP-code-snippets/Views-preprocessing/index.php)
[time:000002357] [memory:000006004]  |    |    └── Controller::_includeView (/var/www/PHP-code-snippets/Views-preprocessing/index.php)
[time:000000039] [memory:000002056]  |    |    |    └── include (/var/www/PHP-code-snippets/Views-preprocessing/views/demo_0.phtml)
[time:000000027] [memory:000000088]  |    |    └── View::__construct (/var/www/PHP-code-snippets/Views-preprocessing/index.php)
[time:000001004] [memory:000006708]  |    └── Controller::prepareView (/var/www/PHP-code-snippets/Views-preprocessing/index.php)
[time:000000024] [memory:000000000]  |    |    └── in_array (/var/www/PHP-code-snippets/Views-preprocessing/index.php)
[time:000000850] [memory:000005344]  |    |    └── Controller::_includeView (/var/www/PHP-code-snippets/Views-preprocessing/index.php)
[time:000000026] [memory:000001888]  |    |    |    └── include (/var/www/PHP-code-snippets/Views-preprocessing/views/demo_2.phtml)
[time:000000022] [memory:000000088]  |    |    └── View::__construct (/var/www/PHP-code-snippets/Views-preprocessing/index.php)
[time:000003630] [memory:000017424]  └── Controller::render (/var/www/PHP-code-snippets/Views-preprocessing/index.php)
[time:000000063] [memory:000000224]  |    └── Controller::_beforeRender (/var/www/PHP-code-snippets/Views-preprocessing/index.php)
[time:000000020] [memory:000000000]  |    |    └── Controller::beforeRender (/var/www/PHP-code-snippets/Views-preprocessing/index.php)
[time:000001646] [memory:000009680]  |    └── Controller::_viewsIterate (/var/www/PHP-code-snippets/Views-preprocessing/index.php)
[time:000001383] [memory:000009060]  |    |    └── View::beforeRender (/var/www/PHP-code-snippets/Views-preprocessing/index.php)
[time:000001269] [memory:000009060]  |    |    |    └── View::__call (/var/www/PHP-code-snippets/Views-preprocessing/index.php)
[time:000001215] [memory:000008768]  |    |    |    |    └── {closure} (/var/www/PHP-code-snippets/Views-preprocessing/views/demo_0.phtml)
[time:000001170] [memory:000008404]  |    |    |    |    |    └── Controller::prepareView (/var/www/PHP-code-snippets/Views-preprocessing/index.php)
[time:000000021] [memory:000000000]  |    |    |    |    |    |    └── in_array (/var/www/PHP-code-snippets/Views-preprocessing/index.php)
[time:000000666] [memory:000005676]  |    |    |    |    |    |    └── Controller::_includeView (/var/www/PHP-code-snippets/Views-preprocessing/index.php)
[time:000000026] [memory:000001912]  |    |    |    |    |    |    |    └── include (/var/www/PHP-code-snippets/Views-preprocessing/views/demo_1.phtml)
[time:000000025] [memory:000000088]  |    |    |    |    |    |    └── View::__construct (/var/www/PHP-code-snippets/Views-preprocessing/index.php)
[time:000000197] [memory:000000672]  |    |    |    |    |    |    └── Controller::processView (/var/www/PHP-code-snippets/Views-preprocessing/index.php)
[time:000000120] [memory:000000292]  |    |    |    |    |    |    |    └── View::beforeRender (/var/www/PHP-code-snippets/Views-preprocessing/index.php)
[time:000000070] [memory:000000292]  |    |    |    |    |    |    |    |    └── View::__call (/var/www/PHP-code-snippets/Views-preprocessing/index.php)
[time:000000024] [memory:000000000]  |    |    |    |    |    |    |    |    |    └── {closure} (/var/www/PHP-code-snippets/Views-preprocessing/views/demo_1.phtml)
[time:000000180] [memory:000000292]  |    |    └── View::beforeRender (/var/www/PHP-code-snippets/Views-preprocessing/index.php)
[time:000000068] [memory:000000292]  |    |    |    └── View::__call (/var/www/PHP-code-snippets/Views-preprocessing/index.php)
[time:000000021] [memory:000000000]  |    |    |    |    └── {closure} (/var/www/PHP-code-snippets/Views-preprocessing/views/demo_2.phtml)
[time:000000858] [memory:000003584]  |    └── include (/var/www/PHP-code-snippets/Views-preprocessing/layout/default.phtml)
[time:000000159] [memory:000000672]  |    |    └── Controller::processView (/var/www/PHP-code-snippets/Views-preprocessing/index.php)
[time:000000111] [memory:000000300]  |    |    |    └── View::render (/var/www/PHP-code-snippets/Views-preprocessing/index.php)
[time:000000065] [memory:000000292]  |    |    |    |    └── View::__call (/var/www/PHP-code-snippets/Views-preprocessing/index.php)
[time:000000021] [memory:000000000]  |    |    |    |    |    └── {closure} (/var/www/PHP-code-snippets/Views-preprocessing/views/demo_0.phtml)
[time:000000335] [memory:000001568]  |    |    └── Controller::processView (/var/www/PHP-code-snippets/Views-preprocessing/index.php)
[time:000000288] [memory:000001196]  |    |    |    └── View::render (/var/www/PHP-code-snippets/Views-preprocessing/index.php)
[time:000000245] [memory:000001188]  |    |    |    |    └── View::__call (/var/www/PHP-code-snippets/Views-preprocessing/index.php)
[time:000000201] [memory:000000896]  |    |    |    |    |    └── {closure} (/var/www/PHP-code-snippets/Views-preprocessing/views/demo_1.phtml)
[time:000000156] [memory:000000672]  |    |    |    |    |    |    └── Controller::processView (/var/www/PHP-code-snippets/Views-preprocessing/index.php)
[time:000000110] [memory:000000300]  |    |    |    |    |    |    |    └── View::render (/var/www/PHP-code-snippets/Views-preprocessing/index.php)
[time:000000065] [memory:000000292]  |    |    |    |    |    |    |    |    └── View::__call (/var/www/PHP-code-snippets/Views-preprocessing/index.php)
[time:000000021] [memory:000000000]  |    |    |    |    |    |    |    |    |    └── {closure} (/var/www/PHP-code-snippets/Views-preprocessing/views/demo_2.phtml)
[time:000000273] [memory:000000672]  |    |    └── Controller::processView (/var/www/PHP-code-snippets/Views-preprocessing/index.php)
[time:000000227] [memory:000000300]  |    |    |    └── View::render (/var/www/PHP-code-snippets/Views-preprocessing/index.php)
[time:000000183] [memory:000000292]  |    |    |    |    └── View::__call (/var/www/PHP-code-snippets/Views-preprocessing/index.php)
[time:000000022] [memory:000000000]  |    |    |    |    |    └── {closure} (/var/www/PHP-code-snippets/Views-preprocessing/views/demo_0.phtml)
[time:000000063] [memory:000000224]  |    └── Controller::_afterRender (/var/www/PHP-code-snippets/Views-preprocessing/index.php)
[time:000000020] [memory:000000000]  |    |    └── Controller::beforeRender (/var/www/PHP-code-snippets/Views-preprocessing/index.php)
[time:000000427] [memory:000002016]  |    └── Controller::_viewsIterate (/var/www/PHP-code-snippets/Views-preprocessing/index.php)
[time:000000114] [memory:000000296]  |    |    └── View::afterRender (/var/www/PHP-code-snippets/Views-preprocessing/index.php)
[time:000000068] [memory:000000292]  |    |    |    └── View::__call (/var/www/PHP-code-snippets/Views-preprocessing/index.php)
[time:000000021] [memory:000000000]  |    |    |    |    └── {closure} (/var/www/PHP-code-snippets/Views-preprocessing/views/demo_0.phtml)
[time:000000110] [memory:000000296]  |    |    └── View::afterRender (/var/www/PHP-code-snippets/Views-preprocessing/index.php)
[time:000000065] [memory:000000292]  |    |    |    └── View::__call (/var/www/PHP-code-snippets/Views-preprocessing/index.php)
[time:000000021] [memory:000000000]  |    |    |    |    └── {closure} (/var/www/PHP-code-snippets/Views-preprocessing/views/demo_2.phtml)
[time:000000109] [memory:000000296]  |    |    └── View::afterRender (/var/www/PHP-code-snippets/Views-preprocessing/index.php)
[time:000000065] [memory:000000292]  |    |    |    └── View::__call (/var/www/PHP-code-snippets/Views-preprocessing/index.php)
[time:000000021] [memory:000000000]  |    |    |    |    └── {closure} (/var/www/PHP-code-snippets/Views-preprocessing/views/demo_1.phtml)
[time:000000040] [memory:000000000]  └── forp_end (/var/www/PHP-code-snippets/Views-preprocessing/index.php)
-----------------------------------------------------------------------------------------------------------
```