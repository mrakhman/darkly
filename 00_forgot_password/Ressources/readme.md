### Web Parameter Tampering
1. Go to Login -> Forgot password
2. Inspect "Submit" button. Hidden input field has email webmaster@borntosec.com
3. Change this value to whatever - no email is received anyway
4. Hit submit

### Docs
https://owasp.org/www-community/attacks/Web_Parameter_Tampering

### Flag
The flag is:
`1D4855F7337C0C14B6F44946872C4EB33853F40B2D54393FBE94F49F1E19BBB0`
