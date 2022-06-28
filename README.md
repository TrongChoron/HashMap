<h1 align="center">❤❤❤ HASHMAP ❤❤❤</h1>
<h2>HashMap lưu trữ một item dưới dạng "key/value". Key và value sẽ thuộc kiểu dữ liệu bất kỳ, và có thể truy cập các 
 giá trị của HashMap bằng một key cụ thể.
 Ảnh phía dưới chính là minh họa.</h2>

<img src="https://cdn.educba.com/academy/wp-content/uploads/2019/11/hashmap-in-java-1.png"/>
<h2>Key trong HashMap vẫn có thể là null và có thể có nhiều giá trị null.</h2>

## Khai báo của Class HashMap:
```java
public class HashMap<K,V> extends AbstractMap<K,V>
    implements Map<K,V>, Cloneable, Serializable
```
## Trong đó:
> K: là kiểu key để lưu trữ \
> V: là kiểu giá trị được ánh xạ

## Khởi tạo một HashMap

```java
import java.util.HashMap;
// Khai báo một HashMap có tên là mapObject
// Có key là Integer và value là HashMapObject
 Map<Integer, HashMapObject> mapObject = new HashMap<>();
```
