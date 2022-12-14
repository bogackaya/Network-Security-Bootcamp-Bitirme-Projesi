# Network & Security Bootcamp Bitirme Projesi

![image](https://user-images.githubusercontent.com/100123477/184011326-5d6555a6-ae15-4aa3-b604-d3d9c86ded4d.png)

# **Projelerden İstenenler**
**Proje 1 :** ``` IPv4 omurga ve IPv6 omurga kendi içlerinde statik routing ile haberleşelebilmeli.```

**Proje 2 :** ``` IPv4 omurga ve IPv6 omurga kendi içlerinde ospf ile haberleşelebilmeli.```

``` Her iki senaryo içinde İstanbul lokasyonunda gerekli L2 düzenlemeler sağlanmalı. ```

``` Serverlara sadece izin verilen portlardan ulaşılmalı.```

# Yapılan İşlemler


- Her iki proje için;

- Topoloji yeniden çizildi.
 
- Kullanıcı cihazların, switchlerin ve routerların temel yapılandırılmaları(password, ip ataması, gateway v.b)tamamlandı.

- L2 ve L3 cihazlar için atanan şifreler;
 
  - **Password:** admin 
  - **Secret Password:** admin
  
- L2 ve L3 cihazlar için kullanılmayan portlar kapatıldı.
 
- İstenilen proje özelinde routelar tamamlandı gerekli ping testleri yapıldı.
 
- İstanbul routerı için sub interface yapılandırıldı her iki omurga için servislere erişim sağlandı.
 
- Proje doğrultusunda İstanbul routerı üzerine Acl yapılandırılması gerçekleştirildi.
 
  - Her iki omurga için sadece izin verilen tcp 80 ve udp 53 portları erişime açıldı.
  
  - Bu doğrultuda sadece iki porttan erişim sağlanırken icmp protokolü devre dışı kaldı.
  
- İstanbul switchinde gerekli vlan yapılandırılmaları tamamlandı.
 
  - Ipv4 için vlan 4,
 
  - Ipv6 için vlan 6 oluşturuldu gerekli ayarlar yapıldı.

- Her iki vlan için server ve dns ayarları yapıldı.

- Projede uygulanan bütün ayarlar proje üzerine not alındı.

***




  

 













