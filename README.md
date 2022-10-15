# -1.0-
文件目录：
backup：游戏各项内容。每当进行一次修改，请将内容立即同步到此处。需要移动位置的时候，如果无法移动原游戏修改内容，此部分可作为最后的保障。
|-3.0SCENE+：3.0新添加的场景。先在这里封包，后续有修改再入scene资料夹。
|-basedata：3.0修改的内容备份。每当有新的文件产生，需要同步到这里。
|-music：3.0使用的音乐。3.0已改为外置。需要在这里保存一份。
|-original basedata：冗余备份。主要用于查找原始素材。
|-PAL3A basedata：冗余备份。主要用于查找原始素材。
|-Patcher：无效资料夹。
|-save：同步游戏存档。PC状况较稳定时不使用。
|-savepic：3.0快速存档使用的图片。
|-scene：3.0修改了的场景文件。每当有新的文件产生或被修改，需要同步到这里。
|-snd：3.0新添加的音效。需要在这里保存一份。
|-src：源代码。每隔一段时间，进行一次备份。
|-wusa：冗余备份。基本没有作用。
|-wusa_gdb：修改gdb文件的部分。3.0已改为外置。每隔一段时间，进行一次备份。
|-wusa_information：修改信息面板等使用的信息内容。先在这里修改，再同步到游戏。

document:游戏文档。先在此处设计，之后再予以实现。

install pack backup：一些必要文件的安装源。

temp document：提供一些制作过程中的参考。
|-敌方资料.xlsx：内含2.0的数据，可用于参考。
|-temp.txt：极重要，提供状态和一些索引，新增状态和一些代码逻辑时需要查看已占位内容，设计后要立即同步到这里

tools：补丁制作过程中使用的工具。
|-CPack：cpk封包和提取。
|-gdb+eff：冗余备份。特效和gdb修改。
|-hook framework：hook框架备份。
|-Patcher：官方Patcher，用于少量添加和更新cpk文件中的内容时。
|-position：辅助器。
|-sce：编写或修改sce脚本。其中的内容未必最新，如果是修改则要先从backup/scene复制过来，修改后应立即同步到backup/scene中。
|-scn：编写或修改scn。如果是修改则要先从backup/scene复制过来，修改后应立即同步到backup/scene中。
|-winhex：用于直接修改二进制文件。例如新建或者复制scn中的部分内容，使开发更加方便。或者修改存档文件等。
