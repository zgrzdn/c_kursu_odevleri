#### Aşağıda bildirimi yapılmış olan *remove_str* isimli fonksiyonu tanımlayınız. 

+ Fonksiyon birinci parametresine adresi gönderilen yazıdan ikinci paremtresine adresi gönderilen yazıyı silmeli.
+ Eğer *p1* adresindeki yazıda *p2* adresindeki yazıdan birden fazla varsa yalnızca birincisi silinecek.
+ Fonksiyonun geri dönüş değeri *p1* adresi

#### Tanımladığınız fonksiyonu aşağıdaki kodla test edebilirsiniz:

```
char *remove_str(char *p1, const char *p2);

int main()
{
	char s1[] = "yine yagmur yagiyor it's raining again";
	char s2[] = "yagmur";

	printf("(%s)\n", s1);

	remove_str(s1, s2);

	printf("(%s)\n", s1);
	//(yine  yagiyor it's raining again)
}
```
