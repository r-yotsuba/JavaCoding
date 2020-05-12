## thisの使用
```
class Car{
    String name;
    void setName(String name){
        this.name = name;
    }
}
```
this演算子を使用することで、メンバ変数とローカル変数を明示的に区別化。  
this.nameがどのnameを指すかが明確で、可読性が上がる  

## 逆コンパイル
クラスファイルのみしかない場合に、javaファイルを生成  
```
> javap Car
```