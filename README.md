# CryptoUtility(V2.0)

Download: link：https://pan.baidu.com/s/1O_t3tCLDltr8XIshB6azHQ  password：sez1 

​			   http://esctech.cn/wp-content/uploads/2020/04/Crypto%20UtilityV2.0.zip

This is a crypto utility which implements various algorithms and protocols.

Add below functions for V2.0

##### Support SM2

Encrypt/decrypt based on p256 curve

Generate signature/Verify signature based on p256 curve

##### Support SM3

##### Support SM4

Encrypt/Decrypt(ECB mode and CBC mode)

##### Support X509

Parse X.509 certificate

Convert X.509 certificate format

# CryptoUtility(V1.0)

##### Input format: 

​	Hex/Text(utf-8)/Text(base64)

##### Output format:

​	Hex/Text(base64)

##### Support AES:

​	AES128/192/256(ECB,CBC,CTR,CCM and GCM mode)

##### Support RSA:

​	Encrypt/Decrypt with RSA_PKCS1_PADDING, RSA_OAEPWithSHA-1MGF1Padding and RSA_OAEPWithSHA-256AndPadding

​	Generate/Verify signature with SHA1WithRSA_PKCS1V15, SHA256WithRSA_PKCS1V15, SHA384WithRSA_PKCS1V15, SHA512WithRSA_PKCS1V15, SHA1WithRSA_PSS, SHA256WithRSA_PSS and SHA384WithRSA_PSS

##### Support ECC:

​	ECDSA signature/verification with SHA1WithECDSA, SHA256WithECDSA

​	ECDH(pending)

##### HASH:

​	Support CRC32, MD5, SHA1, SHA224, SHA256, SHA384 and SHA512

##### MAC:

​	Support CMAC-AES128, CMAC-AES192, CMAC-AES256, HMAC-MD5, HMAC-SHA1, HMAC-SHA224, HMAC-SHA256, HMAC-SHA384, HMAC-SHA512

##### Key process:

​	Generate ECC/RSA Key

​	Key Wrap based on RFC3394

​	HKDF based on RFC5869

​	Parse RSA/ECC key(PEM or DER)

​	Get Public Key

​	Convert between PEM and DER format



