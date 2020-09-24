# Kotlin import

#### 널 안전성

객체 타입의 변수에 널 값의 허용 여부를 구분하지 않던 자바와 달리, 코틀린은 이를 명확히 구분합니다, 또한 널 값의 허용 여부를 컴파일 단계에서 검사하므로 런타임에서 발생하는 오류를 대폭 줄일 수 있습니다.

Kotlin 

// 널 값을 허용하는 문자열 타입(String?)

val foo:String? = nill



// 널 값을 허용하지 않는 문자열 타입(String)

val bar : String = "bar"



#### 가변/ 불변 구분

널 값의 허용 여부를 구분하는 것과 유사하게 코틀린에서는 변수 및 변수에 할당 된 값의 불변 여부를 구별합니다. 

변수의 불변 여부. 즉 최초 생성 시 할당된 값을 이후에도 변경 할 수 있는지 여부는 변수 선언시에 사용하는 키워드인 `val`과 `var`로 구별합니다.

값을 한번 할당하고 나면 그 후에 변경할 수 없는 변수는 val을 사용하며 선언하며, 이는 자바에서 final 키워드를 붙인 변수와 동일 합니다, 이와 달리 할당된 값을 자유자재로 바꿀 수 있는 변수는 var로 선언하며, 이는 자바에서 final 키워드 없이 선언하는 변수와 동일합니다.
