#### Bir yazının sonuna başka bir yazının olup olmadığını sınayan *is_atend* isimli fonksiyonu tanımlayınız.

+ Fonksiyonun birinci parametresi *(p1)* sınamanın yapılacağı yazı adresi. `(bugun hava cok guzel)`
+ Fonksiyonun ikinci parametresi *(p2)* sonda bulunması gereken yazının adresi  `(guzel)`
+ Fonksiyonun geri dönüş değeri sınamanın sonucu *(zero / non-zero)*

```
int is_atend(const char *p1, const char *p2);

int main()
{
	char s1[] = "bugun hava cok guzel";
	char s2[] = "guzel";

	if (is_atend(s1, s2))
		printf("(%s) yazisinin sonunda (%s) yazisi var\n", s1, s2);
	else
		printf("(%s) yazisinin sonunda (%s) yazisi yok\n", s1, s2);
}
```
