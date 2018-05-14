# js-base64-byHexString
JavaScript for implementation for Java: Base64.encodeBase64(byte[] binaryData)
In Java:
```Java
    MessageDigest digester = MessageDigest.getInstance("MD5");
    digester.update(rawPass.getBytes("UTF-8"));
    byte[] hash = digester.digest();
    return new String(Base64.encodeBase64(hash));
```
In js:
```JavaScript
    var originPw = '123456';
    var md5Pw = md5(originPw);
    console.log(md5Pw);
    var base64Pw = Base.decodeByHexString(md5Pw);
    console.log(base64Pw);
```
