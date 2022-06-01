# Arrow Functions (ES6)

* https://www.youtube.com/watch?v=h33Srr5J9nY

# 8 Must Know JavaScript Array Methods

* https://www.youtube.com/watch?v=R8rmfD9Y5-c

En çok kullanılandan en az kullanılana göre sıralama

* map 
* filter
* foreach 
* includes 
* find

en önemlileri diğerleri zorlayabilir çoğu yerde kullanılmaz bilmek iyidir ama yinede.

# JavaScript Higher Order Functions & Arrays 

* https://www.youtube.com/watch?v=rRgD1yVwIvE

- genel video üstteki 3 video ile js hakkında akar gidersin


# VUE

[TIKLA](https://sfc.vuejs.org/#eyJBcHAudnVlIjoiPHRlbXBsYXRlPlxuICA8aDE+e3sgbXNnIH19PC9oMT5cbiAgPGlucHV0IHYtbW9kZWw9XCJtc2dcIj5cbjwvdGVtcGxhdGU+XG5cbjxzY3JpcHQgc2V0dXA+XG5pbXBvcnQgeyByZWYgfSBmcm9tICd2dWUnXG5cbmNvbnN0IG1zZyA9IHJlZignU0EnKVxuXG4vLyBFTiDDh09LIEtVTExBTklMQU4gLT4gcmVmXG5cbi8vIGNvbnN0IG1zZyA9IHJlZignSGVsbG8gV29ybGQhJylcbi8vIG1zZyBkaXllIGJpciB2YXJpYWJsZSBvbHXFn3R1cnVsdXlvciBidW51biByZWYgaWxlIG9sdcWfdHVydWxtYSBzZWJlYmkgdnVlLmpzIGluIGJpciDDtnplbGxpxJ9pIG9sYW4gZGluYW1payBvbGFyYWsgbyBjb25zdGFudCDEsSBkZcSfacWfdGlyaWxlYmlsbWVzaVxuXG4vLyB2LW1vZGVsIFxuLy8gdi1tb2RlbCBpbnB1dGxhcmRhIHNlbGVjdGJveGxhcmRhIHZleWEgaW5wdXQgdGFyesSxIGLDvHTDvG4gaHRtbCBibG9rbGFyxLFuZGEga3VsbGFuxLFsYWJpbGl5b3IuIFxuXG4vLzxpbnB1dCB2LW1vZGVsPVwibXNnXCI+ICB0ZW1wbGF0ZSB0YWdsYXLEsSBpw6dlcmlzaW5kZSBhw6fEsWxkxLHEn8SxbmRhLCBzY3JpcHQgdGFnxLEgacOnZXJpc2luZGUgbXNnIGRpeWUgYWRsYW5kxLFyxLFsYW4gY29uc3RhbnRhIGJpbmQgb2x1eW9yIHZlIG8gaW5wdXRhIGRlxJ9lciBnaXJpbGRpxJ9pbmRlIGJpemltIGNvbnN0IG1zZyB2YXJpYWJsZcSxbcSxeiBkaW5hbWlrIG9sYXJhayBnw7xuY2VsbGVuaXlvci5cbjwvc2NyaXB0PlxuXG4iLCJpbXBvcnQtbWFwLmpzb24iOiJ7XG4gIFwiaW1wb3J0c1wiOiB7XG4gICAgXCJ2dWVcIjogXCJodHRwczovL3NmYy52dWVqcy5vcmcvdnVlLnJ1bnRpbWUuZXNtLWJyb3dzZXIuanNcIlxuICB9XG59In0=)


Aşağıdaki kodu dikkate almadan üstteki url ye tıkla oradan direkt olarak kodların kullanıldığı yeri görebilirsin.



```

<template>
  <h1>{{ msg }}</h1>
  <input v-model="msg">
</template>

<script setup>
import { ref } from 'vue'

const msg = ref('SA')

// EN ÇOK KULLANILAN -> ref

// const msg = ref('Hello World!')
// msg diye bir variable oluşturuluyor bunun ref ile oluşturulma sebebi vue.js in bir özelliği olan dinamik olarak o constant ı değiştirilebilmesi

// v-model 
// v-model inputlarda selectboxlarda veya input tarzı bütün html bloklarında kullanılabiliyor. 

//<input v-model="msg">  template tagları içerisinde açıldığında, script tagı içerisinde msg diye adlandırılan constanta bind oluyor ve o inputa değer girildiğinde bizim const msg variableımız dinamik olarak güncelleniyor.
</script>

```






