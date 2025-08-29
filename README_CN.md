<h4 align="right"><a href="README.md">English</a> | <strong>简体中文</strong> | <a href="README_JP.md">日本語</a></h4>
<p align="center">
    <img src=https://gw.alipayobjects.com/zos/k/fa/logo-modified.png width=138/>
</p>
<h1 align="center">Pake</h1>
<p align="center"><strong>利用 Rust 轻松构建轻量级多端桌面应用</strong></p>
<div align="center">
    <a href="https://twitter.com/HiTw93" target="_blank">
    <img alt="twitter" src="https://img.shields.io/badge/follow-Tw93-red?style=flat-square&logo=Twitter"></a>
    <a href="https://t.me/+GclQS9ZnxyI2ODQ1" target="_blank">
    <img alt="telegram" src="https://img.shields.io/badge/chat-telegram-blueviolet?style=flat-square&logo=Telegram"></a>
    <a href="https://github.com/tw93/Pake/releases" target="_blank">
    <img alt="GitHub downloads" src="https://img.shields.io/github/downloads/tw93/Pake/total.svg?style=flat-square"></a>
    <a href="https://github.com/tw93/Pake/commits" target="_blank">
    <img alt="GitHub commit" src="https://img.shields.io/github/commit-activity/m/tw93/Pake?style=flat-square"></a>
    <a href="https://github.com/tw93/Pake/issues?q=is%3Aissue+is%3Aclosed" target="_blank">
    <img alt="GitHub closed issues" src="https://img.shields.io/github/issues-closed/tw93/Pake.svg?style=flat-square"></a>
    <a href="https://colab.research.google.com/drive/1bX345znvDZ30848xjRtpgtU8eypWwXrp?usp=sharing" target="_blank">
    <img alt="在 Colab 中打开" src="https://colab.research.google.com/assets/colab-badge.svg"></a>
</div>
<div align="left">支持 Mac / Windows / Linux，关于 <a href="#常用包下载">常用包下载</a>、<a href="#命令行一键打包">命令行一键打包</a>、<a href="#定制开发">定制开发</a> 可见下面文档，也欢迎去 <a href=https://github.com/tw93/Pake/discussions>讨论区</a> 交流。</div>

## 特征

- 🎐 相比传统的 Electron 套壳打包，要小将近 20 倍，5M 上下。
- 🚀 Pake 的底层使用的 Rust Tauri 框架，性能体验较 JS 框架要轻快不少，内存小很多。
- 📦 不是单纯打包，实现了快捷键透传、沉浸式窗口、拖动、样式改写、去广告、产品极简风格定制。
- 🖱️ 智能右键菜单，支持图片、视频、文件的下载和操作功能。
- 👻 只是一个很简单的小玩具，用 Tauri 替代之前套壳网页打包的老思路，其实 PWA 也很好。

## 常用包下载

