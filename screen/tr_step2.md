### Screen Ve Code CLI
Burada size Screen aracının kullanımını Code CLI ile göstereceğim
```bash
# İlk Önce bir screen sessionu oluşturuyoruz
screen -s code-cli
```
Ardından programımımızı çalıştırıyoruz
```bash
./code tunnel
```
Tünelimiz çalışmaya başladığına göre bu sessionu bırakabiliriz:
```bash
Ctrl A + D
```
Sessionu Şu Şekilde görebiliriz:

```bash
screen -ls
```