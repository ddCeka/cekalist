<div align="center">
  <h1>Hosts file curated for Personal use</h1> 
</div>

<div align="justify">
Saya mengumpulkan list ini untuk penggunaan pribadi dan kelompok pribadi saya, but feel free to use if you want to 😘.
</div>
&nbsp;
<div align="justify">
   <h3>Pengguna bertanggung jawab atas keamanan perangkat pengguna sendiri, karma sendiri, dosa sendiri, atas tindakannya sendiri dan segala hal yang dapat melanggar hukum. Jika pengguna mengacaukan sesuatu atau melanggar hukum apa pun saat menggunakan proyek ini, itu adalah kesalahan pengguna.</h3>
</div>
&nbsp;
&nbsp;
<div align="center"> 
  <a href="https://github.com/ddCeka/CekaList" > 
    <img src="https://img.shields.io/github/repo-size/ddCeka/CekaList?label=Repo%20Size&color=black" alt="repo size" >
  <a/>
  <a href="https://github.com/ddCeka/CekaList/commits/master" > 
    <img src="https://img.shields.io/badge/Updated%20Hosts-24/Sep/2021-darkblue" >
  <a/>
  <a href="https://github.com/ddCeka/CekaList/commits/master" > 
    <img src="https://img.shields.io/github/last-commit/ddCeka/CekaList?label=Last%20Commit" alt="last commit" >
  <a/>
  <a href="https://github.com/ddCeka/CekaList/commits/master" > 
    <img src="https://img.shields.io/badge/Maintained-Yes-blue" >
  <a/>
  <a href="https://github.com/ddCeka/CekaList/blob/master/LICENSE" > 
    <img src="https://img.shields.io/github/license/ddCeka/CekaList?label=License&color=lightblue" alt="license" >
  <a/>
</div>
&nbsp;
&nbsp;


## <ins>Daftar Isi</ins>