<table>
    <tr>
        <td>WeRead
            <a href="https://github.com/tw93/Pake/releases/latest/download/WeRead.dmg">Mac</a>
            <a href="https://github.com/tw93/Pake/releases/latest/download/WeRead_x64.msi">Windows</a>
            <a href="https://github.com/tw93/Pake/releases/latest/download/WeRead_x86_64.deb">Linux</a>
        </td>
        <td>Twitter
            <a href="https://github.com/tw93/Pake/releases/latest/download/Twitter.dmg">Mac</a>
            <a href="https://github.com/tw93/Pake/releases/latest/download/Twitter_x64.msi">Windows</a>
            <a href="https://github.com/tw93/Pake/releases/latest/download/Twitter_x86_64.deb">Linux</a>
        </td>
    </tr>
    <tr>
        <td><img src=https://raw.githubusercontent.com/tw93/static/main/pake/WeRead.jpg width=600/></td>
        <td><img src=https://raw.githubusercontent.com/tw93/static/main/pake/Twitter.jpg width=600/></td>
    </tr>
    <tr>
        <td>Grok
            <a href="https://github.com/tw93/Pake/releases/latest/download/Grok.dmg">Mac</a>
            <a href="https://github.com/tw93/Pake/releases/latest/download/Grok_x64.msi">Windows</a>
            <a href="https://github.com/tw93/Pake/releases/latest/download/Grok_x86_64.deb">Linux</a>
        </td>
        <td>DeepSeek
            <a href="https://github.com/tw93/Pake/releases/latest/download/DeepSeek.dmg">Mac</a>
            <a href="https://github.com/tw93/Pake/releases/latest/download/DeepSeek_x64.msi">Windows</a>
            <a href="https://github.com/tw93/Pake/releases/latest/download/DeepSeek_x86_64.deb">Linux</a>
        </td>
    </tr>
    <tr>
        <td><img src=https://raw.githubusercontent.com/tw93/static/main/pake/Grok.png width=600/></td>
        <td><img src=https://raw.githubusercontent.com/tw93/static/main/pake/DeepSeek.png width=600/></td>
    </tr>
    <tr>
        <td>ChatGPT
            <a href="https://github.com/tw93/Pake/releases/latest/download/ChatGPT.dmg">Mac</a>
            <a href="https://github.com/tw93/Pake/releases/latest/download/ChatGPT_x64.msi">Windows</a>
            <a href="https://github.com/tw93/Pake/releases/latest/download/ChatGPT_x86_64.deb">Linux</a>
        </td>
        <td>Gemini
            <a href="https://github.com/tw93/Pake/releases/latest/download/Gemini.dmg">Mac</a>
            <a href="https://github.com/tw93/Pake/releases/latest/download/Gemini_x64.msi">Windows</a>
            <a href="https://github.com/tw93/Pake/releases/latest/download/Gemini_x86_64.deb">Linux</a>
        </td>
    </tr>
    <tr>
        <td><img src=https://raw.githubusercontent.com/tw93/static/main/pake/ChatGPT.png width=600/></td>
        <td><img src=https://raw.githubusercontent.com/tw93/static/main/pake/Gemini.png width=600/></td>
    </tr>
    <tr>
      <td>YouTube Music
            <a href="https://github.com/tw93/Pake/releases/latest/download/YouTubeMusic.dmg">Mac</a>
            <a href="https://github.com/tw93/Pake/releases/latest/download/YouTubeMusic_x64.msi">Windows</a>
            <a href="https://github.com/tw93/Pake/releases/latest/download/YouTubeMusic_x86_64.deb">Linux</a>
      </td>
      <td>YouTube
            <a href="https://github.com/tw93/Pake/releases/latest/download/YouTube.dmg">Mac</a>
            <a href="https://github.com/tw93/Pake/releases/latest/download/YouTube_x64.msi">Windows</a>
            <a href="https://github.com/tw93/Pake/releases/latest/download/YouTube_x86_64.deb">Linux</a>
      </td>
    </tr>
    <tr>
        <td><img src=https://raw.githubusercontent.com/tw93/static/main/pake/YouTubeMusic.png width=600 /></td>
        <td><img src=https://raw.githubusercontent.com/tw93/static/main/pake/YouTube.jpg width=600 /></td>
    </tr>
    <tr>
        <td>LiZhi
            <a href="https://github.com/tw93/Pake/releases/latest/download/LiZhi.dmg">Mac</a>
            <a href="https://github.com/tw93/Pake/releases/latest/download/LiZhi_x64.msi">Windows</a>
            <a href="https://github.com/tw93/Pake/releases/latest/download/LiZhi_x86_64.deb">Linux</a>
        </td>
        <td>ProgramMusic
            <a href="https://github.com/tw93/Pake/releases/latest/download/ProgramMusic.dmg">Mac</a>
            <a href="https://github.com/tw93/Pake/releases/latest/download/ProgramMusic_x64.msi">Windows</a>
            <a href="https://github.com/tw93/Pake/releases/latest/download/ProgramMusic_x86_64.deb">Linux</a>
        </td>
    </tr>
    <tr>
        <td><img src=https://raw.githubusercontent.com/tw93/static/main/pake/LiZhi.jpg width=600/></td>
        <td><img src=https://raw.githubusercontent.com/tw93/static/main/pake/ProgramMusic.jpg width=600/></td>
    </tr>
    <tr>
        <td>Excalidraw
            <a href="https://github.com/tw93/Pake/releases/latest/download/Excalidraw.dmg">Mac</a>
            <a href="https://github.com/tw93/Pake/releases/latest/download/Excalidraw_x64.msi">Windows</a>
            <a href="https://github.com/tw93/Pake/releases/latest/download/Excalidraw_x86_64.deb">Linux</a>
        </td>
        <td>XiaoHongShu
            <a href="https://github.com/tw93/Pake/releases/latest/download/XiaoHongShu.dmg">Mac</a>
            <a href="https://github.com/tw93/Pake/releases/latest/download/XiaoHongShu_x64.msi">Windows</a>
            <a href="https://github.com/tw93/Pake/releases/latest/download/XiaoHongShu_x86_64.deb">Linux</a>
        </td>
    </tr>
    <tr>
        <td><img src=https://raw.githubusercontent.com/tw93/static/main/pake/Excalidraw.png width=600/></td>
        <td><img src=https://raw.githubusercontent.com/tw93/static/main/pake/XiaoHongShu.png width=600/></td>
    </tr>
