![Logo](logonew.webp)


# MoiSposed Framework

[![Build](https://img.shields.io/github/actions/workflow/status/LSPosed/LSPosed/core.yml?branch=master&event=push&logo=github&label=Build)](https://github.com/LSPosed/LSPosed/actions/workflows/core.yml?query=event%3Apush+branch%3Amaster+is%3Acompleted) [![Crowdin](https://img.shields.io/badge/Localization-Crowdin-blueviolet?logo=Crowdin)](https://lsposed.crowdin.com/lsposed) [![Channel](https://img.shields.io/badge/Follow-Telegram-blue.svg?logo=telegram)](https://t.me/LSPosed) [![Chat](https://img.shields.io/badge/Join-QQ%E9%A2%91%E9%81%93-red?logo=tencent-qq&logoColor=red)](https://qun.qq.com/qqweb/qunpro/share?_wv=3&_wwv=128&inviteCode=Xz9dJ&from=246610&biz=ka) [![Download](https://img.shields.io/github/v/release/LSPosed/LSPosed?color=orange&logoColor=orange&label=Download&logo=DocuSign)](https://github.com/LSPosed/LSPosed/releases/latest) [![Total](https://shields.io/github/downloads/LSPosed/LSPosed/total?logo=Bookmeter&label=Counts&logoColor=yellow&color=yellow)](https://github.com/LSPosed/LSPosed/releases)

### Introduction

MoiSposed Framework is a continuation of the LSPosed project, aiming to provide an ART hooking framework that delivers consistent APIs with the original Xposed, leveraging the LSPlant hooking framework. By building upon the strong foundation laid by LSPosed, MoiSposed seeks to further enhance and expand the capabilities for ART hooking within the Android ecosystem.

Xposed is a framework for modules that can change the behavior of the system and apps without touching any APKs. This approach is advantageous because it ensures that modules can work across different versions and even ROMs without any changes, provided the original code remains largely unchanged. Moreover, the process is easily reversible since all modifications are performed in memory; deactivating the module and rebooting restores the original system state. MoiSposed Framework inherits these benefits, allowing for simultaneous modifications by multiple modules to the same system or app parts, something not feasible with modified APKs.

### Supported Versions

- Android 8.1 to 14

### Install

1. Install Magisk v24+
2. (For Riru flavor) Install Riru v26.1.7+
3. Download and install MoiSposed in the Magisk app
4. Reboot
5. Open MoiSposed manager from the notification
6. Have fun :)

### Download

- For stable releases, please go to [Github Releases](#) page. <!-- Update the link with the actual URL -->
- For canary builds, please check [Github Actions](#). <!-- Update the link with the actual URL -->

> Note: Debug builds are only available in Github Actions.

### Get Help

Only bug reports from THE LATEST DEBUG BUILD will be accepted.
- GitHub issues: [Issues](#) <!-- Update the link with the actual URL -->
- (For Chinese speakers) 本项目只接受英语标题的issue。如果您不懂英语，请使用翻译工具

### For Developers

Developers are encouraged to write Xposed modules with hooks based on the MoiSposed Framework. Modules based on the MoiSposed framework are fully compatible with the original Xposed Framework, and vice versa.

- [Xposed Framework API](#) <!-- Update the link with the actual API documentation URL -->

We use our own module repository and welcome developers to submit modules for inclusion. These can then be downloaded directly within MoiSposed.

- [MoiSposed Module Repository](#) <!-- Update the link with the actual repository URL -->

### Community Discussion

- Telegram: [@LSPosed](#) <!-- Update if there's a new community channel -->

> Notice: These community groups don't accept any bug reports. Please use the "Get help" section to report issues.

### Translation Contributing

You can contribute to translation [here](#). <!-- Update the link with the actual translation project URL -->

### Credits

Acknowledgments to the following projects and contributors:
- Magisk: For making all these possible.
- Riru: For providing a way to inject code into the zygote process.
- XposedBridge: The original Xposed framework APIs.
- Dobby: Used for inline hooking.
- LSPlant: The core ART hooking framework.
- EdXposed: Fork source.
- And others listed in the original LSPosed credits.

### License

MoiSposed is licensed under the GNU General Public License v3 (GPL-3) (http://www.gnu.org/copyleft/gpl.html).
