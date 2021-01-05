# パスワード・認証
## 概要（当初版）
情報セキュリティで確保すべき機密性の根拠は認証である。認証の種類と特徴について、主にパスワードを例として述べる。また、シングル・サインオン（SSO）についても述べる。

<style>
body {
    counter-reset: h1;
}
h1 {
    counter-reset: h2;
}
h1:before {
    counter-increment: h1;
    content: counter(h1) ". ";
}
h2:before {
    counter-increment: h2;
    content: counter(h1) "." counter(h2) ". ";
}
</style>