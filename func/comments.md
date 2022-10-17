[https://github.com/ton-blockchain/docs/blob/master/docs/func/comments.md]

Комментарии

FunC имеет однострочные комментарии, которые начинаются с ;; (двойные ;).

Например:

int x = 1; ;; assign 1 to x


Он также имеет многострочные комментарии, которые начинаются с {- и заканчиваются -}. Обратите внимание, что в отличие от многих других языков, многострочные комментарии FunC могут быть вложенными. Например:


{- This is a multi-line comment
    {- this is a comment in the comment -}
-}
