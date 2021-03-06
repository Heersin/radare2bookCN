# Summary

* [简介](README.md)
   * [历史](first_steps/history.md)
   * [Radare2框架](first_steps/overview.md)
   * [下载radare2](first_steps/getting_radare.md)
   * [编译与可移植性](first_steps/compilation_portability.md)
   * [Compilation on Windows](first_steps/windows_compilation.md)
   * [Compilation on Android](first_steps/compilation_android.md)
   * [用户界面](first_steps/ui.md)
* [快速上手](first_steps/intro.md)
   * [命令行选项](first_steps/commandline_flags.md)
   * [命令格式](first_steps/command_format.md)
   * [表达式](first_steps/expressions.md)
   * [基本的debug操作](first_steps/basic_debugger_session.md)
   * [Contributing to radare2](first_steps/contributing.md)
* [配置](configuration/intro.md)
   * [Colors](configuration/colors.md)
   * [配置项](configuration/evars.md)
   * [radare2相关文件](configuration/files.md)
* [基本命令](basic_commands/intro.md)
   * [定位](basic_commands/seeking.md)
   * [块大小](basic_commands/block_size.md)
   * [节区](basic_commands/sections.md)
   * [映射文件](basic_commands/mapping_files.md)
   * [输出模式](basic_commands/print_modes.md)
   * [标记符（Flags）](basic_commands/flags.md)
   * [写入数据](basic_commands/write.md)
   * [Zoom模式](basic_commands/zoom.md)
   * [复制/粘贴](basic_commands/yank_paste.md)
   * [字节比较](basic_commands/comparing_bytes.md)
   * [SDB](basic_commands/sdb.md)
   * [Dietline](basic_commands/dietline.md)
* [可视化模式](visual_mode/intro.md)
   * [反汇编界面](visual_mode/visual_disassembly.md)
   * [汇编界面](visual_mode/visual_assembler.md)
   * [变量编辑器界面](visual_mode/visual_configuration_editor.md)
   * [可视化面板](visual_mode/visual_panels.md)
* [搜索字节](search_bytes/intro.md)
   * [基本的搜索用法](search_bytes/basic_searches.md)
   * [配置搜索引擎](search_bytes/configurating_the_search.md)
   * [搜索重复字节序列](search_bytes/pattern_search.md)
   * [搜索中的自动化](search_bytes/automation.md)
   * [回溯搜索](search_bytes/backward_search.md)
   * [搜索汇编指令](search_bytes/search_in_assembly.md)
   * [Searching for AES Keys](search_bytes/searching_aes_keys.md)
* [反汇编](disassembling/intro.md)
   * [为反汇编添加元数据](disassembling/adding_metadata.md)
   * [ESIL](disassembling/esil.md)
* [分析](analysis/intro.md)
   * [代码分析](analysis/code_analysis.md)
   * [变量](analysis/variables.md)
   * [类型](analysis/types.md)
   * [调用约定](analysis/calling_conventions.md)
   * [虚函数表](analysis/vtables.md)
   * [系统调用](analysis/syscalls.md)
   * [模拟执行](analysis/emulation.md)
   * [Symbols 信息](analysis/symbols.md)
   * [函数签名](signatures/zignatures.md)
   * [图形化命令](analysis/graphs.md)
* [脚本化](scripting/intro.md)
   * [循环(Loops)](scripting/loops.md)
   * [宏(Macros)](scripting/macros.md)
   * [R2pipe](scripting/r2pipe.md)
* [调试器](debugger/intro.md)
   * [入门](debugger/getting_started.md)
   * [从ida, GDB 或 WinDBG迁移到radare2](debugger/migration.md)
   * [寄存器（Registers）](debugger/registers.md)
   * [内存映射（Memory Maps）](debugger/memory_maps.md)
   * [堆（Heap）](debugger/heap.md)
   * [文件（Files）](debugger/files.md)
   * [反向调试](debugger/revdebug.md)
   * [Windows消息（Messages）](debugger/windows_messages.md)
* [远程访问](debugger/remoting_capabilities.md)
   * [远程GDB调试](debugger/remote_gdb.md)
   * [远程WinDbg](debugger/windbg.md)
* [命令行工具](tools/intro.md)
   * [Rax2](tools/rax2/intro.md)
   * [Rafind2](tools/rafind2/intro.md)
   * [Rarun2](tools/rarun2/intro.md)
   * [Rabin2](tools/rabin2/intro.md)
      * [文件信息识别](tools/rabin2/file_identification.md)
      * [入口点（EP）](tools/rabin2/entrypoints.md)
      * [导入（Imports）](tools/rabin2/imports.md)
      * [导出（Exports）](tools/rabin2/exports.md)
      * [Symbols (exports)](tools/rabin2/symbols.md)
      * [库文件](tools/rabin2/libraries.md)
      * [字符串（String）](tools/rabin2/strings.md)
      * [节区（Sections）](tools/rabin2/program_sections.md)
   * [Radiff2](tools/radiff2/intro.md)
      * [二进制文件比较](tools/radiff2/binary_diffing.md)
   * [Rasm2](tools/rasm2/intro.md)
      * [汇编](tools/rasm2/assemble.md)
      * [反汇编](tools/rasm2/disassemble.md)
      * [配置项](tools/rasm2/config.md)
   * [Ragg2](tools/ragg2/ragg2.md)
      * [Language](tools/ragg2/lang.md)
   * [Rahash2](tools/rahash2/intro.md)
      * [Rahash Tool](tools/rahash2/rahash_tool.md)
* [插件](plugins/intro.md)
   * [IO 插件](plugins/ioplugins.md)
   * [Asm 插件](plugins/dev-asm.md)
   * [Analysis 插件](plugins/dev-anal.md)
   * [Bin 插件](plugins/dev-bin.md)
   * [其它插件](plugins/dev-other.md)
   * [Python插件](plugins/python.md)
   * [对插件进行调试](plugins/debug.md)
   * [测试](plugins/testing.md)
   * [打包](plugins/r2pm.md)
* [Crackmes](crackmes/intro.md)
   * [IOLI](crackmes/ioli/intro.md)
       * [IOLI 0x00](crackmes/ioli/ioli_0x00.md)
       * [IOLI 0x01](crackmes/ioli/ioli_0x01.md)
   * [Avatao R3v3rs3 4](crackmes/avatao/01-reverse4/intro.md)
       * [.radare2](crackmes/avatao/01-reverse4/radare2.md)
       * [.first_steps](crackmes/avatao/01-reverse4/first_steps.md)
       * [.main](crackmes/avatao/01-reverse4/main.md)
       * [.vmloop](crackmes/avatao/01-reverse4/vmloop.md)
       * [.instructionset](crackmes/avatao/01-reverse4/instructionset.md)
       * [.bytecode](crackmes/avatao/01-reverse4/bytecode.md)
       * [.outro](crackmes/avatao/01-reverse4/outro.md)
* [Reference Card](refcard/intro.md)
* [Acknowledgments](credits/credits.md)
