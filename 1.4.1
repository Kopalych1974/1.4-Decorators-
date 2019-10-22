# Написать декоратор - логгер. Он записывает в файл дату и время вызова функции, имя функции, аргументы, 
№ с которыми вызвалась и возвращаемое значение.



from datetime import datetime
from inspect import signature

def logger(some_func):
    def wrapped(*args, **kwargs):
        now = datetime.now()
        function_name = some_func.__name__

        sig = signature(some_func)
        ba = sig.bind(*args, **kwargs)
        args = ba.args
        kwargs = ba.kwargs

        result = some_func(*args, **kwargs)

        f = open ('log.txt', 'w')
        f.write(str(now) + '\t' + str(function_name) + '\t' +
                str(args) + str(kwargs) + '\t' +
                str(result) + '\t' + '\n')
        f.close()
        return

    return wrapped
        #print(now)


@logger
def say_something(*args, **kwargs):
    return 'return_value'

say_something('Here', 'we will pass ', name='the arguments' )

