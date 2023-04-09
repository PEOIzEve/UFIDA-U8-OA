# UFIDA U8 OA test.JSP XSS vulnerability

## Vulnerability Description

There is an XSS vulnerability in the UFIDA U8 OA test.JSP file, which can trigger a pop-up using the\<script>tag.

## Vulnerability Impact

UFIDA U8 OA

## Recurrence of vulnerabilities

The login page is as follows

![image](https://khykhy.oss-cn-hangzhou.aliyuncs.com/4881ce3dc4508ae81b24857e3066ae2.png)



Verify POC

![image](< https://khykhy.oss-cn-hangzhou.aliyuncs.com/ab73fba58c6d18f0ac4552cab617c2f.png>)

/yyoa/common/js/menu/test.jsp?doType=101\&S1=\<script>alert(1)\</script>