</table>

<details>

<summary>🏂 更多应用可去 <a href="https://github.com/tw93/Pake/releases">Release</a>下载，<b>此外点击可展开快捷键说明</b></summary>

<br/>

| Mac                         | Windows/Linux                  | 功能               |
| --------------------------- | ------------------------------ | ------------------ |
| <kbd>⌘</kbd> + <kbd>[</kbd> | <kbd>Ctrl</kbd> + <kbd>←</kbd> | 返回上一个页面     |
| <kbd>⌘</kbd> + <kbd>]</kbd> | <kbd>Ctrl</kbd> + <kbd>→</kbd> | 去下一个页面       |
| <kbd>⌘</kbd> + <kbd>↑</kbd> | <kbd>Ctrl</kbd> + <kbd>↑</kbd> | 自动滚动到页面顶部 |
| <kbd>⌘</kbd> + <kbd>↓</kbd> | <kbd>Ctrl</kbd> + <kbd>↓</kbd> | 自动滚动到页面底部 |
| <kbd>⌘</kbd> + <kbd>r</kbd> | <kbd>Ctrl</kbd> + <kbd>r</kbd> | 刷新页面           |
| <kbd>⌘</kbd> + <kbd>w</kbd> | <kbd>Ctrl</kbd> + <kbd>w</kbd> | 隐藏窗口，非退出   |
| <kbd>⌘</kbd> + <kbd>-</kbd> | <kbd>Ctrl</kbd> + <kbd>-</kbd> | 缩小页面           |
| <kbd>⌘</kbd> + <kbd>+</kbd> | <kbd>Ctrl</kbd> + <kbd>+</kbd> | 放大页面           |
| <kbd>⌘</kbd> + <kbd>=</kbd> | <kbd>Ctrl</kbd> + <kbd>=</kbd> | 放大页面           |
| <kbd>⌘</kbd> + <kbd>0</kbd> | <kbd>Ctrl</kbd> + <kbd>0</kbd> | 重置页面缩放       |

此外还支持双击头部进行全屏切换，拖拽头部进行移动窗口，Mac 用户支持手势方式返回和去下一页，还有其他需求，欢迎提过来。

</details>

## 开始之前

