### ��ʾ��UUID��ʹ��UUID���������Ƽ�[UUID Generator](https://www.uuidgenerator.net/)

### ���ѣ����ÿ��ܵ����˻���ɾ��������

### ���ѣ��������ӷ�ʽʱ����ϸ�Ķ��������ע������! ! !

### ��֮ǰ�Ѿ�fork�����û�ɾ����Ŀ������fork����Ŀ! ! !

### �ѻָ�Vmess��VLESS��Trojan��Shadowsocks����������! ! !

### �����������Э�����ο�[HTTP·��/HTTP֧�ְ汾](https://devcenter.heroku.com/articles/http-routing#http-versions-supported)Ȼ�������޸ģ������о����û��޸ģ����޸Ĵ���Э��������Ӵ���ı���Ŀ���е��κ����Σ�����

## ����˴�����������

0.������Ŀ��stars

1.������Ŀfork���Լ��ֿ��޸�`Deploy to Heroku`����ָ���ַΪ�Լ��ֿ��ַ

[![Deploy](https://www.herokucdn.com/deploy/button.png)](https://dashboard.heroku.com/new?template=https://github.com/op1end/new2) 

2.���������ɫ`Deploy to Heroku`������ת��heroku app����ҳ�棬Ӧ�ó�����������дҲ�ܴ��������ֻ���heroku������ɣ�ѡ��ڵ㣨��������ŷ�ޣ������û�ֻ��Ҫ�Զ���UUID���CADDYIndexPage���ο���[Caddy��ҳ����](https://github.com/op1end/new2/blob/master/README.md#5caddy%E4%B8%BB%E9%A1%B5%E9%85%8D%E7%BD%AE))���������鱣��Ĭ�ϣ��������deploy�������㶨��   

3.������`We couldn't deploy your app because the source code violates the Salesforce Acceptable Use and External-Facing Services Policy.`��ʾ���򷵻زֿ⣬>`Setting`>`Repository name`�޸Ĳֿ�����

4.��ִ���˵�3���޸Ĳֿ����Ĳ�����������޸�app.json�е�name��description��ʮ����Ҫ���мǣ�������

5.ע��`repository`��������������Ŀ����

6.���޸�`Deploy to Heroku`����ָ���ַΪ�Լ��ֿ��ַ���ظ�`2`�Ĳ���

7.����ɾ���ߵĲ��ֱ�ʾ�Ѿ�����������

## vmess vless trojan-go shadowsocks��Ӧ�ͻ��˲����Ĳο�����,ĩβ��()������ݽ�Ϊ��ʾ

## 1��Xray Vmess/VLESS ws+tls

|**����**|**��Ӧֵ**|
|:------:|:---------:|
|**����Э��**|VLESS+ws+tls</br>Vmess+ws+tls|
|��������ַ|��ѡip���磺`uicdn.cf`��`icook.tw`��</br>Ӧ�ó�����.herokuapp.com|
|�˿�|443|
|Ĭ��UUID|8f91b6a0-e8ee-11ea-adc1-0242ac120002</br>**ע�⣺��ش���ʱ�Զ���UUID��**|
|����|Vmess: Auto</br>VLESS: none</br>**ע�⣺VmessĬ�Ͻ�ֹ���¼��ܷ�ʽ���ӣ�none��aes-128-cfb**|
|����Э��|ws|
|αװ����|none|
|αװhost|xxxx.workers.dev(CF Workers������ַ)</br>Ӧ�ó�����.herokuapp.com|
|SNI��ַ|xxxx.workers.dev(CF Workers������ַ)</br>Ӧ�ó�����.herokuapp.com|
|Path·��|/�Զ���UUID��-vless</br>/�Զ���UUID��-vmess</br>**ע�⣺ǰ��б��/** |
|Vmess����id��alterid��|0</br>Ĭ������AEAD</br>**ע�⣺��ѡ���2022.1.1֮��������ã���ʹ���߼�ʱ�������µĿͻ����Խ�������⡣����ʹ��Xray-core���û���Ӱ�졣**|
|�ײ㴫�䰲ȫ|tls|
|����֤����֤|false|

## 2��Xray Trojan ws+tls

|**����**|**��Ӧֵ**|
|:------:|:-------:|
|��������ַ|��ѡip���磺`uicdn.cf`��`icook.tw`��</br>Ӧ�ó�����.herokuapp.com|
|�˿�|443|
|����|8f91b6a0-e8ee-11ea-adc1-0242ac120002</br>**ע�⣺��ش���ʱ�Զ���UUID��**|
|����Э��|ws|
|Path·��|/�Զ���UUID��-trojan</br>**ע�⣺ǰ��б��/**|
|SNI��ַ|xxxx.workers.dev(CF Workers������ַ)</br>Ӧ�ó�����.herokuapp.com|
|αװhost</br>TLS Host|xxxx.workers.dev(CF Workers������ַ)</br>Ӧ�ó�����.herokuapp.com|

## 3��Xray Shadowsocks ws+tls

|**����**|**��Ӧֵ**|
|:------:|:-------:|
|��������ַ|��ѡip���磺`uicdn.cf`��`icook.tw`��</br>Ӧ�ó�����.herokuapp.com|
|�˿�|443|
|����|8f91b6a0-e8ee-11ea-adc1-0242ac120002</br>**ע�⣺��ش���ʱ�Զ���UUID��**|
|���ܷ�ʽ|chacha20-ietf-poly1305</br>[�������ܷ�ʽ��ο�](https://www.v2fly.org/config/protocols/shadowsocks.html#%E5%8A%A0%E5%AF%86%E6%96%B9%E5%BC%8F%E5%88%97%E8%A1%A8)|
|����Э��|ws|
|αװ����|none|
|αװhost</br>TLS Host|xxxx.workers.dev(CF Workers������ַ)</br>Ӧ�ó�����.herokuapp.com|
|Path·��|/�Զ���UUID��-ss</br>**ע�⣺ǰ��б��/**|
|**ע������**|**1.���ܷ�ʽѡ������о�����û�����������������������ĺ������Ŀ���е��κ����Σ�**</br>**2.ʹ��lean lede��SSRPlus+/Passwall���û��ֿ�ʹ��Xray/v2ray Shadowsocks ws+tls���ӡ�**|

## 4��Trojan+ws+tls�ͻ���֧��״̬�������ڸ��£�

|�ͻ���|�Ƿ�֧��Trojan+ws+tls|
|:----:|:------------------:|
|2dust V2RayN</br>2dust V2RayNG|�ǣ���ҪV2RayN4.26+��V2RayNG���°汾(Pre-release)</br>��Ҫ���Զ�.net framework 6.0�����߰汾|
|OpenWrt SSRPlus+|��|
|OpenWrt Passwall|�ǣ���Ҫ���°汾passwall|
|~~QV2Ray~~|~~QV2Ray~~|

## 5��Caddy��ҳ����

# Caddyindexpage���� (��ӭ����Pull Requests)

* �����������и���ϲ������ҳ���ӵ�CADDYIndexPage������

|#|��ַ|
|:-:|:-:|
| 1(Ĭ��) | [��ӭʹ��caddyҳ��](https://raw.githubusercontent.com/caddyserver/dist/master/welcome/index.html) |
| 2 | [3DCEListԪ�����ڱ�](https://github.com/wulabing/3DCEList/archive/master.zip) |
| 3 | [Spotify-Landing-Page-Redesign](https://github.com/WebDevSimplified/Spotify-Landing-Page-Redesign/archive/master.zip) |
| 4 | [dev-landing-page](https://github.com/flexdinesh/dev-landing-page/archive/master.zip) |
| 5 | [free-for-dev](https://github.com/ripienaar/free-for-dev/archive/master.zip) |
| 6 | [tailwindtoolbox-Landing-Page](https://github.com/tailwindtoolbox/Landing-Page/archive/master.zip) |
| 7 | [sandhikagalih/simple-landing-page](https://github.com/sandhikagalih/simple-landing-page/archive/master.zip) |
| 8 | [StartBootstrap/startbootstrap-new-age](https://github.com/StartBootstrap/startbootstrap-new-age/archive/master.zip) |
| 9 | [mikutap һ����������ֵ�ҳ��](https://github.com/AYJCSGM/mikutap/archive/master.zip) [��ʾ](https://aidn.jp/mikutap) |
| 10 | [WebGL����ģ��](https://github.com/PavelDoGreat/WebGL-Fluid-Simulation/archive/master.zip) [��ʾ](https://paveldogreat.github.io/WebGL-Fluid-Simulation/) |
| 11 | [loruki-website](https://github.com/bradtraversy/loruki-website/archive/master.zip) |
| 12 | [bongo.catһֻ���ֵ�è](https://github.com/Externalizable/bongo.cat/archive/master.zip) [��ʾ](https://bongo.cat/) |

### CloudFlare Workers�������루֧��VLESS\VMESS\Trojan-Go��WSģʽ���ɷֱ��������˺ŵ�Ӧ�ó�������UUID��path����һ�£�����˫����ֱ�ִ�У���һ���¾���550+550Сʱ��

1.���õ�һӦ�õķ�������

```
addEventListener(
  "fetch", event => {
    let url = new URL(event.request.url);
    url.host = "appname.herokuapp.com";
    let request = new Request(url, event.request);
    event.respondWith(
      fetch(request)
    )
  }
)
```

2.���õ�˫��ѭ��ִ�еķ�������

```
const SingleDay = 'Ӧ�ó�����1.herokuapp.com'
const DoubleDay = 'Ӧ�ó�����2.herokuapp.com'
addEventListener(
    "fetch",event => {
    
        let nd = new Date();
        if (nd.getDate()%2) {
            host = SingleDay
        } else {
            host = DoubleDay
        }
        
        let url=new URL(event.request.url);
        url.hostname=host;
        let request=new Request(url,event.request);
        event. respondWith(
            fetch(request)
        )
    }
)
```

3.���ö�ʵ��ѭ��ִ�еķ�������

```
const Day0 = 'app0.herokuapp.com'
const Day1 = 'app1.herokuapp.com'
const Day2 = 'app2.herokuapp.com'
const Day3 = 'app3.herokuapp.com'
const Day4 = 'app4.herokuapp.com'
addEventListener(
    "fetch",event => {
    
        let nd = new Date();
        let day = nd.getDate() % 5;
        if (day === 0) {
            host = Day0
        } else if (day === 1) {
            host = Day1
        } else if (day === 2) {
            host = Day2
        } else if (day === 3){
            host = Day3
        } else if (day === 4){
            host = Day4
        } else {
            host = Day1
        }
        
        let url=new URL(event.request.url);
        url.hostname=host;
        let request=new Request(url,event.request);
        event. respondWith(
            fetch(request)
        )
    }
)
```

### ԭ������Ŀ��ַ��https://github.com/mixool/xrayku

# ��л

- [Xrayku](https://github.com/mixool/xrayku)
- [Project V](https://github.com/v2fly/v2ray-core.git)
- [Project X](https://github.com/XTLS/Xray-core.git)
- [HeroKu](https://heroku.com)
- [heroku-vless](https://github.com/DanyTPG/heroku-vless.git)
- [Better Cloudflare IP](https://github.com/XIU2/CloudflareSpeedTest.git)
