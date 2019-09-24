# Python


public
아무 밑줄이 접두사에 없어야 함
ex)num

private
두개의 밑줄 __이 접두사여야 함
ex)__num

protected
한 개의 밑줄_이 접두사여야 함
ex)_num

접미사는 밑줄이 한 개까지만 허용
ex)__num_

접미사의 밑줄이 두 개 이상이면 public으로 간주

ex)__num__

``` python
class AccessModifier:
    
    def __init__(self):
        self.publicNum = "public"  #public 선언
        self.__privateNum = "private" #private 선언
        self._protectedNum = "protected" #protected 선언


```