1. **小白用户**：使用 「常用包下载」 方式来把玩 Pake 的能力，可去 [讨论群](https://github.com/tw93/Pake/discussions) 寻求帮助，也可试试 [Action](https://github.com/tw93/Pake/wiki/%E5%9C%A8%E7%BA%BF%E7%BC%96%E8%AF%91%EF%BC%88%E6%99%AE%E9%80%9A%E7%94%A8%E6%88%B7%E4%BD%BF%E7%94%A8%EF%BC%89) 方式。
2. **开发用户**：使用 「命令行一键打包」，对 Mac 比较友好，Windows / Linux 需折腾下 [环境配置](https://tauri.app/start/prerequisites/)。
3. **折腾用户**：假如你前端和 Rust 都会，那可试试下面的 「[定制开发](#定制开发)」，可深度二次开发定制你的功能。

## 命令行一键打包

![Pake](https://raw.githubusercontent.com/tw93/static/main/pake/pake.gif)

**Pake 提供了命令行工具，可以更快捷方便地一键自定义打包你需要的应用，详细可见 [CLI 使用指南](docs/cli-usage_CN.md)。**

```bash
# 推荐方式 (pnpm)
pnpm install -g pake-cli

# 备选方式 (npm)
npm install -g pake-cli

# 命令使用
pake url [OPTIONS]...

# 试试看！首次打包可能较慢（需要安装环境），后续会很快
pake https://weekly.tw93.fun --name Weekly --hide-title-bar
```

如果你不太会使用命令行，可以使用 **GitHub Actions 在线编译**，详细步骤请参考[文档](#文档)。

## 定制开发

开始前请确保电脑已经安装了 Rust `>=1.89` 和 Node `>=18`（如 22.11.0）的环境。_注意：推荐使用最新稳定版本。_ 详细安装指南请参考 [Tauri 文档](https://tauri.app/start/prerequisites/)。

如果您对这些不熟悉，建议使用上面的命令行工具进行一键打包。

```sh
# 安装依赖
pnpm i

# 本地开发[右键可打开调试模式]
pnpm run dev

# 打包应用
pnpm run build

```

## 文档

- **[CLI 使用指南](docs/cli-usage_CN.md)** - 命令行接口参考
- **[高级用法指南](docs/advanced-usage_CN.md)** - 自定义和高级功能
- **[GitHub Actions 指南](docs/github-actions-usage_CN.md)** - 在线构建应用
- **[Pake Action](docs/pake-action.md)** - 在你的项目中使用 Pake Action
- **[贡献指南](CONTRIBUTING.md)** - 如何参与开发

## 开发者

Pake 的发展离不开这些 Hacker 们，一起贡献了大量能力，也欢迎关注他们 ❤️

<!-- readme: contributors -start -->
<table>
	<tbody>
		<tr>
            <td align="center">
                <a href="https://github.com/tw93">
                    <img src="https://avatars.githubusercontent.com/u/8736212?v=4" width="90;" alt="tw93"/>
                    <br />
                    <sub><b>Tw93</b></sub>
                </a>
            </td>
            <td align="center">
                <a href="https://github.com/Tlntin">
                    <img src="https://avatars.githubusercontent.com/u/28218658?v=4" width="90;" alt="Tlntin"/>
                    <br />
                    <sub><b>Tlntin</b></sub>
                </a>
            </td>
            <td align="center">
                <a href="https://github.com/jeasonnow">
                    <img src="https://avatars.githubusercontent.com/u/16950207?v=4" width="90;" alt="jeasonnow"/>
                    <br />
                    <sub><b>Santree</b></sub>
                </a>
            </td>
            <td align="center">
                <a href="https://github.com/pan93412">
                    <img src="https://avatars.githubusercontent.com/u/28441561?v=4" width="90;" alt="pan93412"/>
                    <br />
                    <sub><b>Pan93412</b></sub>
                </a>
            </td>
            <td align="center">
                <a href="https://github.com/stone-w4tch3r">
                    <img src="https://avatars.githubusercontent.com/u/100294019?v=4" width="90;" alt="stone-w4tch3r"/>
                    <br />
                    <sub><b>Данил Бизимов</b></sub>
                </a>
            </td>
            <td align="center">
                <a href="https://github.com/wanghanzhen">
                    <img src="https://avatars.githubusercontent.com/u/25301012?v=4" width="90;" alt="wanghanzhen"/>
                    <br />
                    <sub><b>Volare</b></sub>
                </a>
            </td>
            <td align="center">
                <a href="https://github.com/liby">
                    <img src="https://avatars.githubusercontent.com/u/38807139?v=4" width="90;" alt="liby"/>
                    <br />
                    <sub><b>Bryan Lee</b></sub>
                </a>
            </td>
		</tr>
		<tr>
            <td align="center">
                <a href="https://github.com/essesoul">
                    <img src="https://avatars.githubusercontent.com/u/58624474?v=4" width="90;" alt="essesoul"/>
                    <br />
                    <sub><b>Essesoul</b></sub>
                </a>
            </td>
            <td align="center">
                <a href="https://github.com/YangguangZhou">
                    <img src="https://avatars.githubusercontent.com/u/61733195?v=4" width="90;" alt="YangguangZhou"/>
                    <br />
                    <sub><b>Jerry Zhou</b></sub>
                </a>
            </td>
            <td align="center">
                <a href="https://github.com/AielloChan">
                    <img src="https://avatars.githubusercontent.com/u/7900765?v=4" width="90;" alt="AielloChan"/>
                    <br />
                    <sub><b>Aiello</b></sub>
                </a>
            </td>
            <td align="center">
                <a href="https://github.com/m1911star">
                    <img src="https://avatars.githubusercontent.com/u/4948120?v=4" width="90;" alt="m1911star"/>
                    <br />
                    <sub><b>Horus</b></sub>
                </a>
            </td>
            <td align="center">
                <a href="https://github.com/Pake-Actions">
                    <img src="https://avatars.githubusercontent.com/u/126550811?v=4" width="90;" alt="Pake-Actions"/>
                    <br />
                    <sub><b>Pake Actions</b></sub>
                </a>
            </td>
            <td align="center">
                <a href="https://github.com/GoodbyeNJN">
                    <img src="https://avatars.githubusercontent.com/u/6856639?v=4" width="90;" alt="GoodbyeNJN"/>
                    <br />
                    <sub><b>GoodbyeNJN</b></sub>
                </a>
            </td>
            <td align="center">
                <a href="https://github.com/kittizz">
                    <img src="https://avatars.githubusercontent.com/u/62899732?v=4" width="90;" alt="kittizz"/>
                    <br />
                    <sub><b>Kittizz</b></sub>
                </a>
            </td>
		</tr>
		<tr>
            <td align="center">
                <a href="https://github.com/mattbajorek">
                    <img src="https://avatars.githubusercontent.com/u/17235301?v=4" width="90;" alt="mattbajorek"/>
                    <br />
                    <sub><b>Matt Bajorek</b></sub>
                </a>
            </td>
            <td align="center">
                <a href="https://github.com/vaddisrinivas">
                    <img src="https://avatars.githubusercontent.com/u/38348871?v=4" width="90;" alt="vaddisrinivas"/>
                    <br />
                    <sub><b>Srinivas Vaddi</b></sub>
                </a>
            </td>
            <td align="center">
                <a href="https://github.com/QingZ11">
                    <img src="https://avatars.githubusercontent.com/u/38887077?v=4" width="90;" alt="QingZ11"/>
                    <br />
                    <sub><b>Steam</b></sub>
                </a>
            </td>
            <td align="center">
                <a href="https://github.com/Tianj0o">
                    <img src="https://avatars.githubusercontent.com/u/68584284?v=4" width="90;" alt="Tianj0o"/>
                    <br />
                    <sub><b>Qitianjia</b></sub>
                </a>
            </td>
            <td align="center">
                <a href="https://github.com/xinyii">
                    <img src="https://avatars.githubusercontent.com/u/17895104?v=4" width="90;" alt="xinyii"/>
                    <br />
                    <sub><b>Yi Xin</b></sub>
                </a>
            </td>
            <td align="center">
                <a href="https://github.com/g1eny0ung">
                    <img src="https://avatars.githubusercontent.com/u/15034155?v=4" width="90;" alt="g1eny0ung"/>
                    <br />
                    <sub><b>Yue Yang</b></sub>
                </a>
            </td>
            <td align="center">
                <a href="https://github.com/lkieryan">
                    <img src="https://avatars.githubusercontent.com/u/187804088?v=4" width="90;" alt="lkieryan"/>
                    <br />
                    <sub><b>Kieran</b></sub>
                </a>
            </td>
		</tr>
		<tr>
            <td align="center">
                <a href="https://github.com/exposir">
                    <img src="https://avatars.githubusercontent.com/u/33340988?v=4" width="90;" alt="exposir"/>
                    <br />
                    <sub><b>孟世博</b></sub>
                </a>
            </td>
            <td align="center">
                <a href="https://github.com/2nthony">
                    <img src="https://avatars.githubusercontent.com/u/19513289?v=4" width="90;" alt="2nthony"/>
                    <br />
                    <sub><b>2nthony</b></sub>
                </a>
            </td>
            <td align="center">
                <a href="https://github.com/ACGNnsj">
                    <img src="https://avatars.githubusercontent.com/u/22112141?v=4" width="90;" alt="ACGNnsj"/>
                    <br />
                    <sub><b>Null</b></sub>
                </a>
            </td>
            <td align="center">
                <a href="https://github.com/imabutahersiddik">
                    <img src="https://avatars.githubusercontent.com/u/138387257?v=4" width="90;" alt="imabutahersiddik"/>
                    <br />
                    <sub><b>Abu Taher Siddik</b></sub>
                </a>
            </td>
            <td align="center">
                <a href="https://github.com/kidylee">
                    <img src="https://avatars.githubusercontent.com/u/841310?v=4" width="90;" alt="kidylee"/>
                    <br />
                    <sub><b>An Li</b></sub>
                </a>
            </td>
            <td align="center">
                <a href="https://github.com/nekomeowww">
                    <img src="https://avatars.githubusercontent.com/u/11081491?v=4" width="90;" alt="nekomeowww"/>
                    <br />
                    <sub><b>Ayaka Neko</b></sub>
                </a>
            </td>
            <td align="center">
                <a href="https://github.com/turkyden">
                    <img src="https://avatars.githubusercontent.com/u/24560160?v=4" width="90;" alt="turkyden"/>
                    <br />
                    <sub><b>Dengju Deng</b></sub>
                </a>
            </td>
		</tr>
		<tr>
            <td align="center">
                <a href="https://github.com/fvn-elmy">
                    <img src="https://avatars.githubusercontent.com/u/71275745?v=4" width="90;" alt="fvn-elmy"/>
                    <br />
                    <sub><b>Fabien</b></sub>
                </a>
            </td>
            <td align="center">
                <a href="https://github.com/Fechin">
                    <img src="https://avatars.githubusercontent.com/u/2541482?v=4" width="90;" alt="Fechin"/>
                    <br />
                    <sub><b>Fechin</b></sub>
                </a>
            </td>
            <td align="center">
                <a href="https://github.com/ImgBotApp">
                    <img src="https://avatars.githubusercontent.com/u/31427850?v=4" width="90;" alt="ImgBotApp"/>
                    <br />
                    <sub><b>Imgbot</b></sub>
                </a>
            </td>
            <td align="center">
                <a href="https://github.com/droid-Q">
                    <img src="https://avatars.githubusercontent.com/u/708277?v=4" width="90;" alt="droid-Q"/>
                    <br />
                    <sub><b>Jiaqi Gu</b></sub>
                </a>
            </td>
            <td align="center">
                <a href="https://github.com/Jason6987">
                    <img src="https://avatars.githubusercontent.com/u/140222795?v=4" width="90;" alt="Jason6987"/>
                    <br />
                    <sub><b>Luminall</b></sub>
                </a>
            </td>
            <td align="center">
                <a href="https://github.com/Milo123459">
                    <img src="https://avatars.githubusercontent.com/u/50248166?v=4" width="90;" alt="Milo123459"/>
                    <br />
                    <sub><b>Milo</b></sub>
                </a>
            </td>
            <td align="center">
                <a href="https://github.com/princemaple">
                    <img src="https://avatars.githubusercontent.com/u/1329716?v=4" width="90;" alt="princemaple"/>
                    <br />
                    <sub><b>Po Chen</b></sub>
                </a>
            </td>
		</tr>
		<tr>
            <td align="center">
                <a href="https://github.com/beautifulrem">
                    <img src="https://avatars.githubusercontent.com/u/98527099?v=4" width="90;" alt="beautifulrem"/>
                    <br />
                    <sub><b>Xie Ruiqi</b></sub>
                </a>
            </td>
            <td align="center">
                <a href="https://github.com/bocanhcam">
                    <img src="https://avatars.githubusercontent.com/u/35592955?v=4" width="90;" alt="bocanhcam"/>
                    <br />
                    <sub><b>bocanhcam</b></sub>
                </a>
            </td>
            <td align="center">
                <a href="https://github.com/geekvest">
                    <img src="https://avatars.githubusercontent.com/u/126322776?v=4" width="90;" alt="geekvest"/>
                    <br />
                    <sub><b>Null</b></sub>
                </a>
            </td>
            <td align="center">
                <a href="https://github.com/houhoz">
                    <img src="https://avatars.githubusercontent.com/u/19684376?v=4" width="90;" alt="houhoz"/>
                    <br />
                    <sub><b>Hyzhao</b></sub>
                </a>
            </td>
            <td align="center">
                <a href="https://github.com/lakca">
                    <img src="https://avatars.githubusercontent.com/u/16255922?v=4" width="90;" alt="lakca"/>
                    <br />
                    <sub><b>Null</b></sub>
                </a>
            </td>
            <td align="center">
                <a href="https://github.com/liudonghua123">
                    <img src="https://avatars.githubusercontent.com/u/2276718?v=4" width="90;" alt="liudonghua123"/>
                    <br />
                    <sub><b>Liudonghua</b></sub>
                </a>
            </td>
            <td align="center">
                <a href="https://github.com/liusishan">
                    <img src="https://avatars.githubusercontent.com/u/33129823?v=4" width="90;" alt="liusishan"/>
                    <br />
                    <sub><b>Liusishan</b></sub>
                </a>
            </td>
		</tr>
		<tr>
            <td align="center">
                <a href="https://github.com/piaoyidage">
                    <img src="https://avatars.githubusercontent.com/u/5135405?v=4" width="90;" alt="piaoyidage"/>
                    <br />
                    <sub><b>Ranger</b></sub>
                </a>
            </td>
            <td align="center">
                <a href="https://github.com/oulp">
                    <img src="https://avatars.githubusercontent.com/u/8519009?v=4" width="90;" alt="oulp"/>
                    <br />
                    <sub><b>欧雷</b></sub>
                </a>
            </td>
            <td align="center">
                <a href="https://github.com/hetz">
                    <img src="https://avatars.githubusercontent.com/u/820141?v=4" width="90;" alt="hetz"/>
                    <br />
                    <sub><b>贺天卓</b></sub>
                </a>
            </td>
		</tr>
	<tbody>
</table>
<!-- readme: contributors -end -->

## 支持

1. 我有两只猫，一只叫汤圆，一只可乐，假如 Pake 让你生活更美好，可以给她们 <a href="https://miaoyan.app/cats.html?name=Pake" target="_blank">喂罐头 🥩</a>。
2. 如果你喜欢 Pake，可以在 Github Star，更欢迎 [推荐](https://twitter.com/intent/tweet?url=https://github.com/tw93/Pake&text=%23Pake%20%E4%B8%80%E4%B8%AA%E5%BE%88%E7%AE%80%E5%8D%95%E7%9A%84%E7%94%A8%20Rust%20%E6%89%93%E5%8C%85%E7%BD%91%E9%A1%B5%E7%94%9F%E6%88%90%20Mac%20App%20%E7%9A%84%E5%B7%A5%E5%85%B7%EF%BC%8C%E7%9B%B8%E6%AF%94%E4%BC%A0%E7%BB%9F%E7%9A%84%20Electron%20%E5%A5%97%E5%A3%B3%E6%89%93%E5%8C%85%EF%BC%8C%E5%A4%A7%E5%B0%8F%E8%A6%81%E5%B0%8F%E5%B0%86%E8%BF%91%2040%20%E5%80%8D%EF%BC%8C%E4%B8%80%E8%88%AC%202M%20%E5%B7%A6%E5%8F%B3%EF%BC%8C%E5%BA%95%E5%B1%82%E4%BD%BF%E7%94%A8Tauri%20%EF%BC%8C%E6%80%A7%E8%83%BD%E4%BD%93%E9%AA%8C%E8%BE%83%20JS%20%E6%A1%86%E6%9E%B6%E8%A6%81%E8%BD%BB%E5%BF%AB%E4%B8%8D%E5%B0%91%EF%BC%8C%E5%86%85%E5%AD%98%E5%B0%8F%E5%BE%88%E5%A4%9A%EF%BC%8C%E6%94%AF%E6%8C%81%E5%BE%AE%E4%BF%A1%E8%AF%BB%E4%B9%A6%E3%80%81Twitter%E3%80%81Youtube%E3%80%81RunCode%E3%80%81Flomo%E3%80%81%E8%AF%AD%E9%9B%80%E7%AD%89%EF%BC%8C%E5%8F%AF%E4%BB%A5%E5%BE%88%E6%96%B9%E4%BE%BF%E4%BA%8C%E6%AC%A1%E5%BC%80%E5%8F%91~) 给你志同道合的朋友使用。
3. 可以关注我的 [Twitter](https://twitter.com/HiTw93) 获取到最新的 Pake 更新消息，也欢迎加入 [Telegram](https://t.me/+GclQS9ZnxyI2ODQ1) 聊天群。
4. 希望大伙玩的过程中有一种学习新技术的喜悦感，假如你发现有很适合做成桌面 App 的网页也很欢迎告诉我。
