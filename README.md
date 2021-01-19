# testBackend
Test untuk menjadi backend enginer

# Soal
1. Ubah variabel buah [ "apel", "jeruk", "sirsak", "kiwi", "nanas" ] menjadi string "apel, jeruk, sirsak, kiwi, nanas"
```php
<?php
$buah = [ "apel", "jeruk", "sirsak", "kiwi", "nanas" ];

function prosesString($params) {
	// tulis kode mu disini
}

// munculkan hasilnya disini
// hasil yang di inginkan : "apel, jeruk, sirsak, kiwi, nanas"
echo 
?>
```

2. buat buah dari class Buah dengan kriteria berikut
- nama buah jeruk dengan warna kuning
- nama buah salak dengan warna coklat

```php
<?php
class Buah {
  private $nama;
  private $warna;

  function set_nama($n) {
    $this->name = $n;
  }
    
  protected function set_warna($n) {
    $this->color = $n;
  }
    
  function get_nama($n) {
    return $this->name;
  }
    
  protected function get_warna($n) {
    return $this->color;
  }
   
}

/* soal */
// buat buah dengan nama jeruk dan berwarna kuning dengan menggunakan class Buah
// buat buah dengan nama salak dan berwarna coklat dengan menggunakan class Buah

// tulis kode mu disini
?>
```