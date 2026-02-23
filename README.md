# python-basic

name = 'Alice'
print(name, type(name))

is_student = True
print(is_student, type(is_student))

age = 20
print(age, type(age))

score = 80.5
print(isinstance(score, float))
print(score,type(score))

javascript problem in leet code

var map = function(arr, fn) {
    let newArr =[]
    arr.forEach((value,index)=>{
        newArr.push(fn(value,index))
    })
    return newArr
};
