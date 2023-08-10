# NVIDIA_ARSDK_iFacialMocap

NVIDIA社が提供しているAR SDKを、iFacialMocapのiOSアプリと通信互換性を持たせるために変更を加えたリポジトリです。 iFacialMocapのiOSアプリは、多くの開発者のお世話になっているため、このコードを公開することにしました。 ライセンスは、もとのコードのライセンスを引き継いでMITライセンスです。私がGitHubの使い方に慣れていないため、あまり頻繁に更新はしないと思われます。

<B>/OSS/samples/ExpressionApp内にある、run.batまたは、noConsoleRun.vbsをダブルクリックすることで起動します。</B> VMagicMirrorやLuppetなどiFacialMocapのiOSアプリと通信できるすべてのソフトウェアと通信できると思われます。

このコード、またはファイルを自作アプリ等に組み込んで使用して頂いて構いません。 ただし、アプリ内に組み込む場合、NVIDIA社が求めるブランディングガイドラインに沿う必要があります。以下のURLを参照してください。 https://nvidia.frontify.com/d/uAobRitG8H8B/with-nvidia

現状、解決策がよくわからない点は、アプリを最小化したときにFPSが大きく低下する点や、アプリのアイコンがタスクバーに現れないことなどがあります。


This is a repository of the AR SDK provided by NVIDIA, modified to have communication compatibility with the iFacialMocap iOS app. iFacialMocap's iOS app has been indebted to many developers, so I decided to make this code public. The license is the MIT license, inheriting the license of the original code. I'm not used to using GitHub, so I don't expect to update it very often.

Start by double-clicking run.bat or noConsoleRun.vbs in <B>/OSS/samples/ExpressionApp. </B> It should be able to communicate with any software that can communicate with the iFacialMocap iOS app, such as VMagicMirror and Luppet.

You can use this code or file by embedding it in your own application. However, when embedding in an app, it is necessary to follow the branding guidelines required by NVIDIA. See the URL below. https://nvidia.frontify.com/d/uAobRitG8H8B/with-nvidia

At the moment, I don't really know the solution is that the FPS drops significantly when the app is minimized, and the app icon does not appear on the taskbar.