- [Variasi file hosts](#variasi-filter-blokir)
- [Cara Penggunaan?](#cara-penggunaan)
- [Alternatif Lain Untuk Android](#alternatif-lain-untuk-android)
- [Setting DNS](#setting-dns)
- [Sumber](#sumber)
- [Lisensi](#lisensi)
&nbsp;

## <ins>Variasi Filter Blokir</ins>

| Daftar hosts | Deskripsi | Link |
| --- |---| --- |
| Block list | Daftar ini berisi Iklan, Gangguan, Analitik, dan Pelacak di Indonesia. _Disarankan untuk menggunakan daftar ini_ untuk memblokir iklan-iklan di website Indonesia. | [`link`](https://raw.githubusercontent.com/ddCeka/CekaList/master/blocklist/blocklist)
| Sosmed | Daftar ini adalah tambahan untuk memblokir korporasi dan sosial media dari berbagai sumber. Memblokir Facebook, LinkedIn, Pinterest dan TikTok. | [`link`](https://raw.githubusercontent.com/ddCeka/CekaList/master/blocklist/sosmed)
| Block list-Extended | Saya tidak merekomendasikan daftar ini untuk sebagian besar pengguna. Ini adalah daftar blokir yang sangat agresif untuk pelacakan, penargetan geografis, & iklan. Daftar ini kemungkinan akan merusak fungsionalitas, jadi jangan menggunakannya kecuali Anda bersedia mempertahankan _White List_ Anda sendiri. Gunakan ini dengan hati-hati. Ingatlah bahwa ini adalah daftar yang agresif. | [`link`](https://raw.githubusercontent.com/ddCeka/CekaList/master/blocklist/blocklist-extended)
| Unblock list | File host untuk membuka blokir beberapa situs yang diblokir di Indonesia (berdasarkan [`bebasid`](https://bebasid.github.io/)). Dengan filter _`anti LGBT & anti Child Abuse`_, Iklan dan situs Judi | [`link`](https://raw.githubusercontent.com/ddCeka/CekaList/master/unblocklist/whitelist)
| Unblock list-SFW | File host untuk membuka blokir beberapa situs yang diblokir di Indonesia khusus konten SFW (Konten semua umur). | [`link`](https://raw.githubusercontent.com/ddCeka/CekaList/master/unblocklist/whitelist-sfw)

&nbsp;

## <ins>Cara Penggunaan?</ins>

- Salin salah satu URL di atas ke dalam aplikasi HOSTS apa pun yang memungkinkan penambahan URL sebagai sumber.

- Awalnya dibuat untuk digunakan dengan Android.  Untuk perangkat yang tidak di-root, gunakan [personalDNSfilter.](https://f-droid.org/en/packages/dnsfilter.android/)  Untuk perangkat yang di-rooting, coba [AdAway](https://f-droid.org/en/packages/org.adaway/).  Semua tersedia di [F-Droid.](https://www.f-droid.org/)

- Perlu dicatat bahwa DNSfilter dapat menangani entri karakter pengganti, yang akan menawarkan cakupan pemblokiran subdomain yang lebih baik, tetapi menggunakan VPN bawaan Android untuk menangani pemblokiran.
&nbsp;

## <ins>Alternatif lain untuk Android</ins>

Daripada menggunakan file HOSTS, jika Anda menggunakan Android Pie atau lebih tinggi, Anda dapat menggunakan fitur Private DNS (DNS over TLS) dari penyedia terkemuka seperti [AdGuard](https://adguard.com/en/download.html), [NextDNS](https://play.google.com/store/apps/details?id=io.nextdns.NextDNS&hl=en_IE&referrer=utm_source%3Dgoogle%26utm_medium%3Dorganic%26utm_term%3Dnextdns+android) atau [Quad9](https://play.google.com/store/apps/details?id=com.quad9.aegis&utm_campaign=quad9-blog&pcampaignid=MKT-Other-global-all-co-prtnr-py-PartBadge-Mar2515-1) untuk pemblokiran.
&nbsp;

## <ins>Setting DNS</ins>

Custom DNS untuk Android 9.0+ [Non-Root] contoh dari cara di atas
 1. Buka Pengaturan → Jaringan & internet → Lanjutan → DNS Pribadi.
 2. Pilih opsi nama host penyedia DNS Pribadi.
 3. Masukan dari contoh penyedia DNS dibawah dan tekan simpan.
---
[Adguard DNS(Adblocking Supported):](https://adguard.com/en/adguard-dns/overview.html)
```
	dns.adguard.com
```
[NextDNS(Adblocking with Whitelist Supported)](https://help.nextdns.io/t/m1hmv0k/which-setup-type-to-use)
```
	(IdAnda).dns.nextdns.io
```
[Quad9 DNS(Adblocking Supported):](https://support.quad9.net/hc/en-us/articles/360046736911-Configure-Android-to-use-Private-DNS-feature-with-Quad9)
```
	dns.quad9.net
```
[DNS Watch:](https://www.watchguard.com/help/docs/help-center/en-US/Content/en-US/Fireware/services/dnswatch/dnswatch_config_examples_c.html#:~:text=In%20the%20DNSWatch%20settings%2C%20enable,configured%20with%20different%20DNS%20servers.)
```
	resolver1.dns.watch
	resolver1.dns.watch
```
[Blah DNS:](https://github.com/ookangzheng/blahdns)
```
	dot-ch.blahdns.com
```
[CloudFlare DNS:](https://www.cloudflare.com/en-gb/learning/dns/what-is-1.1.1.1)
```
	1dot1dot1dot1.cloudflare-dns.com
```
---
&nbsp;
&nbsp;

## <ins>Sumber</ins>

| Source List | Type | Category | Comments |
| --- | --- | --- | --- |
https://raw.githubusercontent.com/jmdugan/blocklists/master/corporations/microsoft/linkedin.easylist|adblock|`domain`|Sosmed filter
https://raw.githubusercontent.com/jmdugan/blocklists/master/corporations/facebook/all-but-whatsapp.easylist|adblock|`domain`|Sosmed filter
https://raw.githubusercontent.com/jmdugan/blocklists/master/corporations/pinterest/all.easylist|adblock|`domain`|Sosmed filter
https://raw.githubusercontent.com/ddCeka/personalhost/master/Facebook.txt|hostfile|`domain`|Sosmed filter
https://raw.githubusercontent.com/ddCeka/personalhost/master/LinkedIn.txt|hostfile|`domain`|Sosmed filter
https://raw.githubusercontent.com/ddCeka/personalhost/master/Pinterest.txt|hostfile|`domain`|Sosmed filter
https://raw.githubusercontent.com/ddCeka/personalhost/master/Tiktok.txt|hostfile|`domain`|Sosmed filter
https://raw.githubusercontent.com/bebasid/bebasid/master/releases/hosts|hostfile|`domain`|LGBT,Child Abuse,Gambling and Ads domain unlisted
https://raw.githubusercontent.com/bigdargon/hostsVN/master/source/adservers-all.txt|hostfile|`ads`|
https://s3.amazonaws.com/lists.disconnect.me/simple_ad.txt|hostfile|`ads`|
https://s3.amazonaws.com/lists.disconnect.me/simple_malvertising.txt|hostfile|`malware`|
https://s3.amazonaws.com/lists.disconnect.me/simple_tracking.txt|hostfile|`trackers`|
https://raw.githubusercontent.com/deathbybandaid/piholeparser/master/Subscribable-Lists/ParsedBlacklists/ABPindo.txt|hostfile|`ads`|
https://raw.githubusercontent.com/deathbybandaid/piholeparser/master/Subscribable-Lists/CountryCodesLists/Indonesia.txt|hostfile|`ads`|
https://raw.githubusercontent.com/AmnestyTech/investigations/master/2021-07-18_nso/domains.txt|hostfile|`malware`|
https://raw.githubusercontent.com/Perflyst/PiHoleBlocklist/master/android-tracking.txt|hostfile|`ads` `tracker`|
https://raw.githubusercontent.com/stamparm/blackbook/master/blackbook.txt|hostfile|`ads` `trackers`|
https://raw.githubusercontent.com/blokadaorg/landing-github-pages/master/blocklists/exodusprivacy/standard/hosts.txt|hostfile|`ads` `trackers`|Some domain unlisted
https://raw.githubusercontent.com/uBlockOrigin/uAssets/master/filters/badware.txt|adblock|`ads`|
https://raw.githubusercontent.com/uBlockOrigin/uAssets/master/filters/filters.txt|adblock|`ads`|
https://raw.githubusercontent.com/uBlockOrigin/uAssets/master/filters/privacy.txt|adblock|`ads` `trackers`|
https://v.firebog.net/hosts/static/w3kbl.txt|hostfile|`ads`|
https://v.firebog.net/hosts/Admiral.txt|hostfile|`ads`|
https://v.firebog.net/hosts/Prigent-Ads.txt|hostfile|`trackers`|
https://bitbucket.org/ethanr/dns-blacklists/raw/8575c9f96e5b4a1308f2f12394abd86d0927a4a0/bad_lists/Mandiant_APT1_Report_Appendix_D.txt|hostfile|`malware`|
https://orca.pet/notonmyshift/domains.txt|hostfile|`ads`|
https://gitlab.com/quidsup/notrack-blocklists/raw/master/notrack-malware.txt|hostfile|`malware`|
https://raw.githubusercontent.com/DandelionSprout/adfilt/master/Alternate%20versions%20Anti-Malware%20List/AntiMalwareDomains.txt|hostfile|`malware`|
https://osint.digitalside.it/Threat-Intel/lists/latestdomains.txt|hostfile|`malware`|
https://urlhaus.abuse.ch/downloads/hostfile|hostfile|`malware`|
https://raw.githubusercontent.com/Hakame-kun/uBlock-Filters-Indonesia/master/uBlock%20Indo/ubindo.txt|adblock|`ads`|
https://raw.githubusercontent.com/ABPindo/indonesianadblockrules/master/subscriptions/abpindo.txt|adblock|`ads`|
https://raw.githubusercontent.com/realodix/AdBlockID/master/output/adblockid.txt|adblock|`ads`|
https://filters.adtidy.org/extension/chromium/filters/4.txt|adblock|`domain`|Sosmed filter
https://raw.githubusercontent.com/AdguardTeam/AdguardFilters/master/SocialFilter/sections/popups.txt|adblock|`domain`|Sosmed filter
https://raw.githubusercontent.com/AdguardTeam/AdguardFilters/master/SocialFilter/sections/social_trackers.txt|adblock|`trackers`|Sosmed filter
https://raw.githubusercontent.com/AdguardTeam/AdguardFilters/master/MobileFilter/sections/adservers.txt|adblock|`ads`|
https://raw.githubusercontent.com/AdguardTeam/AdguardFilters/master/MobileFilter/sections/specific_app.txt|adblock|`ads`|
https://raw.githubusercontent.com/AdguardTeam/cname-trackers/master/combined_disguised_trackers_justdomains.txt|hostfile|`trackers`|
https://raw.githubusercontent.com/AdguardTeam/AdguardFilters/master/SpywareFilter/sections/tracking_servers_firstparty.txt|adblock|`trackers`|
https://raw.githubusercontent.com/AdguardTeam/AdguardFilters/master/SpywareFilter/sections/tracking_servers.txt|adblock|`trackers`|
https://raw.githubusercontent.com/AdguardTeam/AdGuardSDNSFilter/master/Filters/rules.txt|adblock|`ads`|
https://raw.githubusercontent.com/Spam404/lists/master/adblock-list.txt|adblock|`ads`|
https://raw.githubusercontent.com/Spam404/lists/master/main-blacklist.txt|hostfile|`ads` `malware`|
https://fanboy.co.nz/r/fanboy-complete.txt|adblock|`ads` `trackers`|This is the Complete list
https://easylist.to/easylist/easylist.txt|adblock|`ads`|
https://easylist.to/easylist/easyprivacy.txt|adblock|`trackers`|
https://raw.githubusercontent.com/Yhonay/antipopads/master/popads.txt|adblock|`ads`|
https://raw.githubusercontent.com/ddCeka/personalhost/master/Custom%20List.txt|hostfile|`ads` `malware` `trackers`|Curated custom list

&nbsp;
&nbsp;

## <ins>Lisensi</ins>
---
```
           DO WHAT THE FUCK YOU WANT TO PUBLIC LICENSE
                   Version 2, December 2004
 
Copyright (C) 2004 Sam Hocevar <sam@hocevar.net>

Everyone is permitted to copy and distribute verbatim or modified
copies of this license document, and changing it is allowed as long
as the name is changed.
 
           DO WHAT THE FUCK YOU WANT TO PUBLIC LICENSE
  TERMS AND CONDITIONS FOR COPYING, DISTRIBUTION AND MODIFICATION

 0. You just DO WHAT THE FUCK YOU WANT TO.
```
# cekalist