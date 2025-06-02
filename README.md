# LolbinMMCDownload
Download files with MMC

Step by step guide:
1. Open mmc.exe
2. File - Add/Remove Snap-in
3. Choose: Link To Web Address and press Add....
4. Paste in link to file you want to download, click Next and name it. Click Finish.
5. Make sure to highlight your newly created link and save your console file. File - Save As
6. Open CMD and type: mmc.exe -Embedding path/to/file

PoC Video: https://www.youtube.com/watch?v=LFgZOTmhzeA

(The downloader is run under the MMC process as shown in the video.)

Example MSC file(Downloads ProcExp.zip): https://github.com/FredCyberSecurity/LolbinMMCDownload/blob/main/download.msc

Lolbas Project: https://lolbas-project.github.io/lolbas/Binaries/Mmc/#download

