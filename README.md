# Python爬虫：爬取网页视频并合成MP4文件

## 简介

本项目提供了一个Python爬虫脚本，用于爬取网页上的视频资源。由于许多网站上的视频仅支持在线观看，而没有提供下载选项，因此通过网络爬虫技术来获取这些视频资源变得尤为重要。本脚本利用`requests`库获取网页源代码中的`m3u8`链接，并对该链接进行逐步解析，获取`ts`文件列表，下载所有`ts`文件，并最终将它们合并生成一个`mp4`文件。

## 功能描述

1. **获取网页源代码**：使用`requests`库获取目标网页的源代码。
2. **解析m3u8链接**：从网页源代码中提取`m3u8`链接。
3. **下载ts文件**：解析`m3u8`文件，获取所有`ts`文件的链接，并下载这些文件。
4. **合并ts文件**：将下载的`ts`文件合并成一个`mp4`文件。

## 使用方法

1. **克隆仓库**：
    ```bash
    git clone https://github.com/your-repo-url.git
    ```

2. **安装依赖**：
    ```bash
    pip install -r requirements.txt
    ```

3. **运行脚本**：
    ```bash
    python main.py
    ```

4. **输入目标网页URL**：
    按照提示输入你想要爬取视频的网页URL。

5. **等待完成**：
    脚本将自动完成视频的爬取和合并过程，最终生成一个`mp4`文件。

## 注意事项

- 请确保你有权爬取目标网站的视频资源。
- 本脚本仅供学习和研究使用，请勿用于非法用途。

## 相关博文

本项目的详细实现过程和代码解析可以在同名博文中找到，欢迎阅读和交流。

## 许可证

本项目采用[MIT许可证](LICENSE)。

---

如果你有任何问题或建议，欢迎提交Issue或Pull Request。感谢你的使用和支持！

## 下载链接

[Python爬虫爬取网页视频并合成MP4文件](https://pan.quark.cn/s/acc1eb968afc)