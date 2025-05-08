# 代理设置

代理IP如何配置

{% hint style="success" %}
会话代理支持离线与在线设置，设置后再打开会话即可生效
{% endhint %}

{% stepper %}
{% step %}
### 第一步：点击打开代理配置

![](<../../.gitbook/assets/image (12).png>)点击打开代理配置
{% endstep %}

{% step %}
### 第二步：智能填写处、粘贴复制过来的IP，自动识别

<figure><img src="../../.gitbook/assets/image (13).png" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
### 第三步：点击保存/保存并打开会话，即可成保存

<figure><img src="../../.gitbook/assets/image (14).png" alt=""><figcaption></figcaption></figure>
{% endstep %}
{% endstepper %}

<details>

<summary>2 为什么保存代理后，登录账号，代理就不能修改了？</summary>

<mark style="color:green;">问题回复</mark>：代理服务器启动后就需要按照预设的配置信息进行运行，此时如果修改代理配置可能会影响代理服务器的的性能和稳定性。如果代理服务器正在处理大量的网络流量，而此时又进行了实时修改配置信息，可能会导致代理服务器的性能下降或者崩溃。所以为了确保代理服务器的正常运行，我们建议您在代理服务器运行前预先设置好所需的配置信息，如果需要修改请关闭会话后重新设置。

</details>

<details>

<summary>3 一般什么情况下需要用到会话代理？</summary>

<mark style="color:green;">问题回复：</mark>

1）隐藏真实IP地址。可以使用代理协议去实现；

2）提高网络速度。遇到网络延迟或带宽限制的问题时，可以使用代理协议来加速网络连接，特别是在访问跨国网站时，使用代理可以减少跨国网络传输的时延和波动；

3）提高安全性。使用代理协议来保护自己的网络安全，可以减少在公共网络中被黑客攻击的风险。

4）减少封号。代理IP可以使用真实住宅IP，更不容易触发封号；当封号时，因使用不同IP，也不会影响到其他账号。当您有大量的账号需要接粉时，为了减少风控，建议您给账号配置不同的IP，每条IP建议不要登录过多的账号

</details>

<details>

<summary>4 代理服务器验证是干什么用的？</summary>

<mark style="color:green;">问题回复</mark>：代理服务器验证是指对代理服务器进行身份验证的过程。身份验证是一种安全机制，用于确保只有授权的用户才能使用代理服务器，可以帮助保护代理服务器免受未经授权的访问和滥用。

</details>

<details>

<summary>5 我不进行代理服务器验证会有什么影响吗？</summary>

<mark style="color:green;">问题回复</mark>：如果代理服务器不进行身份验证，任何人都可以通过代理服务器访问互联网，无需提供身份凭证。这种情况下，代理服务器可以被广泛使用，但相应地，也容易受到滥用和攻击。

</details>

<details>

<summary>6 我该如何选择是否进行代理服务器验证?</summary>

<mark style="color:green;">问题回复</mark>：如果代理服务器不进行身份验证，可能会受到滥用和攻击，而且可能会影响代理服务器的性能和可靠性。如果代理服务器进行身份验证，可以提高代理服务器的安全性和稳定性，但同时也会限制代理服务器的使用范围。因此，在选择是否进行身份验证时，需要根据实际需求和安全要求进行权衡。

</details>

<details>

<summary>7 HTTP、HTTPS、SOCKS4、SOCKS5这些协议是什么意思？有什么区别？</summary>

<mark style="color:green;">问题回复</mark>：

<mark style="color:yellow;">**HTTP协议**</mark>：HTTP是超文本传输协议的缩写，是应用层协议，主要用于Web浏览器和Web服务器之间的通信。HTTP协议可以被应用于代理服务器，用于代理HTTP和HTTPS流量。HTTP代理服务器可以缓存Web页面，以提高访问速度，并且可以对流量进行过滤和记录。

<mark style="color:yellow;">**HTTPS协议**</mark>：HTTPS是在HTTP协议基础上增加了SSL/TLS协议支持的协议，用于加密Web通信。HTTPS代理服务器可以代理HTTPS流量，并且可以提供更高的安全性。

