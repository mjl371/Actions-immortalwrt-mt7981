# Actions-OpenWrt

## Usage

- Generate `.config` files using [immortalwrt-mt798x](https://github.com/hanwckf/immortalwrt-mt798x) source code. ( You can change it through environment variables in the workflow file. )
- Push `.config` file to the GitHub repository.
- Select `Build OpenWrt` on the Actions page.
- Click the `Run workflow` button.
- When the build is complete, click the `Artifacts` button in the upper right corner of the Actions page to download the binaries.

## Tips

- It may take a long time to create a `.config` file and build the OpenWrt firmware. Thus, before create repository to build your own firmware, you may check out if others have already built it which meet your needs by simply [search `Actions-Openwrt` in GitHub](https://github.com/search?q=Actions-openwrt).
- Add some meta info of your built firmware (such as firmware architecture and installed packages) to your repository introduction, this will save others' time.

## Credits
- [Actions-OpenWrt](https://github.com/P3TERX/Actions-OpenWrt)
- [GitHub Actions](https://github.com/features/actions)
- [OpenWrt](https://github.com/openwrt/openwrt)
- [immortalwrt](https://github.com/immortalwrt/immortalwrt)
- [immortalwrt-mt798x](https://github.com/hanwckf/immortalwrt-mt798x)
- [Mikubill/transfer](https://github.com/Mikubill/transfer)

