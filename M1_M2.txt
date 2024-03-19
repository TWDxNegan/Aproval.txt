def B1():
    a = "[FBAN/FB4A;FBAV/" + str(random.randint(49, 66)) + ".0.0." + str(random.randrange(20, 49)) + str(random.randint(11, 99)) + ";FBBV/" + str(random.randint(11111111, 77777777))
    
    b = random.choice([
    ";[FBAN/FB4A;FBAV/196.0.0.69;FBBV/654519483;FBDM/{density=3.0,width=1080,height=2400};FBLC/fr_FR;FBRV/250986361;FBCR/TIM 41;FBMF/Xiaomi;FBBD/Xiaomi;FBPN/com.facebook.katana;FBDV/M2002J9G;FBSV/10.0.1;FBOP/1;FBCA/armeabi-v7a:armeabi;]", 
    ";[FBAN/FB4A;FBAV/330.0.0.31.120;FBBV/286016007;FBDM/{density=2.0,width=720,height=1436};FBLC/en_US;FBCR/airtel;FBMF/Ulefone;FBBD/Ulefone;FBPN/com.facebook.katana;FBDV/Note 8P;FBSV/10;nullFBCA/armeabi-v7a:armeabi;]", 
    ";[FBAN/FB4A;FBAV/214.0.0.43.83;FBBV/147376170;FBDM/{density=3.0,width=720,height=1440};FBLC/en_US;FBCR/airtel;FBMF/Itel;FBBD/itel;FBPN/com.facebook.katana;FBDV/itel W6002E;FBSV/7;nullFBCA/arm64-v8a:;]", 
    ";[FBAN/FB4A;FBAV/417.0.0.33.65;FBPN/com.facebook.katana;FBLC/in_ID;FBBV/480086274;FBCR/Corporation Tbk;FBMF/realme;FBBD/realme;FBDV/RMX3740;FBSV/7.1.2;FBCA/x86:armeabi-v7a;FBDM/{density=1.0,width=540,height=960};FB_FW/1;FBRV/483172840;]"
    ])
    
    ua = a + b
    return ua
