# CryptoUtility(V1.0)

This is a crypto utility which implements various algorithms and protocols.

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

##### X509:

​	pending

##### Key process:

​	Generate ECC/RSA Key

​	Key Wrap based on RFC3394

​	HKDF based on RFC5869

​	Parse RSA/ECC key(PEM or DER)

​	Get Public Key

​	Convert between PEM and DER format



