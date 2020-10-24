
<a name="module_Rita"></a>
## Rita

* [Rita](#module_Rita)
    * _@_
        * [.@](#module_Rita.@)
    * _Service_
        * [./login/otp-request](#module_Rita./login/otp-request)
        * [./oauth/token](#module_Rita./oauth/token)
        * [./homescreen/profile](#module_Rita./homescreen/profile)
        * [./homescreen/home](#module_Rita./homescreen/home)
        * [./balloon](#module_Rita./balloon)
        * [./transaction/get](#module_Rita./transaction/get)
        * [./notification/get](#module_Rita./notification/get)
        * [./notification/read-update](#module_Rita./notification/read-update)
        * [./profile/home](#module_Rita./profile/home)
        * [./profile/profile](#module_Rita./profile/profile)
        * [./product/get-product/:path](#module_Rita./product/get-product/_path)
        * [./product/activation-product-frc](#module_Rita./product/activation-product-frc)
        * [./product/activation-product-spv](#module_Rita./product/activation-product-spv)
        * [./product/activation-product-recharges](#module_Rita./product/activation-product-recharges)
        * [./ligaSuper/checkKPK](#module_Rita./ligaSuper/checkKPK)
        * [./ligaSuper/checkSPV](#module_Rita./ligaSuper/checkSPV)



<a name="module_Rita.@"></a>
### Rita.@
**Akses lebih dari 1 Akun**



<a name="module_Rita./login/otp-request"></a>
### Rita./login/otp-request
**Request**


| Param | Type | Description |
| --- | --- | --- |
| _id | <code>String</code> | awalan `rita-`, wajib diisi, digunakan untuk akses lebih dari 1 akun |
| msisdn | <code>String</code> | wajib diisi, MSISDN Pemilik Toko |
| qrCode | <code>String</code> | wajib diisi, ID Retailer |

**Example**  
```


<a name="module_Rita./oauth/token"></a>
### Rita./oauth/token
**Request**


| Param | Type | Description |
| --- | --- | --- |
| _id | <code>String</code> | awalan `rita-`, wajib diisi, digunakan untuk akses lebih dari 1 akun |
| username | <code>String</code> | wajib diisi, MSISDN Pemilik Toko |
| password | <code>String</code> | wajib diisi, Kode OTP |
| qrCode | <code>String</code> | wajib diisi, ID Retailer |

**Example**  
```


<a name="module_Rita./homescreen/profile"></a>
### Rita./homescreen/profile
**Request**


| Param | Type | Description |
| --- | --- | --- |
| _id | <code>String</code> | awalan `rita-`, wajib diisi, digunakan untuk akses lebih dari 1 akun |

**Example**  
```


<a name="module_Rita./homescreen/home"></a>
### Rita./homescreen/home
**Request**


| Param | Type | Description |
| --- | --- | --- |
| _id | <code>String</code> | awalan `rita-`, wajib diisi, digunakan untuk akses lebih dari 1 akun |

**Example**  
```


<a name="module_Rita./balloon"></a>
### Rita./balloon
**Request**


| Param | Type | Description |
| --- | --- | --- |
| _id | <code>String</code> | awalan `rita-`, wajib diisi, digunakan untuk akses lebih dari 1 akun |

**Example**  
```


<a name="module_Rita./transaction/get"></a>
### Rita./transaction/get
**Request**


| Param | Type | Description |
| --- | --- | --- |
| _id | <code>String</code> | awalan `rita-`, wajib diisi, digunakan untuk akses lebih dari 1 akun |

**Example**  
```


<a name="module_Rita./notification/get"></a>
### Rita./notification/get
**Request**


| Param | Type | Description |
| --- | --- | --- |
| _id | <code>String</code> | awalan `rita-`, wajib diisi, digunakan untuk akses lebih dari 1 akun |

**Example**  
```


<a name="module_Rita./notification/read-update"></a>
### Rita./notification/read-update
**Request**


| Param | Type | Description |
| --- | --- | --- |
| _id | <code>String</code> | awalan `rita-`, wajib diisi, digunakan untuk akses lebih dari 1 akun |
| id | <code>String</code> | wajib diisi |

**Example**  
```


<a name="module_Rita./profile/home"></a>
### Rita./profile/home
**Request**


| Param | Type | Description |
| --- | --- | --- |
| _id | <code>String</code> | awalan `rita-`, wajib diisi, digunakan untuk akses lebih dari 1 akun |

**Example**  
```


<a name="module_Rita./profile/profile"></a>
### Rita./profile/profile
**Request**


| Param | Type | Description |
| --- | --- | --- |
| _id | <code>String</code> | awalan `rita-`, wajib diisi, digunakan untuk akses lebih dari 1 akun |

**Example**  
```


<a name="module_Rita./product/get-product/_path"></a>
### Rita./product/get-product/:path
**Request**


| Param | Type | Description |
| --- | --- | --- |
| _id | <code>String</code> | awalan `rita-`, wajib diisi, digunakan untuk akses lebih dari 1 akun |

**Example**  
```


<a name="module_Rita./product/activation-product-frc"></a>
### Rita./product/activation-product-frc
**Request**


| Param | Type | Description |
| --- | --- | --- |
| _id | <code>String</code> | awalan `rita-`, wajib diisi, digunakan untuk akses lebih dari 1 akun |
| code | <code>String</code> | boleh kosong, boleh diulang |
| price | <code>String</code> | boleh kosong, boleh diulang |
| msisdn | <code>String</code> | wajib diisi, boleh diulang |
| pin | <code>String</code> | wajib diisi |
| productCode | <code>String</code> | wajib diisi |
| productPrice | <code>String</code> | wajib diisi |
| trxMsisdn | <code>String</code> | wajib diisi |

**Example**  
```


<a name="module_Rita./product/activation-product-spv"></a>
### Rita./product/activation-product-spv
**Request**


| Param | Type | Description |
| --- | --- | --- |
| _id | <code>String</code> | awalan `rita-`, wajib diisi, digunakan untuk akses lebih dari 1 akun |
| pin | <code>String</code> | wajib diisi |
| productCode | <code>String</code> | wajib diisi, untuk `SPVBLANK` |
| productPrice | <code>String</code> | wajib diisi, untuk `SPVBLANK` |
| qrVoucher | <code>String</code> | wajib diisi, untuk `SPVBLANK`, boleh diulang |
| price | <code>String</code> | wajib diisi, untuk `SPV0`, boleh diulang |
| voucher | <code>String</code> | wajib diisi, untuk `SPV0`, boleh diulang |
| spvType | <code>String</code> | wajib diisi, `SPVBLANK`,`SPV0` |
| trxMsisdn | <code>String</code> | wajib diisi |

**Example**  
```


<a name="module_Rita./product/activation-product-recharges"></a>
### Rita./product/activation-product-recharges
**Request**


| Param | Type | Description |
| --- | --- | --- |
| _id | <code>String</code> | awalan `rita-`, wajib diisi, digunakan untuk akses lebih dari 1 akun |
| groupFeature | <code>String</code> | wajib diisi, `RITATOPUP`,`RITAPACKAGE`,`VASPRODUCTS` |
| msisdn | <code>String</code> | wajib diisi |
| pin | <code>String</code> | wajib diisi |
| productCode | <code>String</code> | wajib diisi |
| productPrice | <code>String</code> | wajib diisi |
| trxMsisdn | <code>String</code> | wajib diisi |

**Example**  
```


<a name="module_Rita./ligaSuper/checkKPK"></a>
### Rita./ligaSuper/checkKPK
**Request**


| Param | Type | Description |
| --- | --- | --- |
| _id | <code>String</code> | awalan `rita-`, wajib diisi, digunakan untuk akses lebih dari 1 akun |
| subscriberMsisdn | <code>String</code> | waajib |

**Example**  
```


<a name="module_Rita./ligaSuper/checkSPV"></a>
### Rita./ligaSuper/checkSPV
**Request**


| Param | Type | Description |
| --- | --- | --- |
| _id | <code>String</code> | awalan `rita-`, wajib diisi, digunakan untuk akses lebih dari 1 akun |
| voucherQrCode | <code>String</code> | wajib |

**Example**  
```