<mark style="color:yellow;">**SOCKS4协议**</mark>：SOCKS协议是一种网络传输协议，可以代理TCP流量和UDP流量。SOCKS4协议是它的第四个版本，但它不支持身份验证和DNS解析，只支持TCP流量代理。SOCKS4协议的优点是简单、快速，并且可以代理大多数TCP流量，适用于一些简单的代理场景。

<mark style="color:yellow;">**SOCKS5协议**</mark>：是SOCKS协议的第五个版本，支持身份验证和DNS解析，并且可以代理TCP流量和UDP流量。SOCKS5协议的优点是更加灵活、安全，可以适应更多的代理场景。相比于SOCKS4协议，SOCKS5协议可以更好地支持网络环境中的复杂网络拓扑和安全需求。

</details>

<details>

<summary>8 推荐使用哪种协议进行代理？</summary>

<mark style="color:green;">问题回复</mark>：SOCKS5协议。相比SOCK4代理只支持[TCP协议](https://www.baidu.com/s?wd=TCP%E5%8D%8F%E8%AE%AE\&tn=SE_PcZhidaonwhc_ngpagmjz\&rsv_dl=gh_pc_zhidao)，[SOCKS5代理](https://www.baidu.com/s?wd=SOCKS5%E4%BB%A3%E7%90%86\&tn=SE_PcZhidaonwhc_ngpagmjz\&rsv_dl=gh_pc_zhidao)则既支持[TCP协议](https://www.baidu.com/s?wd=TCP%E5%8D%8F%E8%AE%AE\&tn=SE_PcZhidaonwhc_ngpagmjz\&rsv_dl=gh_pc_zhidao)又支持[UDP协议](https://www.baidu.com/s?wd=UDP%E5%8D%8F%E8%AE%AE\&tn=SE_PcZhidaonwhc_ngpagmjz\&rsv_dl=gh_pc_zhidao)，还支持各种身份验证机制、[服务器端](https://www.baidu.com/s?wd=%E6%9C%8D%E5%8A%A1%E5%99%A8%E7%AB%AF\&tn=SE_PcZhidaonwhc_ngpagmjz\&rsv_dl=gh_pc_zhidao)域名解析等。又因为SOCKS5代理工作在会话层，不要求应用程序遵循特定的操作系统平台，SOCKS5 代理只是简单地传递数据包，而不必关心是何种应用协议。 由上可知，SOCKS5 代理比HTTP 代理速度要快得多。

</details>

<details>

<summary>9 如果我不想别人查到我的真实IP，用哪种代理好？</summary>

<mark style="color:green;">问题回复</mark>：如果是不想让人看到真实IP，用高匿的[SOCKS5代理](https://www.baidu.com/s?wd=SOCKS5%E4%BB%A3%E7%90%86\&tn=SE_PcZhidaonwhc_ngpagmjz\&rsv_dl=gh_pc_zhidao)IP就可以的。当你使用SOCKS协议时，你的计算机会将数据包发送到代理服务器，代理服务器再将数据包转发到目标服务器。因此SOCKS协议可以帮助你隐藏你的真实IP地址，从而提高你的网络安全性。

</details>

<details>

<summary>10 XX协议有哪些优缺点？用户如何根据自己的需求去选择？</summary>

<mark style="color:green;">问题回复</mark>：结论：如果只需要代理HTTP和HTTPS流量，且对安全性要求不高，可以选择HTTP代理协议；如果需要更好的安全性，可以选择HTTPS代理协议；如果需要代理多种类型的流量且速度要求较高，可以选择SOCKS4代理协议；如果需要更好的安全性和身份验证功能，可以选择SOCKS5代理协议。

<mark style="color:yellow;">1）HTTP：</mark>优点是易于使用，因为绝大多数Web浏览器和Web服务器都支持该协议。缺点是只能代理HTTP和HTTPS流量，不能代理其他协议的流量。此外，HTTP代理协议不支持身份验证和加密，因此在安全性方面有一定的缺陷。

<mark style="color:yellow;">2）HTTPS</mark>：它在HTTP协议的基础上增加了SSL/TLS协议的支持，可以对HTTP流量进行加密，可以对数据进行加密传输。缺点是相对于HTTP协议而言，HTTPS代理协议的配置和使用较为复杂。此外，HTTPS代理协议也不能代理所有类型的流量，只能代理HTTPS流量。

<mark style="color:yellow;">3）SOCKS4</mark>：优点是可以代理多种类型的流量，速度较快。缺点是不支持身份验证和加密，安全性较差，且仅支持[TCP协议](https://www.baidu.com/s?wd=TCP%E5%8D%8F%E8%AE%AE\&tn=SE_PcZhidaonwhc_ngpagmjz\&rsv_dl=gh_pc_zhidao)。

<mark style="color:yellow;">4）SOCKS5</mark>：SOCKS5代理协议是在SOCKS4协议的基础上增加了身份验证和加密功能，支持多种身份验证方式，包括用户名/密码、GSSAPI和TLS等。SOCKS5代理协议的优点是提供了更好的安全性，支持身份验证和加密，可以代理TCP流量和UDP流量。缺点是相对于SOCKS4协议而言，SOCKS5协议的配置和使用较为复杂。

</details>

<details>

<summary>11 代理服务器中的主机和端口是什么意思？</summary>

<mark style="color:green;">问题回复</mark>：代理服务器中的主机和端口是代理服务器的地址和端口号，用于确定网络流量的传输目的地和传输通道。

主机可以理解为代理服务器的地址，类似于门牌号。在网络中，每个设备都有一个唯一的IP地址，用于标识设备在网络中的位置。当用户需要访问互联网上的某个资源时，需要将请求发送到相应的服务器上，这时就需要知道代理服务器的地址（即主机），以便将请求发送到正确的代理服务器。

端口可以理解为代理服务器的门牌号，类似于房间号码。在网络中，每个应用程序都需要使用一个唯一的端口号，用于标识应用程序在设备中的位置。当用户发送请求到代理服务器时，需要将请求发送到相应的应用程序中，这时就需要知道代理服务器上的应用程序的端口号，以便将请求发送到正确的应用程序中。

</details>

<details>

<summary>12 代理服务器是否会影响网络速度和稳定性？</summary>

<mark style="color:green;">问题回复</mark>：代理服务器可能会影响网络速度和稳定性，因为在使用代理服务器时，网络流量需要先经过代理服务器再进行转发。如果代理服务器的带宽或性能不足，会导致网络速度变慢或者连接不稳定。

</details>

<details>

<summary>13 使用代理服务器后网络延迟较高是怎么回事？如何解决？</summary>

<mark style="color:green;">问题回复</mark>：可能的原因有代理服务器的带宽或性能不足，无法满足网络需求。或代理服务器所在的网络环境不稳定，导致网络延迟较高。

这边建议您选择带宽和性能较高的代理服务器，以确保代理服务器的性能足够支持自己的网络需求，或更换其他代理服务器重试。

</details>

<details>

<summary>14 如何导入自己的IP在桌面端使用？批量导入呢？</summary>

<mark style="color:green;">问题回复</mark>：少量IP使用时，参考代理IP配置流程。大量IP使用需求时，支持导入配置好的IP在桌面端上使用，您首先得在系统后台的IP管理页面中进行导入，具体操作如下：

1）如果您在已购买客服系统的IP套餐，可在套餐IP内查看；若没有则点击导入IP；

2）选择IP协议类型；

3）上传配置IP文件，没有文件的可以直接下载，在文件内补充IP信息即可提交上传；

4）上传成功，此时您可以在桌面端使用已配置的IP。

需要好用稳定IP，可[联系客服](https://t.me/xiaomm_007tg)获取体验，量大从优\


</details>

<details>

<summary>15 桌面端登录多个平台账号，由于网络代理或其他原因会掉线，账号掉线后会有提示吗，会自动重连吗？</summary>

<mark style="color:green;">问题回复</mark>：当您的网络代理连接不稳定时，会有对应的提示：

![](https://lh7-rt.googleusercontent.com/docsz/AD_4nXfXUrkm8NyktlAgT05mkb7Xoxe4bx2BM7_JuXJwZq59mlfrXIvmqtHct0m2JcS0fbzR0u_LMhS8aRt_wXqz9aS-syF0H0BmZy7uLGLclOnTCUYR_JUhYxo-Hj_Xng43f5xllqeu5bACdkT1lOokNOAfMywq?key=cxKLOe4yBeUbM5_97Gr4XA)

账号掉线后消息发不出去、一般的设置操作也无法使用，待网络代理稳定后自然恢复正常。

</details>
