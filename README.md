# Alışveriş Sitesi Mobil Uygulaması
Bu proje, React Native kullanılarak geliştirilmiş bir alışveriş sitesi mobil uygulamasıdır. Kullanıcıların ürünleri görüntüleyebileceği, detaylarına bakabileceği, sepete ürün ekleyebileceği ve siparişlerini yönetebileceği bir alışveriş deneyimi sunmaktadır.

## Başlangıç
Bu rehber, projeyi çalıştırmak ve geliştirmek için gerekli adımları içermektedir.

## 1. Metro Sunucusunu Başlatın
Metro sunucusu, React Native uygulamalarını çalıştırmak için kullanılan bir paket demetleyicisidir. Metro sunucusunu başlatmak için aşağıdaki adımları izleyin:

Proje dizinine gidin:

```
cd proje-dizini
```

Metro sunucusunu başlatın:


```
npx react-native start
```

Bu komut, Metro sunucusunu başlatır ve uygulamanızın kaynak kodunu demetlemeye başlar.

## 2. Uygulamanızı Başlatın
Metro sunucusu çalışırken, uygulamanızı başlatmak için aşağıdaki adımları izleyin:

iOS için:

```
npx react-native run-ios
```
Android için:

```
npx react-native run-android
```
Bu komutlar, uygulamanızı ilgili emülatör veya bağlı cihazda başlatacaktır. Uygulamanız başarılı bir şekilde derlenip çalıştırıldığında, cihazınızda veya emülatörde ana ekran görünecektir.

## 3. Uygulamanızı Değiştirme
Uygulamanızı değiştirmek ve geliştirmek için kaynak kod dosyalarını düzenleyebilirsiniz. Uygulamanın ana dosyası App.js olup, bu dosyada ve src klasöründeki diğer dosyalarda değişiklikler yapabilirsiniz.

Örneğin, ana ekranın içeriğini değiştirmek için src/screen/HomeScreen.js dosyasını düzenleyebilirsiniz:

```
import React from 'react';
import { View, Text, StyleSheet } from 'react-native';

const HomeScreen = () => {
  return (
    <View style={styles.container}>
      <Text style={styles.text}>Hoşgeldiniz! Yeni ürünlerimize göz atın.</Text>
    </View>
  );
};

const styles = StyleSheet.create({
  container: {
    flex: 1,
    justifyContent: 'center',
    alignItems: 'center',
  },
  text: {
    fontSize: 18,
    fontWeight: 'bold',
  },
});

export default HomeScreen;
```
Bu dosyada yapılan değişiklikler, uygulamanızın ana ekranında hemen yansıyacaktır.

### Ek Bilgiler
Uygulamanın nasıl çalıştığı, kullanılan teknolojiler ve bileşenler hakkında daha fazla bilgi için lütfen proje dokümantasyonunu inceleyin. Sorularınız veya katkılarınız için proje deposunda bir "Issue" açabilir veya doğrudan katkıda bulunabilirsiniz.

### Gereksinimler
Node.js

React Native CLI

Xcode (iOS için)

Android Studio (Android için)
