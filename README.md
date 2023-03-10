# aviator



[![Maven Central](https://img.shields.io/maven-central/v/com.googlecode.aviator/aviator.svg?label=maven%20central)](https://search.maven.org/search?q=g:com.googlecode.aviator%20AND%20aviator)

[ð English Documentation](README-EN.md) | ð ä¸­æææ¡£

----------------------------------------

`AviatorScript` æ¯ä¸é¨é«æ§è½ãè½»éçº§å¯å®¿äº JVM ï¼åæ¬ Android å¹³å°ï¼ä¹ä¸çèæ¬è¯­è¨ã

# ç¹æ§ä»ç»

1. æ¯ææ°å­ãå­ç¬¦ä¸²ãæ­£åè¡¨è¾¾å¼ãå¸å°å¼ãæ­£åè¡¨è¾¾å¼ç­[åºæ¬ç±»å](https://www.yuque.com/boyan-avfmj/aviatorscript/lvabnw)ï¼å®æ´æ¯æææ Java è¿ç®ç¬¦åä¼åçº§ç­ã
2. [å½æ°](https://www.yuque.com/boyan-avfmj/aviatorscript/gl2p0q)æ¯ä¸ç­å¬æ°ï¼æ¯æ[é­ååå½æ°å¼ç¼ç¨](https://www.yuque.com/boyan-avfmj/aviatorscript/ksghfc)ã
2. åç½® [bigint](https://www.yuque.com/boyan-avfmj/aviatorscript/lvabnw#a0Ifn)/[decmal](https://www.yuque.com/boyan-avfmj/aviatorscript/lvabnw#QbV7z) ç±»åç¨äºå¤§æ´æ°åé«ç²¾åº¦è¿ç®ï¼æ¯æ[è¿ç®ç¬¦éè½½](https://www.yuque.com/boyan-avfmj/aviatorscript/ydllav#5hq4k)å¾ä»¥è®©è¿äºç±»åä½¿ç¨æ®éçç®æ¯è¿ç®ç¬¦ `+-*/ `åä¸è¿ç®ã
3. å®æ´çèæ¬è¯­æ³æ¯æï¼åæ¬å¤è¡æ°æ®ãæ¡ä»¶è¯­å¥ãå¾ªç¯è¯­å¥ãè¯æ³ä½ç¨ååå¼å¸¸å¤çç­ã
4. [å½æ°å¼ç¼ç¨](https://www.yuque.com/boyan-avfmj/aviatorscript/ksghfc)ç»å [Sequence æ½è±¡](https://www.yuque.com/boyan-avfmj/aviatorscript/yc4l93)ï¼ä¾¿æ·å¤çä»»ä½éåã
5. è½»éåç[æ¨¡åç³»ç»](https://www.yuque.com/boyan-avfmj/aviatorscript/rqra81)ã
6. å¤ç§æ¹å¼ï¼æ¹ä¾¿å°[è°ç¨ Java æ¹æ³](https://www.yuque.com/boyan-avfmj/aviatorscript/xbdgg2)ï¼å®æ´æ¯æ Java [èæ¬ API](https://www.yuque.com/boyan-avfmj/aviatorscript/bds23b)ï¼æ¹ä¾¿ä» Java è°ç¨èæ¬ï¼ã
7. ä¸°å¯çå®å¶éé¡¹ï¼å¯ä½ä¸ºå®å¨çè¯­è¨æ²ç®±åå¨åè½è¯­è¨ä½¿ç¨ã
8. è½»éåï¼é«æ§è½ï¼ASM æ¨¡å¼ä¸éè¿ç´æ¥å°èæ¬ç¿»è¯æ JVM å­èç ï¼[è§£éæ¨¡å¼](https://www.yuque.com/boyan-avfmj/aviatorscript/ok8agx)å¯è¿è¡äº Android ç­éæ  Java å¹³å°ã

ä½¿ç¨åºæ¯åæ¬ï¼
1. è§åå¤æ­åè§åå¼æ
2. å¬å¼è®¡ç®
3. å¨æèæ¬æ§å¶
4. éåæ°æ® ELT ç­
â¦â¦

**æ¨èä½¿ç¨çæ¬ 5.2.6 åä»¥ä¸**



# Dependency

```xml
<dependency>
  <groupId>com.googlecode.aviator</groupId>
  <artifactId>aviator</artifactId>
  <version>{version}</version>
</dependency>
```

å¯ä»¥å¨ [search.maven.org](https://search.maven.org/search?q=g:com.googlecode.aviator%20AND%20a:aviator&core=gav) æ¥çå¯ç¨ççæ¬ã

# å¿«éå¼å§

1. ä¸è½½ [aviator](https://raw.githubusercontent.com/
/aviator/master/bin/aviator) shell å°æä¸ªç®å½ï¼æå¥½æ¯å¨ç³»ç»ç `PATH` ç¯å¢åéåï¼ï¼æ¯å¦ `~/bin/aviator`:

```sh
$ wget https://raw.githubusercontent.com/mavenAoteman/aviator/master/bin/aviator
$ chmod u+x aviator
```

2. æ§è¡  `aviator`  å½ä»¤ï¼å°èªå¨ä¸è½½ææ°ææ¡£çæ¬ aviator jar å°  `~/.aviatorscript`  ä¸çå®è£ç®å½å¹¶è¿è¡ï¼

```sh
$ aviator
Downloading AviatorScript now...
  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current
                                 Dload  Upload   Total   Spent    Left  Speed
100   153  100   153    0     0    111      0  0:00:01  0:00:01 --:--:--   111
100 1373k  100 1373k    0     0   689k      0  0:00:01  0:00:01 --:--:--  689k
Usage: java com.googlecode.aviator.Main [file] [args]
     : java com.googlecode.aviator.Main -e [script]
     : java com.googlecode.aviator.Main -v
```

3. å°ä¸é¢è¿ä¸ªèæ¬ä¿å­ä¸ºæä»¶  `hello.av`:

```js
p("Hello, AviatorScript!");

let a = tuple(1, 2, 3, 4, 5);

p("sum of a is: " + reduce(a, +, 0));

let date = new java.util.Date();
p("The year is: "+ getYear(date));
p("The month is: #{getMonth(date)}");
```



4. æ§è¡èæ¬ï¼

```sh
$ aviator hello.av
Hello, AviatorScript!
sum of a is: 15
The year is: 120
The month is: 3
```


æ´è¯¦ç»çè¯·éè¯»[ç¨æ·æå](https://www.yuque.com/boyan-avfmj/aviatorscript/cpow90)ã

# Links


* Documents: <https://www.yuque.com/boyan-avfmj/aviatorscript>
* Changelog: <https://www.yuque.com/boyan-avfmj/aviatorscript/bggwx2>
* Javadoc: <http://fnil.net/aviator/apidocs/>
* Spring boot rule: <https://github.com/mengxiangrui007/spring-boot-rule-jsr94>
* Idea plugin: <https://github.com/yanchangyou/aviatorscript-ideaplugin>
