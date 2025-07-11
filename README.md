<div align="center">
  <a href="https://alist.nn.ci"><img width="100px" alt="logo" src="https://cdn.jsdelivr.net/gh/alist-org/logo@main/logo.svg"/></a>
  <p><em>🗂️A file list program that supports multiple storages, powered by Gin and Solidjs.</em></p>
</div>


> [!IMPORTANT]
> 
> **THIS IS A FORK VERSION !!!**
>
> We sincerely thank the original author [xhofe/alist](https://github.com/xhofe/alist) for his substantial prior contributions.
>
> This fork is not yet stable. A large number of external links point to unaudited content, posing a supply chain attack risk, including related documentation websites, etc. Do not trust!
>

---

English | [中文](./README_cn.md)

## Features

- [x] Multiple storages
  - [x] Local storage
  - [x] [Aliyundrive](https://www.alipan.com/)
  - [x] OneDrive / Sharepoint ([global](https://www.office.com/), [cn](https://portal.partner.microsoftonline.cn),de,us)
  - [x] [189cloud](https://cloud.189.cn) (Personal, Family)
  - [x] [GoogleDrive](https://drive.google.com/)
  - [x] [123pan](https://www.123pan.com/)
  - [x] FTP / SFTP
  - [x] [PikPak](https://www.mypikpak.com/)
  - [x] [S3](https://aws.amazon.com/s3/)
  - [x] [Seafile](https://seafile.com/)
  - [x] [UPYUN Storage Service](https://www.upyun.com/products/file-storage)
  - [x] WebDav(Support OneDrive/SharePoint without API)
  - [x] Teambition([China](https://www.teambition.com/ ),[International](https://us.teambition.com/ ))
  - [x] [Mediatrack](https://www.mediatrack.cn/)
  - [x] [139yun](https://yun.139.com/) (Personal, Family, Group)
  - [x] [YandexDisk](https://disk.yandex.com/)
  - [x] [BaiduNetdisk](http://pan.baidu.com/)
  - [x] [Terabox](https://www.terabox.com/main)
  - [x] [UC](https://drive.uc.cn)
  - [x] [Quark](https://pan.quark.cn)
  - [x] [Thunder](https://pan.xunlei.com)
  - [x] [Lanzou](https://www.lanzou.com/)
  - [x] [ILanzou](https://www.ilanzou.com/)
  - [x] [Aliyundrive share](https://www.alipan.com/)
  - [x] [Google photo](https://photos.google.com/)
  - [x] [Mega.nz](https://mega.nz)
  - [x] [Baidu photo](https://photo.baidu.com/)
  - [x] SMB
  - [x] [115](https://115.com/)
  - [x] Cloudreve
  - [x] [Dropbox](https://www.dropbox.com/)
  - [x] [FeijiPan](https://www.feijipan.com/)
  - [x] [dogecloud](https://www.dogecloud.com/product/oss)
  - [x] [Azure Blob Storage](https://azure.microsoft.com/products/storage/blobs)
- [x] Easy to deploy and out-of-the-box
- [x] File preview (PDF, markdown, code, plain text, ...)
- [x] Image preview in gallery mode
- [x] Video and audio preview, support lyrics and subtitles
- [x] Office documents preview (docx, pptx, xlsx, ...)
- [x] `README.md` preview rendering
- [x] File permalink copy and direct file download
- [x] Dark mode
- [x] I18n
- [x] Protected routes (password protection and authentication)
- [x] WebDav (see https://alist.nn.ci/guide/webdav.html for details)
- [x] [Docker Deploy](https://hub.docker.com/r/xhofe/alist)
- [x] Cloudflare Workers proxy
- [x] File/Folder package download
- [x] Web upload(Can allow visitors to upload), delete, mkdir, rename, move and copy
- [x] Offline download
- [x] Copy files between two storage
- [x] Multi-thread downloading acceleration for single-thread download/stream

## Discussion

Please go to our [discussion forum](https://github.com/alist-org/alist/discussions) for general questions, **issues are for bug reports and feature requests only.**

## Sponsor

AList is an open-source software, if you happen to like this project and want me to keep going, please consider sponsoring me or providing a single donation! Thanks for all the love and support:
https://alist.nn.ci/guide/sponsor.html

## Contributors

Thanks goes to these wonderful people:

[![Contributors](http://contrib.nn.ci/api?repo=alist-org/alist&repo=alist-org/alist-web&repo=alist-org/docs)](https://github.com/alist-org/alist/graphs/contributors)

## License

The `AList` is open-source software licensed under the AGPL-3.0 license.

## Disclaimer

- This program is a free and open source project. It is designed to share files on the network disk, which is convenient for downloading and learning Golang. Please abide by relevant laws and regulations when using it, and do not abuse it;
- This program is implemented by calling the official sdk/interface, without destroying the official interface behavior;
- This program only does 302 redirect/traffic forwarding, and does not intercept, store, or tamper with any user data;
- Before using this program, you should understand and bear the corresponding risks, including but not limited to account ban, download speed limit, etc., which is none of this program's business;
