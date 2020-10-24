
<a name="module_Griyabayar"></a>
## Griyabayar

* [Griyabayar](#module_Griyabayar)
    * _@_
        * [.@](#module_Griyabayar.@)
    * _Service_
        * [./page-login](#module_Griyabayar./page-login)
        * [./function-laporan](#module_Griyabayar./function-laporan)
        * [./products](#module_Griyabayar./products)
        * [./format](#module_Griyabayar./format)
        * [./function-preinq](#module_Griyabayar./function-preinq)
        * [./function-inq](#module_Griyabayar./function-inq)
        * [./function-pay](#module_Griyabayar./function-pay)



<a name="module_Griyabayar.@"></a>
### Griyabayar.@
**Akses lebih dari 1 Akun**



<a name="module_Griyabayar./page-login"></a>
### Griyabayar./page-login
**Request**


| Param | Type | Description |
| --- | --- | --- |
| _id | <code>String</code> | awalan `griyabayar-`, wajib diisi |
| user_id | <code>String</code> | user_id/username, wajib diisi |
| pass | <code>String</code> | pass/password, wajib diisi |
| MAC_ADD | <code>String</code> | MAC_ADD/mac address terdaftar, wajib diisi |

**Example**  
```


<a name="module_Griyabayar./function-laporan"></a>
### Griyabayar./function-laporan
**Request**


| Param | Type | Description |
| --- | --- | --- |
| _id | <code>String</code> | awalan `griyabayar-`, wajib diisi |
| tgl | <code>String</code> | tgl, tanggal awal, format `DDMMYYYY` |
| tgl2 | <code>String</code> | tgl2, tanggal akhir, format `DDMMYYYY` |
| type | <code>String</code> | type, `0`,`1`,`2`,`3`, untuk `lengkap`,`sederhana`,`harian`,`mutasi` |
| order | <code>String</code> | order, `0`,`1`, untuk `asc`,`desc` |
| waktu | <code>String</code> | waktu, waktu awal, format `MMHH` |
| waktu2 | <code>String</code> | waktu2, waktu akhir, format `MMHH` |

**Example**  
```


<a name="module_Griyabayar./products"></a>
### Griyabayar./products
**Request**


| Param | Type | Description |
| --- | --- | --- |
| _id | <code>String</code> | awalan `griyabayar-`, wajib diisi |

**Example**  
```


<a name="module_Griyabayar./format"></a>
### Griyabayar./format
**Request**


| Param | Type | Description |
| --- | --- | --- |
| _id | <code>String</code> | awalan `griyabayar-`, wajib diisi |

**Example**  
```


<a name="module_Griyabayar./function-preinq"></a>
### Griyabayar./function-preinq
**Request**


| Param | Type | Description |
| --- | --- | --- |
| _id | <code>String</code> | awalan `griyabayar-`, wajib diisi |
| uid | <code>String</code> | wajib diisi |

**Example**  
```


<a name="module_Griyabayar./function-inq"></a>
### Griyabayar./function-inq
**Request**


| Param | Type | Description |
| --- | --- | --- |
| _id | <code>String</code> | awalan `griyabayar-`, wajib diisi |
| uid | <code>String</code> | wajib diisi |

**Example**  
```


<a name="module_Griyabayar./function-pay"></a>
### Griyabayar./function-pay
**Request**


| Param | Type | Description |
| --- | --- | --- |
| _id | <code>String</code> | awalan `griyabayar-`, wajib diisi |
| uid | <code>String</code> | wajib diisi |

**Example**  
```
